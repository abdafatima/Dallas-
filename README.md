This repository presents a comprehensive data science project that explores the underlying factors influencing the suspension of police investigations in Dallas, Texas. Using police incident reports and machine learning techniques, the project aims to uncover patterns and predictors associated with suspended cases—contributing to informed policy reform and operational improvements in law enforcement.

🧾 Project Overview
Objective:
To model and analyze the factors—demographic, geographic, and incident-related—that correlate with police case suspensions. The analysis is grounded in real-world data and applies supervised learning algorithms to predict outcomes and interpret key drivers.

Data Source:
Dallas Police Department incident reports (structured dataset including demographics, incident types, locations, temporal features, etc.)

📂 Repository Contents
Dallas.ipynb: Jupyter Notebook containing data preprocessing, exploratory data analysis (EDA), and model development using Decision Tree and Random Forest classifiers.

Dallas Report.docx: Detailed project report including abstract, literature review, methodology, findings, and references.

🧠 Methodology
🔍 Exploratory Data Analysis (EDA)
Temporal trend analysis (monthly incident distribution)

Victim gender distribution

Most common weapon types used in incidents

⚙️ Machine Learning
Target Variable: Offense Status (Suspended: 1, Not Suspended: 0)

Algorithms Used:

Decision Tree Classifier

Random Forest Classifier

Feature Engineering: Encoding categorical variables, handling missing values, and temporal aggregation

Key Predictors Identified:

Incident Type (e.g., Natural Death, Accidental Death)

Reporting Area

Victim Race and other demographic indicators

📈 Model Performance (Random Forest)
Accuracy: 92%

Precision (Suspended Cases): 93%

Recall (Suspended Cases): 99%

Noted class imbalance impacted the recall for non-suspended cases (29%)

🧩 Key Insights
Incident type was the strongest predictor of case suspension, particularly for non-criminal events.

Geographic disparities emerged, with certain reporting areas showing higher suspension rates—suggesting differences in resource allocation and operational prioritization.

Victim race, though not the dominant factor, emerged as a notable contributor, hinting at potential systemic bias.

The findings align with existing literature but emphasize local nuances specific to Dallas.

🛠 Technologies Used
Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Scikit-learn

Tools: Jupyter Notebook, Microsoft Word

📚 References
Academic references, data ethics guidelines, and prior research studies cited are included in the attached report (Dallas Report.docx) for further reading and validation.

📌 Future Work
Addressing class imbalance via SMOTE or other sampling techniques

Incorporating qualitative factors from police narratives

Expanding analysis to include temporal patterns across multiple years

Exploring interactive visual dashboards using Tableau or Power BI

