# House Price Predictor

A machine learning project for predicting house prices using advanced regression techniques. This project includes comprehensive data preprocessing, feature engineering, and model optimization to achieve high accuracy in predictions.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Models Used](#models-used)
- [Data Preprocessing](#data-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Contributing](#contributing)
- [License](#license)

## Introduction
RealEstateValuePredictor is designed to predict house prices using a variety of regression models. It includes detailed data preprocessing steps to handle missing values and outliers, and feature engineering to enhance model performance.

## Features
- Comprehensive data preprocessing
- Advanced feature engineering
- Utilization of multiple regression models:
  - LGBMRegressor
  - XGBRegressor
  - CatBoostRegressor
- Model optimization using GridSearchCV
- Feature importance analysis and visualization

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/rohanag03/House-Price-Prediction.git
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Load the dataset:
    ```python
    train = pd.read_csv("path/to/train.csv")
    test = pd.read_csv("path/to/test.csv")
    ```
2. Run the preprocessing and model training script:
    ```python
    python housepricepredict-regression.py
    ```

## Models Used
- **LGBMRegressor**: LightGBM model optimized for speed and performance.
- **XGBRegressor**: Extreme Gradient Boosting model known for its robustness.
- **CatBoostRegressor**: Categorical Boosting model that handles categorical data efficiently.

## Data Preprocessing
- Handling missing values
- Outlier detection and replacement
- Log transformation of skewed data

## Feature Engineering
- Creation of new features to enhance model performance
- Encoding categorical variables
- Scaling and normalization of numerical features

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
