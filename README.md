# Linear Regression – E-commerce Customer Spending

This project is a beginner-friendly implementation of **Linear Regression** to predict **yearly customer spending** based on customer behavior data from an e-commerce platform.

The goal of this project is to understand the **end-to-end workflow** of a regression problem, including data preprocessing, feature selection, model training, evaluation, and visualization.

---

## 📌 Project Overview
In this project, we analyze customer behavior features such as:
- Average session length
- Time spent on the mobile app
- Length of membership

Using these features, a Linear Regression model is built to predict **Yearly Amount Spent** by customers.

---

## 🧹 Data Preprocessing
The following preprocessing steps were performed:
- Removed non-informative columns (**Email, Address, Avatar**) as they do not contribute to prediction
- Dropped **Time on Website** due to near-zero correlation with the target variable
- Selected only relevant numeric features
- Applied **StandardScaler** to standardize feature values

---

## 🧠 Feature Selection
Feature selection was based on:
- **Correlation analysis**
- Domain understanding of customer behavior

Final features used:
- Avg. Session Length  
- Time on App  
- Length of Membership  

---

## 🤖 Model Used
- **Linear Regression** (scikit-learn)

The dataset was split into training and testing sets, and the model was trained on standardized features.

---

## 📊 Model Evaluation
Model performance was evaluated using:
- **R² Score**
- **RMSE (Root Mean Squared Error)**
- Residual analysis

**Results:**
- R² ≈ **0.99**
- RMSE ≈ **8.9**

Residual plots show random scatter around zero, indicating a good linear fit and well-behaved residuals.

---

## 📈 Visualizations
The project includes the following visualizations:
- Correlation heatmap for feature selection
- Actual vs Predicted values plot
- Residuals vs Predictions plot

These plots help validate model assumptions and performance.

---

## 🛠 Tools & Libraries
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn

---

## 🚀 Learning Outcome
This project helped reinforce:
- Regression fundamentals
- Proper data preprocessing
- Feature selection techniques
- Model evaluation and interpretation
- Importance of residual analysis

---

## 📌 Future Work
- Try regularized regression models (Ridge, Lasso)
- Perform cross-validation
- Explore more advanced regression techniques

---

## 📬 Feedback
This is a learning project, and any feedback or suggestions are highly appreciated!
