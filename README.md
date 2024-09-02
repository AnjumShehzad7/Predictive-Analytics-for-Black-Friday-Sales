# Predictive Analytics for Black Friday Sales

## Project Overview
This project aims to predict the purchase amount made by customers during Black Friday sales at a retail store. By leveraging data from previous transactions, we explore various machine learning models to accurately forecast customer spending. This project serves as an excellent example of applying data science techniques, such as feature engineering and regression analysis, to a real-world problem.

## Dataset Information
The dataset used in this project comprises 550,069 sales transactions recorded at a retail store. The data is structured with 12 columns that provide various details about the customers and the products they purchased.

### Dataset Attributes

| Column ID | Column Name                | Data Type | Description                           | Masked |
|-----------|----------------------------|-----------|---------------------------------------|--------|
| 0         | User_ID                    | int64     | Unique Id of customer                 | False  |
| 1         | Product_ID                 | object    | Unique Id of product                  | False  |
| 2         | Gender                     | object    | Sex of customer                       | False  |
| 3         | Age                        | object    | Age of customer                       | False  |
| 4         | Occupation                 | int64     | Occupation code of customer           | True   |
| 5         | City_Category              | object    | City category of customer             | True   |
| 6         | Stay_In_Current_City_Years | object    | Number of years of stay in city       | False  |
| 7         | Marital_Status             | int64     | Marital status of customer            | False  |
| 8         | Product_Category_1         | int64     | Primary category of the product       | True   |
| 9         | Product_Category_2         | float64   | Secondary category of the product     | True   |
| 10        | Product_Category_3         | float64   | Tertiary category of the product      | True   |
| 11        | Purchase                   | int64     | Purchase amount (Target Variable)     | False  |

**Download Link**: [Black Friday Sales Prediction Dataset](https://www.kaggle.com/kkartik93/black-friday-sales-prediction)

## Problem Statement
The primary goal of this project is to develop a machine learning model that predicts the purchase amount based on the given attributes of customers and products.

## Libraries and Tools
The following Python libraries and tools were used in this project:

- **pandas**: For data manipulation and analysis.
- **matplotlib**: For creating static, animated, and interactive visualizations in Python.
- **seaborn**: For making statistical graphics.
- **scikit-learn**: For implementing machine learning algorithms and evaluation metrics.

## Machine Learning Algorithms
The following algorithms were explored and implemented to predict the purchase amount:

1. **Linear Regression**
2. **Decision Tree**
3. **Random Forest**
4. **Extra Trees**

## Project Workflow
1. **Data Preprocessing**: Cleaning the data, handling missing values, encoding categorical variables, and feature scaling.
2. **Exploratory Data Analysis (EDA)**: Visualizing data to uncover insights and patterns.
3. **Model Development**: Training and evaluating different machine learning models.
4. **Model Evaluation**: Using metrics like RMSE, MAE, and R^2 to measure the performance of the models.

## Future Work
There are several directions for future work to enhance the performance and robustness of the predictive models:

- **Hyperparameter Tuning**: Fine-tuning model parameters to improve accuracy and generalization.
- **Exploration of Different Models**: Trying advanced models such as Gradient Boosting Machines, XGBoost, or Neural Networks.
- **Creation of New Attributes**: Engineering new features that might provide better insights and improve model predictions.
- **Normalization**: Applying different normalization techniques to the dataset for potentially better performance.

## Conclusion
This project demonstrates the application of data science and machine learning techniques to predict customer purchase behavior during Black Friday sales. The results obtained from various models provide a solid foundation for further exploration and refinement.
