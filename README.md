🚚 Swiggy Delivery Time Prediction using Linear Regression

This project focuses on predicting Swiggy food delivery time using a Machine Learning Linear Regression model. The objective is to analyze delivery-related features and estimate the expected delivery time more accurately.

The project was implemented using Python in Google Colab, following a complete data science workflow including data exploration, preprocessing, modeling, and evaluation. A simulated dataset was used to demonstrate the machine learning process.

📊 Project Workflow

The following steps were performed in this project:

1️⃣ Import Required Libraries
Used Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

2️⃣ Basic Data Exploration
Examined dataset structure, data types, missing values, and summary statistics.

3️⃣ Exploratory Data Analysis (EDA)
Visualized data patterns using:

📈 Histograms – to understand distribution of numerical features

📦 Box Plots – to detect outliers

🔵 Scatter Plots – to analyze relationships between variables

4️⃣ Remove Useless Features
Dropped irrelevant columns that do not contribute to prediction.

5️⃣ Data Preprocessing
Handled missing values and encoded categorical variables.

6️⃣ Feature Selection
Selected the most relevant variables affecting delivery time.

7️⃣ Train–Test Split
Split the dataset into training and testing sets for unbiased evaluation.

8️⃣ Feature Scaling
Standardized numerical features to improve model performance.

9️⃣ Model Building
Implemented a Linear Regression model to predict delivery time.

🔟 Model Evaluation
Evaluated the model using standard regression metrics.

1️⃣1️⃣ Actual vs Predicted Visualization
Compared predicted values with actual delivery times.

1️⃣2️⃣ Comparison Table
Displayed predicted vs actual values for clearer interpretation.

📈 Model Performance
Metric	Value
MAE (Mean Absolute Error)	5.01
RMSE (Root Mean Squared Error)	6.22
R² Score	0.898

The R² score of 0.898 indicates that the model explains approximately 89.8% of the variance in delivery time, showing strong predictive capability.

🛠 Technologies Used

Python

Google Colab

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

🔗 Project Notebook

📎 Google Colab Notebook:
https://colab.research.google.com/drive/1gIHaQxJn7OBoDTlpYvI6cFbb87bCCvX6?usp=sharing

💡 Project Objective

This project demonstrates how machine learning techniques can be applied to delivery service operations to estimate delivery time more accurately. Such predictive models can help improve delivery planning, operational efficiency, and customer satisfaction.
