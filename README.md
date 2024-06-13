# COGS188 Stock Price Prediction Project

## Group Members
- Lucas Fasting
- Yash Sharma
- Bryan Nguyen

## Project Overview
This project aims to predict future stock prices using various machine learning algorithms and evaluate their effectiveness in trading and generating profit across different stocks and their respective call and put options. 

We evaluated multiple models, including Long Short-Term Memory (LSTM), K-Nearest Neighbors (KNN), and Deep Q-Networks (DQN), to identify the most effective approach. The results indicate that the LSTM model outperforms others in terms of accuracy, making it a promising tool for stock price prediction.

## Prerequisites
To run this project, you need to have the following libraries installed:
- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `keras`
- `statsmodels`
- `tensorflow`

These libraries can be installed using pip:
```bash
pip install pandas numpy matplotlib scikit-learn keras statsmodels tensorflow
```

## How to Run the Program
1. **Google Colab Setup**: This project is designed to be run in Google Colab. Ensure you have access to Google Colab and are logged into your Google account.
2. **Dataset Availability**:
   - One of the datasets is available in the project's GitHub repository.
   - The second dataset, which is too large to be included in the repository, must be downloaded from here [Kaggle](https://www.kaggle.com/datasets/kylegraupe/aapl-options-data-2016-2020).
3. **Download the Large Dataset**:
   - Visit the Kaggle link provided above.
   - Download the dataset and upload it to your Google Drive.
4. **Run the Jupyter Notebook**:
   - Open the `FinalProject_StockPricePrediction_FinalVersion.ipynb` notebook in Google Colab.
   - Follow the instructions in the notebook to load the datasets from your Google Drive and execute the code cells.
