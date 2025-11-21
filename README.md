# Temperature Trend Analysis and Prediction (2020–2025)

## Overview of the Project

This project analyzes daily temperature trends from 2020 to September 2025 and predicts October 2025 temperatures using the Random Forest regression algorithm. The model's predictions for October 2025 are compared against the actual recorded temperatures to assess accuracy. The workflow demonstrates practical data science methods and end-to-end reproducibility.

## Features

- Loads historical and actual temperature datasets from Google Drive
- Parses and preprocesses daily temperature time-series data
- Visualizes temperature trends over multiple years
- Engineers lag features for improved prediction
- Trains and applies a Random Forest regression model
- Predicts daily October 2025 temperatures
- Tabulates and compares predicted vs actual values
- Calculates key error metrics (MAE, RMSE, MAPE, accuracy)
- Displays user-friendly result tables and plots

## Technologies/Tools Used

- Python 3 (Colab, Jupyter Notebook)
- Pandas (data manipulation and analysis)
- Scikit-learn (machine learning, Random Forest)
- Matplotlib (data visualization)
- Google Colab & Google Drive (cloud data management)

## Steps to Install & Run the Project

1. Clone or download this repository from GitHub.
2. Upload your `dataset1.csv` (2020–Sep 2025) and `dataset2.csv` (October 2025) files to your Google Drive folder named `vityarthiproj`.
3. Open the main notebook/script in Google Colab.
4. Mount Google Drive in Colab at the start of your notebook:

5. Verify file paths in the code match your Google Drive directory.
6. Run the notebook cell-by-cell to process data, train the model, and generate results.

## Instructions for Testing

- Ensure both datasets are present in `/content/drive/MyDrive/vityarthiproj/`.
- Execute all code cells in the notebook.
- View printed results and generated plots for actual vs predicted temperature comparison.
- Confirm error/accuracy metrics in output summary.
- For troubleshooting, check that date columns are parsed correctly and column names match your files.

## Screenshots

### 1. Temperature Trend (2020 to Sept 2025)
This plot shows the temperature trend over multiple years:
![Temperature Trend](https://github.com/user-attachments/assets/709504b0-aee8-4ebf-8118-a985cac2580e)
### 2. Predicted vs Actual Table (October 2025)
Table showing Date, Actual Temperature, Predicted Temperature, and Error:
![Comparison Table](https://github.com/user-attachments/assets/49832019-41d8-4f5e-9bcb-a9c32e332948)

### 3. Actual vs Predicted Temperature Plot (October 2025)
Plot comparing actual and predicted temperatures for October 2025:
![Actual vs Predicted Plot](https://github.com/user-attachments/assets/00663cc7-babd-456e-ac2e-ff2366fc9b16)



