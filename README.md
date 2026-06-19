# Hospital-Management- 
Objective

To analyze hospital data and generate insights on patient admissions, treatment efficiency, resource utilization, and overall healthcare operations.

Dataset

* Patient records
* Admission and discharge data
* Doctor information
* Department details
* Treatment records

Tools & Technologies

* Python
* Pandas
* NumPy
* Power BI
* SQL
* Matplotlib

Key Features

* Patient admission analysis
* Department-wise patient distribution
* Length of stay analysis
* Doctor workload analysis
* Treatment outcome monitoring
* Interactive healthcare dashboard

Outcomes

* Identified patient admission trends
* Improved resource allocation insights
* Enhanced hospital performance monitoring
* Supported data-driven healthcare decision-making

Project Description 

* Developed a healthcare analytics dashboard to analyze patient admissions, treatment outcomes, and hospital resource utilization using Python, SQL, and Power BI.

Sample Code 

import pandas as pd

df = pd.read_csv("hospital_data.csv")

total_patients = df["Patient_ID"].nunique()
avg_stay = df["Length_of_Stay"].mean()

print("Total Patients:", total_patients)
print("Average Length of Stay:", round(avg_stay, 2), "days")
