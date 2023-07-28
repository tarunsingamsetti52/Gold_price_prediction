# Gold Price Prediction using Machine Learning (Multiple Linear Regression)

## Overview

This project aims to predict the gold price using machine learning techniques, specifically employing Multiple Linear Regression. The dataset used for training and testing the model spans from January 2, 2008, to May 16, 2018. The dataset includes several attributes, such as SPX, GLD, USO, SLV, and EUR/USD, which are utilized as features to predict the gold price.

## Dataset

The dataset used for this project is available in a CSV format and contains the following attributes:

- Date: The date of the data entry (format: YYYY-MM-DD).
- SPX: The Standard & Poor's 500 (S&P 500) index.
- GLD: The gold price.
- USO: United States Oil Fund LP (USO) stock price.
- SLV: iShares Silver Trust (SLV) stock price.
- EUR/USD: The exchange rate between the Euro and the US Dollar.

The dataset covers historical data from January 2, 2008, to May 16, 2018, with daily frequency.

## Requirements

To run the code and perform the gold price prediction using Multiple Linear Regression, you'll need the following:

- Python (version 3.6 or higher)
- Jupyter Notebook or any Python IDE
- Libraries: pandas, numpy, scikit-learn

Ensure that you have the necessary libraries installed by running:

```
pip install pandas numpy scikit-learn
```

## Methodology

The project follows these general steps:

1. **Data Preprocessing**: Load the dataset, handle missing values (if any), and format the data appropriately.

2. **Feature Selection**: Select the relevant features (SPX, USO, SLV, EUR/USD) that will be used as input for the Multiple Linear Regression model.

3. **Data Split**: Divide the dataset into a training set and a testing set. The training set will be used to train the model, and the testing set will be used to evaluate its performance.

4. **Model Training**: Implement Multiple Linear Regression using scikit-learn's `LinearRegression` class. Train the model using the training data.

5. **Prediction**: Apply the trained model to predict gold prices for the testing set.

6. **Evaluation**: Assess the model's performance by comparing the predicted gold prices with the actual gold prices from the testing set. Common metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) can be used for evaluation.

7. **Visualization**: Visualize the predicted gold prices alongside the actual gold prices to observe the model's performance graphically.

## Usage

1. Clone the repository or download the project files to your local machine.

2. Ensure you have installed all the necessary requirements as mentioned in the "Requirements" section.

3. Open the Jupyter Notebook or your preferred Python IDE.

4. Navigate to the directory where the project files are located.

5. Open the notebook file (e.g., `gold_price_prediction(1).ipynb`).

6. Run the code cells in the notebook sequentially to perform data preprocessing, model training, and evaluation.

## Results

The model's performance will be displayed through evaluation metrics and visualizations in the notebook. Keep in mind that the prediction results are based on historical data, and actual market conditions may differ.

