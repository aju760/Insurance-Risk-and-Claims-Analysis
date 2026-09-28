# Insurance Risk & Claims Analysis

An interactive **Insurance Risk & Claims Analysis Dashboard** developed using **Power BI, Excel, Power Query, and DAX** to analyze insurance policies, claims, customer demographics, and vehicle-related risk patterns.

---

## 📌 Project Overview

The Insurance Risk & Claims Analysis project focuses on analyzing insurance policyholder and claims data to understand customer characteristics, claim behavior, vehicle information, and risk patterns.

The project uses Power BI to transform the available insurance data into an interactive dashboard that helps users explore key insurance metrics and business dimensions.

---

## 🎯 Business Problem

Insurance policy and claims information can be difficult to analyze when the data contains multiple customer, vehicle, demographic, and claims-related attributes.

This project provides a centralized Power BI dashboard to:

- Monitor important insurance KPIs
- Analyze claim amounts and claim frequency
- Understand policyholder demographics
- Analyze vehicle-related information
- Identify patterns across different customer and policy segments
- Support data-driven insurance analysis

---

## 🎯 Project Objectives

The main objectives of this project are:

1. Analyze the total number of insurance policies.
2. Analyze the total claim amount.
3. Understand claim frequency.
4. Calculate the average claim amount.
5. Analyze policies by gender.
6. Analyze insurance data based on car usage.
7. Understand claim frequency across age groups.
8. Analyze insurance patterns by car make and car year.
9. Study the relationship between education and marital status.
10. Analyze the impact of demographic and vehicle-related factors on insurance risk.

---

## 📊 Key Performance Indicators (KPIs)

The dashboard includes the following key metrics:

- **Total Policies**
- **Total Claim Amount**
- **Claim Frequency**
- **Average Claim Amount**
- **Gender-wise Total Policies**

These KPIs provide a quick overview of the insurance portfolio and claim-related information.

---

## 📈 Dashboard Visualizations

The dashboard includes the following visualizations:

### By Car Use
A donut chart is used to analyze insurance policies based on different types of car usage.

### By Car Make
A bar chart is used to analyze insurance data across different car manufacturers.

### By Coverage Zone
A donut chart is used to understand the distribution of policies across coverage zones.

### By Age Group
An age-group analysis is used to understand claim frequency across different customer age groups.

### By Car Year
An area chart is used to analyze insurance data across different vehicle years.

### By Kids Driving
A ribbon chart is used to analyze insurance patterns based on kids driving information.

### By Education
A pie chart is used to analyze policyholders based on education level.

### Education & Marital Status
A matrix/heat-grid visualization is used to analyze the relationship between education and marital status.

---

## 🗂️ Dataset

The project dataset contains insurance policyholder, vehicle, demographic, and claims-related information.

### Main Dataset Fields

- ID
- Birthdate
- Car Color
- Car Make
- Car Model
- Car Use
- Car Year
- Coverage Zone
- Education
- Gender
- Marital Status
- Parent
- Claim Amount
- Claim Frequency
- Household Income
- Kids Driving

The dataset supports analysis of customer segmentation, risk profiling, vehicle characteristics, and claims behavior.

---

## 🛠️ Tools & Technologies

The following tools and technologies were used:

- **Microsoft Excel** – Dataset storage and initial data handling
- **Power Query** – Data cleaning and transformation
- **Power BI** – Data modeling and dashboard development
- **DAX** – Measures and calculations
- **GitHub** – Project version control and documentation

---

## 🔄 Data Preparation

The insurance dataset was prepared before dashboard development.

The workflow includes:

1. Importing the insurance dataset into Power BI.
2. Reviewing the available fields.
3. Cleaning and transforming data using Power Query.
4. Checking data types and column values.
5. Preparing the dataset for analysis.
6. Creating required calculations using DAX.
7. Building dashboard visualizations.

---

## 🧮 DAX Measures

Example DAX measures used for dashboard analysis include:

### Total Policies

```DAX
Total Policies = COUNTROWS('Insurance')

### Total Claim Amount

```Dax
Total Claim Amount = SUM('Insurance'[Claim Amount])

### Average Claim Amount

```DAX
Average Claim Amount = AVERAGE('Insurance'[Claim Amount])

### Claim Frequency

```DAX
Claim Frequency = AVERAGE('Insurance'[Claim Frequency])

### Gender-wise Total Policies

Analyze the total number of insurance policies across different genders.

## 💡 Business Insights

The dashboard helps users explore:

- Policy distribution across different customer segments
- Claim amount patterns
- Claim frequency across age groups
- Vehicle-related insurance patterns
- Coverage zone distribution
- Car usage patterns
- Education-based customer segmentation
- Marital-status-based customer segmentation
- Kids driving-related insurance patterns
- Gender-wise policy distribution

## 📁 Project Structure

```text
Insurance-Risk-and-Claims-Analysis
│
├── README.md
├── LICENSE
│
├── Dataset
│   ├── README.md
│   └── insurance_policies_data.xlsx
│
├── PowerBI
│   ├── README.md
│   └── INSURANCE PROJECT.pbix
│
└── Documentation
    ├── README.md
    ├── Business Requirements.docx
    └── Domain Doc.docx


## 🔄 Project Workflow

```text
Insurance Dataset
       ↓
Microsoft Excel
       ↓
Power Query
       ↓
Data Cleaning & Transformation
       ↓
Power BI Data Model
       ↓
DAX Measures
       ↓
Interactive Dashboard
       ↓
Insurance Risk & Claims Analysis


## 📚 Skills Demonstrated

- Microsoft Excel
- Power Query
- Power BI
- DAX
- Data Cleaning
- Data Transformation
- Data Visualization
- KPI Development
- Dashboard Development
- Business Analysis
- GitHub

## 📌 Business Value

The dashboard provides a centralized view of insurance policies, claims, customer demographics, and vehicle-related information.

It helps users interactively explore key insurance metrics and identify patterns across different customer, vehicle, and claim-related segments.


## 🚀 Future Enhancements

- Add more advanced DAX calculations
- Add additional insurance risk segmentation
- Create time-based claim analysis
- Add more interactive filters and slicers
- Develop predictive claim analysis
- Add automated data refresh
- Expand the dashboard with additional insurance KPIs


## 👨‍💻 Author

**Ajay Kumar**

Data Analyst / Data Science Aspirant

### Skills

- Excel
- SQL
- Power BI
- Power Query
- DAX
- Python
- Data Analysis
- Data Visualization
