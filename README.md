# Teleco-Customer-Churn-Prediction

**Teleco-Customer-Churn-Prediction** is a data analysis project aimed at understanding the factors that influence customer churn in the telecom industry. Using a publicly available telecom dataset, this project performs detailed Exploratory Data Analysis (EDA) to uncover patterns, correlations, and trends that may help telecom companies identify customers at risk of leaving. The analysis includes data cleaning, handling missing values, encoding categorical variables, visualizing key relationships, and summarizing customer behavior across various features like contract type, internet service, tenure, monthly charges, and more. The goal is to extract meaningful insights that can guide future model development or business decisions. Technologies used include Python, pandas, NumPy, matplotlib, and seaborn. This project sets the foundation for building predictive models by first understanding the structure and story within the data.

## 🔍 Key Objectives

- Understand the distribution of churned vs. retained customers  
- Analyze numerical and categorical features  
- Explore relationships between customer attributes and churn  
- Prepare data for future machine learning applications

## 🛠️ Technologies Used

- Python  
- pandas  
- NumPy  
- matplotlib  
- seaborn  
- Jupyter Notebook

## 📁 Project Structure

Teleco-Customer-Churn-Prediction/
├── data/ # Raw dataset
├── notebooks/ # Jupyter notebooks for EDA
├── images/ # Plots and visualizations (optional)
├── README.md # Project documentation
└── requirements.txt # List of Python packages


## 📊 Dataset Features

Some key columns in the dataset include:
- `gender`, `SeniorCitizen`, `Partner`, `Dependents`  
- `tenure`, `PhoneService`, `InternetService`, `Contract`  
- `MonthlyCharges`, `TotalCharges`, and `Churn` (target)

## 🚀 How to Run

1. Clone the repository:  
   `git clone https://github.com/Nandana-pramod/Teleco-Customer-Churn-Prediction.git`

2. Navigate to the project folder:  
   `cd Teleco-Customer-Churn-Prediction`

3. Install dependencies:  
   `pip install -r requirements.txt`

4. Open the EDA notebook:  
   Use Jupyter Notebook or VSCode to explore the `notebooks/` directory and run the analysis.

## 📌 Next Steps

- Build a machine learning model to predict churn  
- Perform feature engineering and model evaluation  
- Deploy the model as a web app using Flask or Streamlit

