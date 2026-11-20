Hospital Management Data Analysis

Introduction

This project focuses on analysing healthcare data to understand patient admissions, medical conditions, demographics, insurance providers, and billing information.

I used Microsoft Excel, Power Query, and Power BI to clean the dataset, perform analysis, calculate key metrics, and create an interactive dashboard.

The main aim was to transform raw healthcare data into meaningful information through data analysis and visualisation.

Project Objectives

- Clean and prepare the healthcare dataset.
- Analyse patient admission patterns.
- Understand the distribution of medical conditions.
- Examine admission types and gender distribution.
- Analyse patient records across insurance providers.
- Calculate important healthcare KPIs.
- Create an interactive dashboard using Power BI.

Tools Used

- Microsoft Excel
- Power Query
- Microsoft Power BI
- DAX

Dataset Details

Dataset Name: Healthcare Dataset

Source: Kaggle

[https://www.kaggle.com/datasets/prasad22/healthcare-dataset](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)

- Original Records: 55,500
- Original Columns: 15
- Duplicate Records Removed: 534
- Final Records: 54,966

The dataset contains synthetic patient records with details such as age, gender, blood type, medical condition, admission date, hospital, insurance provider, billing amount, medication, and test results.

Data Cleaning and Preparation

The dataset was imported into Excel Power Query for cleaning and preparation.

The following steps were performed:

1. Inspected the dataset and checked its structure.
2. Corrected data types for numerical, date, and text columns.
3. Removed 534 exact duplicate records.
4. Retained 106 negative billing records for further review.
5. Created a Length of Stay column using admission and discharge dates.
6. Created additional columns for Admission Month, Admission Month Number, and Admission Year.

After cleaning, the dataset contained 54,966 records.

 Data Analysis

The cleaned dataset was imported into Power BI for analysis.

DAX measures were created to calculate:

- Total Admissions
- Average Patient Age
- Average Length of Stay
- Total Billing Amount
- Negative Billing Records

Key Performance Indicators

| KPI                      |        Value |
| ------------------------ | -----------: |
| Total Admissions         |       54,966 |
| Average Patient Age      |   51.5 Years |
| Average Length of Stay   |    15.5 Days |
| Total Billing Amount     | ₹140.41 Cr\* |
| Negative Billing Records |          106 |

The original dataset does not specify the billing currency. INR is used as an assumed display format, not as a verified currency conversion.

 Dashboard Preview

The Power BI dashboard provides an overview of patient admissions and related healthcare information.
The dashboard includes:

- Monthly Patient Admissions
- Admissions by Medical Condition
- Admission Type Distribution
- Admissions by Gender
- Admissions by Insurance Provider
- Patient and billing KPIs

Key Observations

- The final dataset contains 54,966 records after duplicate removal.
- The average patient age is approximately 51.5 years.
- The average length of stay is approximately 15.5 days.
- Six medical condition categories are available in the dataset.
- Patient records cover three admission types: Emergency, Urgent, and Elective.
- Five insurance providers are represented.
- A total of 106 negative billing records were retained for review.

Limitations

- The dataset contains synthetic records rather than real hospital patient information.
- The original dataset does not specify the billing currency.
- Negative billing records have no documented explanation.
- Hospital bed capacity information is unavailable.
- The available information is insufficient to evaluate individual doctor performance.

Conclusion

This project helped me gain practical experience in data cleaning, data transformation, data analysis, DAX calculations, and Power BI dashboard development.

By working through the complete process, I learned how to prepare raw data, calculate useful metrics, and present the results through visualisations.

Future Improvements

- Explore treatment and medication patterns.
- Add department-level analysis if suitable data becomes available.
- Include additional healthcare-related KPIs.
- Compare multiple healthcare datasets.

Project Files

The repository includes the cleaned dataset, Power BI dashboard, dashboard screenshot, and detailed project documentation.
