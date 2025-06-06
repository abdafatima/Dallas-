# Dallas Police Case Suspension Analysis

This repository presents a machine learning analysis of police case suspensions using real incident data from Dallas, Texas. The goal is to identify the most influential factors behind the suspension of police investigations, particularly focusing on victim demographics, incident characteristics, and geographical variables.

##  Dataset
- **Source:** Dallas Open Data (Police Reports)
- **Size:** 300,000+ incident records
- **Target Variable:** Case Suspension (Suspended = 1, Not Suspended = 0)
- **Features:** Victim race, gender, incident type, reporting area, weapon use, time of occurrence, etc.

##  Project Overview

### Objective
To investigate and model the factors influencing why certain cases are marked as "Suspended" using classification techniques such as Decision Trees and Random Forest.

### Key Findings
- **Accuracy:** 92%
- **Precision (Suspended):** 93%
- **Recall (Suspended):** 99%
- **Top Predictors:**
  - Incident Type (e.g., Natural/Accidental Death)
  - Reporting Area
  - Victim Race (less influential but present)

##  Tools & Techniques
- **Language:** Python
- **Libraries:** pandas, sklearn, matplotlib, seaborn
- **Models:** Decision Tree, Random Forest Classifier
- **EDA:** Gender distribution, weapon types, temporal trends

### Preprocessing Steps
- **Missing Value Handling:** Rows with missing target or critical features were dropped.
- **Encoding:** Categorical variables were label-encoded or one-hot encoded depending on their cardinality.
- **Datetime Parsing:** Dates were converted into separate features: year, month, and day of the week.
- **Class Imbalance:** Identified and documented for future handling with rebalancing methods.
- **Feature Selection:** Selected features based on importance in tree-based models and domain relevance.

##  Insights
- Operational and geographic factors like incident type and reporting area strongly influence case suspensions.
- Demographic variables like race are less dominant but still significant, pointing to possible systemic disparities.
- The model struggled to recall non-suspended cases due to class imbalance.



