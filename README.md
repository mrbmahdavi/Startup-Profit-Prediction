# Startup-Profit-Prediction
Startup Profit Prediction with Multiple Linear Regression

## 📋 Project Overview
This project implements a Multiple Linear Regression model to predict the profitability of startups based on various financial and operational factors. The model was trained on a dataset containing information about 50 startups, including their R&D spending, administration costs, marketing expenses, and location.

## 🎯 Objective
To build a predictive model that can estimate a startup's profit based on:
- R&D Spending
- Administration Costs
- Marketing Expenses
- Geographic Location (State)

## 📊 Dataset
The dataset (`50_Startups.csv`) contains information about 50 startups with the following features:
- **R&D Spend**: Investment in research and development
- **Administration**: Administrative expenses
- **Marketing Spend**: Marketing budget
- **State**: Geographic location (California, Florida, or New York)
- **Profit**: Target variable to predict

## 🛠️ Technologies Used
- Python 3
- Pandas (Data manipulation)
- NumPy (Numerical operations)
- Scikit-learn (Machine learning models)
- Matplotlib (Data visualization)

## 🔧 Implementation Steps

### 1. Data Preprocessing
- Loaded and explored the dataset
- Split data into features (X) and target variable (y)
- Handled categorical data (State) using One-Hot Encoding
- Split data into training and test sets (80/20 ratio)

### 2. Model Training
- Implemented Multiple Linear Regression using Scikit-learn
- The model automatically handles dummy variable trap
- Trained on the preprocessed dataset

### 3. Model Evaluation & making predictions
- Made predictions on the test set
- Calculated performance metrics:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R-squared

## 🚀 How to Use
1. Clone the repository
2. Install required dependencies: `pandas`, `numpy`, `scikit-learn`, `matplotlib`
3. Run the Jupyter notebook to:
   - Preprocess the data
   - Train the model
   - Make predictions
   - Evaluate performance

## 📝 Example Prediction
For a startup with:
- R&D Spend: $160,000
- Administration: $130,000
- Marketing Spend: $300,000
- State: California

The predicted profit would be: **$181,566.92**

## 📁 Files
- `Jozveh_Multiple_linear_regression.ipynb`: Main Jupyter notebook with complete implementation
- `50_Startups.csv`: Dataset used for training and testing


## 📄 License
This project is open source and available under the [MIT License](LICENSE).
