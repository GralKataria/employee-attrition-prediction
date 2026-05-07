#  Employee Attrition Prediction using Machine Learning

##  Project Summary
This project focuses on predicting employee attrition using machine learning techniques. The goal is to analyze HR data and identify patterns that indicate whether an employee is likely to leave the organization.

The system compares multiple classification algorithms and evaluates their performance to determine the most effective model.

---

##  Contributors

| Name | Roll Number |
|------|-------------|
| Gral Kataria | 245UAI047 |

---

##  Objective

The primary objective of this project is to build a predictive system that can classify employees into two categories:

- **Will Stay**
- **Will Leave**

This helps organizations proactively understand employee behavior and improve retention strategies.

---

##  Dataset Description

- **Dataset Name:** IBM HR Analytics Employee Attrition Dataset  
- **Source:** Kaggle  
- **Total Records:** 1470 employee entries  
- **Target Variable:** Attrition (Yes / No)

###  Feature Categories:
- **Demographic:** Age, Gender, Education
- **Job Details:** Job Role, Department, Job Level
- **Compensation:** Monthly Income, Salary Slab
- **Work Factors:** OverTime, Work-Life Balance
- **Experience:** Years at Company, Total Working Years

---

##  Data Exploration Insights

During exploratory data analysis, several important patterns were observed:

- Employees working overtime show a higher tendency to leave
- Lower income groups are more prone to attrition
- Certain job roles experience higher turnover rates
- Longer tenure generally correlates with employee retention

Visual analysis was performed using:
- Distribution plots
- Count plots
- Heatmaps
- Feature comparison graphs

---

##  Data Preparation Steps

To prepare the dataset for modeling, the following steps were performed:

- Removed irrelevant or redundant columns
- Converted categorical variables into numerical form using encoding techniques
- Verified absence of missing values
- Separated dataset into features (X) and target (y)
- Split data into training and testing sets

---

##  Machine Learning Models Implemented

Three classification algorithms were applied:

| Model | Purpose |
|------|--------|
| Logistic Regression | Baseline linear classification model |
| Decision Tree | Rule-based decision learning |
| Random Forest | Ensemble method for improved accuracy |

---

##  Model Evaluation

Performance was measured using accuracy score and classification metrics.

| Model | Accuracy |
|------|----------|
| Logistic Regression | ~85% |
| Decision Tree | ~84% |
| Random Forest | **~87% (Best Performing)** |

###  Evaluation Techniques Used:
- Accuracy Score
- Confusion Matrix
- Classification Report

---

###  Key influencing factors:
- Overtime
- Monthly Income
- Job Role
- Years at Company
- Work-Life Balance indicators

These features significantly impact employee retention decisions.

---

##  Project File Structure

```
Employee-Attrition-Prediction/
│
├── dataset.csv                          # HR dataset
├── Employee_Attrition.ipynb            # Main notebook
├── employee_attrition_model.pkl        # Trained model file
└── README.md                            # Project documentation
```

---

##  Requirements

The project requires the following Python libraries:

```
pandas
numpy
matplotlib
seaborn
scikit-learn
```

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

##  How to Execute

1. Download or clone the repository
2. Open the Jupyter Notebook or Google Colab
3. Load the dataset into the environment
4. Run all cells sequentially
5. View model performance and visual insights

---

##  Key Learnings

- Employee attrition can be effectively analyzed using machine learning
- Ensemble models like Random Forest perform better on HR datasets
- Work-related factors (overtime, income, job role) strongly influence attrition
- Data preprocessing plays a crucial role in model accuracy

---

##  References

- IBM HR Analytics Dataset (Kaggle)
- Scikit-learn Documentation: https://scikit-learn.org
- Machine Learning Best Practices in Classification Problems
