# House Price Advanced Regression

## Overview
This project focuses on predicting house prices using advanced regression techniques. A comparative analysis of various machine learning models was conducted to determine the best-performing model.

## Features
- **House Price Prediction**: Uses multiple regression models to predict house prices.
- **Comparative Analysis**: Evaluates different models based on performance metrics.
- **Feature Engineering**: Implements data preprocessing techniques for better accuracy.

## Models Evaluated
- **Linear Regression**
- **Ridge Regression**
- **Lasso Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **XGBoost Regressor**
- **LightGBM**

## Dataset
- Contains various house features such as location, size, number of rooms, and amenities.
- Preprocessing includes handling missing values, feature scaling, and encoding categorical variables.

## Technologies Used
- Python
- Scikit-learn
- XGBoost & LightGBM
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook / Google Colab

## Installation
To set up the project, follow these steps:

```bash
# Clone the repository
git clone https://github.com/yourusername/House-Price-Regression.git
cd House-Price-Regression

# Install dependencies
pip install -r requirements.txt
```

## Usage
To train and evaluate the models:

```bash
python train_models.py
```

To make a price prediction:

```bash
python predict.py --input data/sample_house.csv
```


| Models |
|--------|
| Linear Regression | 
| Ridge Regression | 
| Lasso Regression | 
| Decision Tree Regressor |
| Random Forest Regressor |
| Gradient Boosting | 
| XGBoost | 

## Future Enhancements
- Hyperparameter tuning for improved accuracy.
- Deploy the model as a web application.
- Include more features such as neighborhood crime rates and school proximity.
