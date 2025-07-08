
# 🩺 Healthcare Insurance Data Analysis

A data analysis project exploring healthcare insurance claim patterns using Python, Pandas and Matplotlib.

---

## 📌 Project Objective

Analyzing a healthcare insurance dataset and then drawing insights for the claim amounts, patient demographics, chronic illness impact and regional differences using data visualization and statistical analysis.

---

## 📂 Dataset Overview

The dataset contains synthetic records of 200 patients and includes:

| Column Name        | Description                            |
|--------------------|----------------------------------------|
| `Patient_ID`       | A unique identifier for each patient     |
| `Age`              | Age of the patient                     |
| `Gender`           | Gender either Male / Female                          |
| `Region`           | Region of residence (4 regions)        |
| `Smoker`           | Whether the patient smokes             |
| `BMI`              | Body Mass Index of the patient                       |
| `Chronic_Disease`  | Indicates chronic illness (Yes/No)     |
| `Claim_Amount`     | Insurance claim amount                 |
| `Approved_Amount`  | Final approved insurance amount        |
| `Diagnosis`        | Type of diagnosis (e.g., Diabetes)     |
| `Claim_Status`     | Status of claim (Approved/Rejected)    |

---

## 📊 Visualizations

This project includes the following visual analyses:

1. Boxplot – This shows the claim amount distribution by region  
2. Bar Chart – This shows the total claim amount by smoker vs non-smoker  
3. Scatter Plot – This shows the Age vs claim amount, colored by chronic disease  
4. Histogram – This shows the distribution of claim amounts  
5. Pie Chart – This shows the gender proportion in the dataset  
6. Line Plot – This shows the average claim amount by age group

---

## 🧠 Key Insights

- Smokers had higher total claim amounts than non-smokers.
- Patients with chronic diseases filed more expensive claims.
- Older adults (60+) tend to have larger claims.
- Midwest and Southeast regions showed greater claim variability.
- Claims were showing as they were right-skewed — few patients drive most of the cost.

---

## 🛠️ Tools Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📁 Project Structure

```
📁 healthcare-insurance-analysis
├── healthcare_insurance_data.csv
├── insurance_analysis.ipynb
└── README.md
```

## 📬 Contact

Made by **Nupur Singh**  

