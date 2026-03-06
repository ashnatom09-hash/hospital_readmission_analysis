# Hospital Readmission Analysis

## Project Overview
Hospital readmissions are an important indicator of healthcare quality and patient management. This project analyzes hospital readmission patterns using patient healthcare data to identify factors that influence the likelihood of patients being readmitted after discharge.

The analysis explores patient characteristics, clinical indicators, and hospital visit history to understand how these variables relate to readmission risk. By combining data exploration, SQL analysis, and dashboard visualization, the project demonstrates how data analytics can support better healthcare decision-making.

---

## Tools and Technologies
This project demonstrates a complete data analysis workflow using the following tools:

- Python (Jupyter Notebook) – Data exploration and preprocessing  
- SQL – Data querying and analytical calculations  
- Power BI – Interactive dashboard visualization  

---

## Project Workflow

### Python Analysis
Initial exploratory data analysis was conducted using Python in Jupyter Notebook. The dataset was inspected to understand its structure, variables, and data distributions. This stage helped identify important attributes such as age groups, number of medications, emergency visits, inpatient visits, glucose levels, and A1C test results that could potentially influence hospital readmission.

### SQL Analysis
SQL queries were used to analyze relationships between patient attributes and readmission outcomes. For each variable, the total number of patients, number of readmitted patients, and readmission rate percentage were calculated. These queries helped quantify how different patient characteristics relate to the probability of hospital readmission.

### Power BI Visualization
The results of the SQL analysis were visualized using Power BI dashboards. Multiple charts were created to compare readmission rates across various patient attributes. The dashboard enables quick interpretation of patterns and trends within the dataset through interactive visualizations.

---

## Key Insights
The analysis reveals several patterns associated with hospital readmissions. Patients with a higher number of previous inpatient or emergency visits generally show higher readmission rates, suggesting that frequent hospital usage may indicate more complex medical conditions.

Age also appears to influence readmission risk, with older patient groups tending to have higher readmission percentages. Medication-related factors also show meaningful patterns, as patients taking a larger number of medications or experiencing medication changes often exhibit increased readmission likelihood.

Clinical indicators such as glucose levels and A1C test results also show variation in readmission rates, highlighting the potential relationship between disease management and hospital outcomes.

---

## Dashboard
The Power BI dashboard visualizes readmission rates across several patient characteristics including:

- Age groups  
- Glucose test results  
- A1C test results  
- Medication changes  
- Number of medications  
- Emergency visits  
- Previous inpatient visits  

These visualizations make it easier to identify trends and compare readmission rates between different patient categories.

---

## Repository Structure

hospital-readmission-analysis  

data/  
Dataset used for the analysis  

python/  
Jupyter Notebook containing exploratory data analysis  

sql/  
SQL queries used for calculating readmission metrics  

powerbi/  
Power BI dashboard file  

report/  
Final project report with explanations and screenshots  

---

## Dashboard Preview
Screenshots of the Power BI dashboard are included in the project report. These visualizations highlight key relationships between patient characteristics and hospital readmission rates.

---

## Conclusion
This project demonstrates an end-to-end data analysis workflow using Python, SQL, and Power BI. The analysis highlights how healthcare data can be used to identify patterns related to hospital readmissions and provides insights into factors that may influence patient outcomes. By integrating data exploration, structured querying, and visualization, the project shows how data analytics can transform raw healthcare data into meaningful insights.
