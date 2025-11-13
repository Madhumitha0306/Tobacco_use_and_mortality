🚭 Tobacco Use and Mortality (2004–2015)
*A Machine Learning and Data Analysis Project*


📌 Project Overview
This project analyzes the relationship between **tobacco use** and **mortality rates** in England using health data from **2004–2015**.  
It combines data from multiple health sources (admissions, fatalities, smokers, metrics, prescriptions) to predict mortality likelihood using machine learning models.


 🧠 Objectives
- Merge and clean multi-source tobacco-related datasets.
- Perform visual **Exploratory Data Analysis (EDA)**.
- Build and tune **Logistic Regression** and **Random Forest** models.
- Evaluate model performance using ROC-AUC and classification metrics.
- Save and export the best-performing model for deployment.


 🧰 Tools & Technologies
| Category | Tools |
|-----------|--------|
| **Language** | Python 3.x |
| **IDE** | Jupyter Notebook  |
| **Libraries** | pandas, numpy, matplotlib, seaborn, scikit-learn, joblib |
| **Domain** | Machine Learning, Data Science |

📂 Dataset Description
The project uses five CSV datasets (from official UK health sources):

| File | Description |
|------|--------------|
| `admissions.csv` | Hospital admissions due to tobacco-related diseases |
| `fatalities.csv` | Annual mortality statistics |
| `metrics.csv` | General health indicators |
| `prescriptions.csv` | Smoking cessation prescription data |
| `smokers.csv` | Smoking prevalence (segmented by year and sex) |

**Merge Keys:** `Year`, `Sex`  
**Target Column:** `mortality` (binary outcome: 0 = Alive, 1 = Deceased)

📈 Model Pipeline
The ML pipeline performs:
1. **Data Preprocessing** – Imputation, scaling, encoding  
2. **Feature Engineering** – Handling numeric and categorical data  
3. **Model Training** – Logistic Regression, Random Forest  
4. **Evaluation** – Accuracy, Precision, Recall, F1, ROC-AUC  



