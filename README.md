# 📊 HR Analytics & Employee Attrition Prediction

## Project Overview
This project analyzes employee data to predict **attrition** using machine learning. The goal is to identify key factors driving employee turnover and provide actionable insights for HR teams.  

**Key Highlights:**
- Explored HR dataset using **Python, Pandas, Matplotlib, and Seaborn**  
- Built multiple ML models to predict employee attrition:
  - Logistic Regression  
  - Decision Tree Classifier  
  - Random Forest Classifier  
- Identified the **most important features** influencing attrition  

---

## Dataset
The dataset contains employee demographics, job-related information, and compensation details.  

**Key Features:**
- Employee demographics: Age, Gender, Marital Status  
- Job information: Department, Job Role, OverTime  
- Compensation: Monthly Income, Job Level  
- Target variable: **Attrition** (Yes/No)  

**Source:** [Insert Dataset Link if Public]  

---

## Exploratory Data Analysis (EDA)
We explored the data to understand patterns and trends:

- Visualized **attrition count** and **department-wise attrition**  
- Examined **monthly income distribution**  
- Created a **correlation heatmap** to find relationships between features  

**Example Plots:**
- Attrition Count 📊  
- Department-wise Attrition  
- Monthly Income Distribution 💰  
- Correlation Heatmap  

---

## Machine Learning Models
### 1️⃣ Logistic Regression
- Baseline model for predicting attrition  
- Metrics used: Accuracy, Precision, Recall, F1-score  

### 2️⃣ Decision Tree Classifier
- Captures non-linear relationships between features  
- Feature importance highlights factors influencing attrition  

### 3️⃣ Random Forest Classifier
- Ensemble model combining multiple decision trees  
- Improved accuracy and robustness  
- Top features influencing attrition: **OverTime, MonthlyIncome, JobRole, YearsAtCompany**  

---

## Technologies & Tools
- **Python 3.x**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn** (Data Visualization)  
- **Scikit-learn** (Machine Learning)  
- **Jupyter Notebook / Google Colab**  

---

## Key Insights
- Employees working **overtime** are at higher risk of attrition ⏰  
- **Lower monthly income** correlates with higher attrition 💰  
- Job role and **years at company** also significantly impact turnover  
- **Random Forest** performed best among the three models  

**Conclusion:** Insights can help HR teams design retention strategies and optimize workforce planning.  

---

## How to Run
1. Clone the repository:  
```bash
git clone https://github.com/yourusername/HR-Analytics-ML.git
```

2. Open the notebook in either Jupyter Notebook or Google Colab.

3. Ensure the dataset WA_Fn-UseC_-HR-Employee-Attrition.csv is in the same folder as the notebook.

4. Run all cells to replicate the analysis and machine learning models.
