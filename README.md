# Future Sales Prediction with Machine Learning

Welcome to the "Future Sales Prediction with Machine Learning" project! This repository demonstrates how to predict future sales using machine learning techniques, specifically focusing on the impact of advertising expenditures across various media channels.

## 📌 Project Overview

Businesses often face the challenge of forecasting future sales to optimize inventory, plan marketing strategies, and manage resources effectively. This project leverages machine learning to predict sales based on historical data, providing valuable insights for decision-making.

## 📊 Dataset

The dataset used in this project contains information about advertising expenditures across three media channels:

* **TV**: Advertising cost spent in dollars for advertising on TV
* **Radio**: Advertising cost spent in dollars for advertising on Radio
* **Newspaper**: Advertising cost spent in dollars for advertising on Newspaper
* **Sales**: Number of units sold

The data is sourced from [Kaggle](https://www.kaggle.com/datasets/uciml/advertising) and is available in CSV format.

## 🛠️ Technologies Used

* **Programming Language**: Python
* **Libraries**:

  * `pandas`: Data manipulation and analysis
  * `numpy`: Numerical computations
  * `scikit-learn`: Machine learning algorithms
  * `plotly`: Data visualization([precom][1], [Amazon Web Services, Inc.][2])

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/ManishBhojak/Future-Sales-Prediction-With-Machine-Learning.git
cd Future-Sales-Prediction-With-Machine-Learning
```



### 2. Install Dependencies

```bash
pip install -r requirements.txt
```



### 3. Run the Jupyter Notebook

```bash
jupyter notebook futuresalesprediction.ipynb
```



This will open the Jupyter Notebook in your browser, where you can follow along with the steps to load the dataset, preprocess the data, train a machine learning model, and make predictions.

## 🔍 Project Workflow

1. **Data Loading**: Load the dataset into a pandas DataFrame.
2. **Exploratory Data Analysis (EDA)**: Visualize relationships between advertising expenditures and sales using scatter plots.
3. **Data Preprocessing**: Handle missing values, encode categorical variables if any, and split the data into training and testing sets.
4. **Model Training**: Train a machine learning model (e.g., Linear Regression) on the training data.
5. **Model Evaluation**: Evaluate the model's performance using metrics like Mean Absolute Error (MAE) or R-squared.
6. **Prediction**: Use the trained model to predict future sales based on new advertising expenditure data.([Analytics Vidhya][3], [GitHub][4])

## 📈 Visualizations

The project includes various visualizations to understand the data better:

* **Scatter Plots**: Show the relationship between sales and advertising expenditures on TV, Radio, and Newspaper.
* **Correlation Matrix**: Displays the correlation between different variables.([GitHub][4])
