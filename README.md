# Gold Price Prediction with Random Forest Regressor


## 1. Project Overview

This project implements a Random Forest Regressor to predict gold prices based on various economic and financial indicators. The goal is to build a model that can accurately forecast gold prices using historical data, such as interest rates, stock market indices, and currency exchange rates.




## 2. Dataset Source

https://www.kaggle.com/datasets/altruistdelhite04/gold-price-data

## 3. Features
- **Data Preprocessing**: Data cleaning, feature engineering, handling missing values, and splitting into training and testing sets.
- **Model Training**: Training a Random Forest Regressor using scikit-learn.
- **Model Evaluation**: Evaluating the performance of the model using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R²).
- **Visualization**: Visualization of feature relationships and residual plots to assess the model's accuracy.



## 4. Project Structure
    ├── gld_price_data.csv          # Dataset file 
    ├── gold_price_prediction.ipynb # Jupyter notebook with end-to-end implementation
    ├── README.md                   # Project documentation
    ├── requirements.txt            # Python dependencies
    └── .gitignore                  # Files to be ignored in version control

## 5. Getting Started

### Prerequisites
- Python 3.9 or higher
- Jupyter Notebook
- scikit-learn
- pandas
- matplotlib
- numpy
- seaborn

### Installation
1. Clone the repository:

```python
    git clone https://github.com/adamsdossantos/gold_price.git
    
```
2. Create a virtual environment and activate it:
```python
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required packages:
```python
   pip install -r requirements.txt
```

4. Launch the Jupyter Notebook:
```python
    jupyter notebook gold_price_prediction.ipynb
```
## 6. Usage

Open the gold_price_prediction.ipynb file and follow the step-by-step instructions provided in the notebook. The notebook includes:

- **Data Loading and Preprocessing**: Load data from the 'gld_price_data.csv' and perform necessary preprocessing like handling missing values, encoding categorical variables, and feature scaling.
- **Model Training**: Train a Random Forest Regressor with adjustable hyperparameters like n_estimators, max_depth, and max_features to optimize performance.
- **Model Evaluation**:  Evaluate the model using metrics such as MAE, RMSE, and R² to understand how well the model predicts car prices.
- **Visualization**:  Visualize the most important features influencing gold prices and plot predictions versus actual gold prices for a detailed performance analysis.


## 7. Results in Test

    | Metric    |  Value |
    |-----------|--------|
    | Mean Absolute Error  |  1.34   |
    | Root Mean Squared Error	 |  2.40   |
    | R-squared (R²)    | 0.98  |


## 8. Contributing

Feel free to open issues or submit pull requests if you find any bugs or want to improve the project.

## 9. License

This project is licensed under the MIT License - see the LICENSE file for details.







