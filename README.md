# ChurnSense
A smart AI-powered solution for predicting and preventing customer churn with actionable insights.
# Customer Churn Prediction

## Overview
Customer attrition, or churn, occurs when customers stop doing business with a company. Churn can significantly impact a company's revenue, making it crucial for businesses to understand why customers leave and take proactive steps to reduce churn rates.

By identifying at-risk customer segments and implementing retention strategies, businesses can mitigate churn. Leveraging data and machine learning techniques, we can predict which customers are likely to leave and take preventive actions before they decide to do so.

## Project Description
This project aims to build a predictive model for customer churn using the **Telco Customer Churn dataset**. We employ classification algorithms to model customers who have left. The project utilizes Python tools such as **pandas** for data manipulation and **matplotlib** for visualizations.

## Steps Involved in Predicting Customer Churn

### 1. Importing Libraries
- Load essential Python libraries such as pandas, numpy, matplotlib, seaborn, and scikit-learn.

### 2. Loading Dataset
- Import the Telco Customer Churn dataset for analysis.

### 3. Exploratory Data Analysis (EDA)
- Understand dataset structure, check for missing values, and visualize data distributions.

### 4. Handling Outliers using IQR Method
- Identify and remove outliers to ensure model accuracy.

### 5. Cleaning and Transforming Data
- Handle missing values and prepare data for machine learning models.

### 6. One-Hot Encoding
- Convert categorical variables into numerical format for model training.

### 7. Rearranging Columns
- Organize dataset for better readability and processing.

### 8. Feature Scaling
- Standardize numerical features for optimal model performance.

### 9. Feature Selection
- Select the most relevant features for training the model.

### 10. Model Predictions
#### Machine Learning Models Used:
- **Logistic Regression**
- **Support Vector Classifier (SVC)**
- **Decision Tree Classifier**
- **K-Nearest Neighbors (KNN) Classifier**

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn

## Dataset
The dataset used is the **Telco Customer Churn dataset**, which includes customer demographics, account information, and service details.

## How to Use
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/CustomerChurnPrediction.git
   cd CustomerChurnPrediction
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the script:
   ```sh
   python churn_prediction.py
   ```

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

---

### 🚀 Stay Ahead of Churn, Retain More Customers!

