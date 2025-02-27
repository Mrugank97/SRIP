# SRIP Selection Task Project

## Overview
This project classifies human activities using the **UCI-HAR dataset**, which contains sensor data (accelerometer & gyroscope) from 30 participants performing six activities.

## Preprocessing
1. Extract raw accelerometer data.
2. Use `CombineScript.py` & `MakeDataset.py` to organize and split data.
3. Focus on the first 10 seconds (500 samples/activity).

## Methods
### Machine Learning (ML)
- **Models**: Decision Tree, Random Forest, SVM, Logistic Regression.
- **Feature Engineering**: Use **TSFEL** to extract features and compare with dataset-provided features.

### Deep Learning (DL)
- **Models**: LSTM, 1D CNN trained on raw data.
- **Comparison**: ML models use features, DL models leverage time-series directly.

## Results & Insights
- Visualization of activity waveforms.
- PCA applied to raw & TSFEL features.
- ML vs. DL performance comparison.
- Featurization impact on ML models.

## How to Run
1. Place scripts in the dataset folder.
2. Run `CombineScript.py` & `MakeDataset.py`.
3. Use the Jupyter Notebook to train & evaluate models.


## Summary
All insights, detailed analysis, and results are available in the Jupyter Notebook (`.ipynb` file) along with the complete code implementation. The notebook includes step-by-step explanations, visualizations, and model performance comparisons to provide a comprehensive understanding of the project.
All insights and analysis are available in the Jupyter Notebook (`.ipynb` file) along with the code.
This project explores **HAR using ML & DL models**, highlighting feature engineering's impact on ML and DL's ability to handle raw data.
