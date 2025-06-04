# 🎓 Graduate Admission Prediction Using Linear Regression

This project builds a **Linear Regression model** to predict a student’s chance of admission to a graduate program based on academic and personal attributes. It demonstrates a complete data science workflow from data exploration to model training and evaluation.Linear Regression model is one of the simplest predictive model in Machine Learning. It predicts by deriving a straight-line formula based on the data fit on it. But as simple as it is, Linear Regression can still be an effective model such as in use-cases like this.

---

##  Project Motivation

In today's competitive academic environment, many students seek to understand how their profile affects graduate school admissions. This project aims to:

- Identify the most influential factors (CGPA, GRE, Research, etc.)
- Provide a predictive model for estimating admission chances
- Demonstrate an end-to-end regression use case in Python

---

##  Files Included

- `lr_linear_regression.ipynb` – Jupyter notebook with complete code
- `requirements.txt` – Python dependencies
- `README.md` – Project documentation (this file)

---

## Dataset Information

The dataset is publicly available on GitHub/Kaggle and contains 500 samples with the following attributes:

| Feature              | Description                             |
|----------------------|------------------------------------------|
| GRE Score            | Graduate Record Examination (out of 340) |
| TOEFL Score          | TOEFL score (out of 120)                 |
| University Rating    | Rating from 1 to 5                       |
| SOP                  | Statement of Purpose Strength (1–5)      |
| LOR                  | Letter of Recommendation Strength (1–5)  |
| CGPA                 | Undergraduate GPA (out of 10)            |
| Research             | Research experience (0 = No, 1 = Yes)    |
| Chance of Admit      | Target variable (probability between 0–1)|

---

##  Techniques Used

-  Data Preprocessing (`pandas`, `numpy`)
-  Exploratory Data Analysis (EDA) with `matplotlib` and `seaborn`
-  Feature Correlation & Trend Analysis
-  Model Training using `sklearn.linear_model.LinearRegression`
-  Evaluation Metrics: R² Score, MAE, MSE, RMSE
-  Residual Analysis & Regression Plots

---

##  Key Results & Insights

- The **CGPA** and **GRE Score** were the most influential predictors.
- **Research Experience** and **University Rating** also had noticeable effects.
- The model achieved an **R² Score of approximately 0.82**, indicating strong predictive power.

###  Feature Importance Snapshot

| Feature         | Coefficient Impact |
|-----------------|--------------------|
| CGPA            | High Positive      |
| GRE Score       | Moderate Positive  |
| Research        | Moderate Positive  |
| TOEFL Score     | Moderate           |

---

##  Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/LinearRegressionProject.git
   cd LinearRegressionProject
2.Install dependencies:
pip install -r requirements.txt

# 3. Run the project
python lr_linear_regression.ipynb
