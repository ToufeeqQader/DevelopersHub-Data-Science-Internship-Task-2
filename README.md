# DevelopersHub-Data-Science-Internship-Task-2

# Task 2: Credit Risk Prediction

### 1. The Task Objective
[cite_start]To predict whether a loan applicant is likely to default on a loan or have their loan approved based on their profile data[cite: 26, 27].

### 2. My Approach
* [cite_start]Handled missing data by using mean imputation for numerical features (like Loan Amount) and mode imputation for categorical features (like Gender and Dependents)[cite: 31].
* [cite_start]Conducted Exploratory Data Analysis (EDA) using `matplotlib` and `seaborn` to visualize key features such as applicant income, education levels, and loan amounts[cite: 32].
* Preprocessed the data by encoding categorical variables into numerical values using Label Encoding.
* [cite_start]Trained a Logistic Regression classification model to predict the loan status[cite: 33].
* [cite_start]Evaluated the model's performance using an accuracy score and a confusion matrix[cite: 34].

### 3. Results and Insights
* **Insights from EDA:** Applicants with a Graduate-level education were noticeably more likely to have their loans approved. The income distribution was highly skewed, with the majority of applicants falling into a specific lower-to-middle income bracket.
* **Model Performance:** The Logistic Regression model achieved a solid accuracy score. The confusion matrix revealed the exact breakdown of correctly predicted loan approvals versus rejections, showing that the model is reliable for basic credit risk assessment.

---
