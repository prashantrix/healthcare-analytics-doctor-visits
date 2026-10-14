# 🏥 Healthcare Analytics for Doctor Visits 

## 📌 Project Overview ##

The Healthcare Analytics for Doctor Visits project explores patient doctor-visit patterns using Python and data analysis techniques. The goal is to understand how doctor visits vary across patients based on illness scores, gender, and other available demographic information.

This project uses Exploratory Data Analysis (EDA) to identify patterns and present findings through visualizations that can help support data-driven healthcare insights.

## 🎯 Objectives ##

Analyze the distribution of doctor visits among patients.

Investigate the relationship between illness scores and average doctor visits.

Compare average doctor visits across genders.

Explore patient demographics and healthcare utilization patterns.

Communicate insights through clear, informative visualizations.

## 📂 Dataset Overview ##

The dataset contains 5,190 records and 13 columns related to patient characteristics and doctor visits.

| Dataset Detail | Description |
|:---|:---|
| **Total Records** | 5,190 |
| **Total Columns** | 13 |
| **Missing Values** | None detected during initial inspection |
| **Target Variable** | `visits` |
| **Analysis Type** | Exploratory Data Analysis (EDA) |


The dataset includes information such as patient demographics, illness scores, and recorded doctor visits.

Note: These findings describe the dataset used in this project and should not be interpreted as conclusions about all patients or healthcare systems.

## 🛠️ Technologies Used ##

Python — Data analysis and processing

Pandas — Data manipulation and analysis

NumPy — Numerical operations

Matplotlib — Data visualization

Seaborn — Statistical visualization

Jupyter Notebook — Interactive analysis and documentation

## 🔍 Project Workflow ##

Data loading: Imported the healthcare dataset into a Pandas DataFrame.

Data inspection: Examined the dataset's dimensions, columns, data types, and structure.

Data quality checks: Checked for missing values and reviewed the data for analysis.

Exploratory analysis: Examined doctor visits across different patient characteristics.

Visualization: Created charts to communicate the distribution of visits and relationships between variables.

Insights: Interpreted the observed patterns while keeping the limitations of the data in mind.

## 📊 Key Visualizations and Findings ##

<img width="704" height="470" alt="image" src="https://github.com/user-attachments/assets/feb706cf-8fba-4f9f-9be5-2e35608f0db7" />



1. Distribution of Doctor Visits

The distribution is strongly concentrated at zero recorded visits, with progressively fewer observations at higher visit counts.

Key insight: Most records in this dataset contain zero doctor visits, while a smaller proportion records one or more visits. The distribution is right-skewed, with relatively few records showing higher visit counts.


<img width="567" height="455" alt="image" src="https://github.com/user-attachments/assets/b3f6e141-3342-4ac4-825d-bce1c4c22282" />



2. Illness Score vs. Average Doctor Visits

The chart shows an overall increase in average recorded doctor visits as the illness score rises.

Key insight: Records with higher illness scores tend to have higher average doctor-visit counts in this dataset. The highest average in the displayed chart occurs at illness score 5.




<img width="576" height="455" alt="image" src="https://github.com/user-attachments/assets/73e20c81-3557-4278-9b09-9868f0b6a4fd" />



3. Average Doctor Visits by Gender

The gender comparison shows a higher average number of recorded visits for female patients than for male patients in the dataset.

Female: approximately 0.36 average visits

Male: approximately 0.24 average visits

Key insight: Female records show a higher average visit count than male records in this dataset. This is an observed association and does not establish why the difference exists.



## 💡 Business and Healthcare Relevance ##

The analysis demonstrates how data analytics can help explore healthcare utilization patterns.

Potential applications include:

Understanding the distribution of healthcare service usage.

Identifying patterns associated with illness severity.

Comparing healthcare utilization across demographic groups.

Supporting further investigation into patient behavior and service demand.

These are potential applications of the analysis, not outcomes validated by this project.

## ⚠️ Limitations ##

The analysis describes patterns in the available dataset only.

Observed relationships do not establish causation.

Differences between gender groups do not explain the reasons behind those differences.

The project focuses on exploratory data analysis; it does not currently implement a predictive machine learning model or an interactive dashboard.

The results may not generalize to other patient populations or healthcare settings.

## 🔮 Future Improvements ##

Add deeper statistical analysis to investigate observed relationships.

Explore additional demographic and health-related variables.

Build an interactive dashboard using Power BI or Tableau.

Evaluate an appropriate predictive model if the dataset and project objectives support it.

Improve documentation and automate the analysis workflow.

## 👨‍💻 Author ##

Prashant Kashyap

BCA Graduate | Aspiring Data Analyst

GitHub: @prashantrix

Project Repository: Healthcare Analytics for Doctor Visits

⭐ If you find this project useful, feel free to explore the repository and share your feedback.
