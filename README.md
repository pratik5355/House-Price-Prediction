# House Price Prediction

This repository contains a machine learning project focused on predicting house prices using the Boston Housing Dataset. The goal of this project is to build and evaluate predictive models that can estimate the median value of owner-occupied homes in Boston suburbs based on various features.

## Dataset
The dataset used in this project is the famous Boston Housing Dataset (`boston_housing.csv`), originally sourced from the StatLib archive and available on Kaggle. It contains various socioeconomic and housing-related attributes.

**Key Features:**
- `CRIM`: Per capita crime rate by town
- `ZN`: Proportion of residential land zoned for lots over 25,000 sq.ft.
- `INDUS`: Proportion of non-retail business acres per town
- `CHAS`: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
- `NOX`: Nitric oxides concentration (parts per 10 million)
- `RM`: Average number of rooms per dwelling
- `AGE`: Proportion of owner-occupied units built prior to 1940
- `DIS`: Weighted distances to five Boston employment centres
- `RAD`: Index of accessibility to radial highways
- `TAX`: Full-value property-tax rate per $10,000
- `PTRATIO`: Pupil-teacher ratio by town
- `B`: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town
- `LSTAT`: % lower status of the population
- `MEDV`: Median value of owner-occupied homes in $1000's (Target Variable)

## Setup and Installation

To run this project locally, make sure you have Python installed. You can use Jupyter Notebook or Google Colab to run the code.

1. Clone the repository:
   ```bash
   git clone https://github.com/pratik5355/House-Price-Prediction.git
   cd House-Price-Prediction
   ```

2. Open the notebook `House_Price_Prediction.ipynb` in your preferred environment (Jupyter / VS Code / Colab) to view the data processing, EDA, and model training.

## Methodology
The notebook follows a standard Machine Learning pipeline:
1. **Data Loading & Exploration:** Checking for missing values and understanding data distributions.
2. **Exploratory Data Analysis (EDA):** Visualizing correlations between features and the target variable (`MEDV`).
3. **Data Preprocessing:** Scaling features and splitting data into training and testing sets.
4. **Model Training:** Training regression models (like Linear Regression, Random Forest) to predict house prices.
5. **Model Evaluation:** Using metrics like Mean Squared Error (MSE) and R-squared to evaluate model performance.

## Results
(Refer to the notebook outputs to see the detailed evaluation metrics and performance comparisons for the trained models.)

---
Feel free to fork this project or contribute by opening issues/pull requests!
