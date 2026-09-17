# End-to-End People Analytics: Employee Attrition Prediction & Executive BI Dashboard

An end-to-end Data Science and Business Intelligence solution using the IBM HR Analytics dataset. The project transitions HR management from reactive exit tracking to proactive attrition mitigation through machine learning inference and interactive executive reporting.

---

##  Business Understanding & Problem Statement

Voluntary employee turnover incurs substantial financial overhead in hiring, training, and operational friction. 

The objectives of this project are:
* Identify the primary drivers behind attrition across departments and job roles.
* Build a machine learning classification pipeline to calculate turnover probability per employee.
* Translate raw predictive outputs into an operational Power BI decision-support tool for HR stakeholders.

---

##  Repository Structure

```text
├── rawdata.csv                          # Raw IBM HR Analytics dataset
├── archive.zip                          # Dataset archive package
├── analysis.ipynb                       # Data cleaning, EDA, feature engineering & model training
├── hr_attrition_dashboard_data.csv      # Inference dataset with attrition probabilities and risk buckets
├── Employee Attrition Risk Analysis.pbix # Interactive multi-page Power BI dashboard
└── README.md                            # End-to-end documentation
