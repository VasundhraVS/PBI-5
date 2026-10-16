# Healthcare Data Analysis Dashboard

**Created by: Vasundhra V S**

## 📌 Project Overview

This project is a **Healthcare Data Analysis Dashboard** created using **Microsoft Power BI**. The project focuses on organizing healthcare data into a structured data model and preparing it for meaningful analysis and interactive reporting.

The Power BI project uses patient, admission, healthcare, and billing-related information to support data-driven insights.

## 🎯 Objectives

The main objectives of this project are:

- To organize healthcare data efficiently.
- To create a structured data model in Power BI.
- To separate patient, admission, and billing information.
- To establish relationships between different tables.
- To support healthcare and billing analysis.
- To create a foundation for interactive dashboards and reports.

## 🗂️ Data Tables

The project contains the following major tables:

### Healthcare Dataset

The `healthcare_dataset` table contains the main healthcare records used in the project.

### Dim_Patient

`Dim_Patient` is the patient dimension table containing patient-related information.

### Dim_Admission

`Dim_Admission` contains information related to patient admissions and is used for admission-based analysis.

### Fact_Billing

`Fact_Billing` contains billing-related information and provides the measurable data required for financial analysis.

## 🔗 Data Model

The project follows a dimensional data-modeling approach in Power BI.

```text
                    healthcare_dataset
                           |
             +-------------+-------------+
             |                           |
        Dim_Patient                Dim_Admission
             |                           |
             +-------------+-------------+
                           |
                      Fact_Billing
```

The use of dimension and fact tables helps organize the data and makes it easier to analyze information across different healthcare categories.

## 🛠️ Tools Used

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Power BI Data Modeling**

## 📊 Analysis Areas

The project can be used to explore different aspects of healthcare data, including:

- Patient details
- Admission information
- Healthcare records
- Billing information
- Patient-wise analysis
- Admission-wise analysis
- Billing-related analysis
- Relationships between healthcare entities

## 📐 Data Modeling

The project follows a structured approach where:

- **Dimension tables** contain descriptive information.
- **Fact_Billing** contains measurable billing information.
- Relationships connect the tables for combined analysis.
- The model supports filtering and interactive reporting in Power BI.

## 📁 Project Structure

```text
Healthcare-Data-Analysis/
│
├── Task5_Pbi.pbix
└── README.md
```

## ▶️ How to Use

1. Install **Microsoft Power BI Desktop**.
2. Open the `Task5_Pbi.pbix` file.
3. Review the tables and relationships in the **Model** view.
4. Explore the available report and visualizations.
5. Refresh the data when required.
6. Use filters and Power BI interactions to perform analysis.

## 💡 Project Outcome

This project demonstrates the use of **Power BI for healthcare data modeling and analysis**. By separating patient, admission, and billing information into appropriate tables, the project provides a structured foundation for creating interactive healthcare reports.

## 👩‍💻 Author

**Vasundhra V S**

### Project: Healthcare Data Analysis Dashboard
### Tool: Microsoft Power BI
