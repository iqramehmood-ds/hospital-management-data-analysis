# Hospital Management Data Analysis | Excel & Power BI

An end-to-end data analytics project exploring hospital operations, treatment revenue, doctor staffing, patient demographics, and billing patterns using Microsoft Excel and Power BI.

## Project Overview

This project uses multiple hospital management datasets to demonstrate the data analytics workflow, from cleaning and organizing records to exploratory analysis, visualization, and interactive dashboard development.

The analysis covers five key areas:
- Appointment Analysis
- Treatment & Revenue Analysis
- Doctor Staffing & Workforce Demographics
- Patient Demographics & Registration Trends
- Billing & Payment Analysis

## Tools & Technologies

- **Microsoft Excel:** Data cleaning, data organization, PivotTables, PivotCharts, and analytical reporting
- **Microsoft Power BI:** KPI cards, interactive visualizations, dashboard design, and slicers
- **Analytics:** Exploratory Data Analysis (EDA), trend identification, and comparative analysis

## Project Workflow

1. **Data preparation:** Cleaned and organized hospital management records across multiple datasets.
2. **Exploratory analysis:** Used Excel to summarize records, compare categories, and identify patterns.
3. **Reporting:** Developed PivotTables, charts, and written insights.
4. **Dashboard development:** Translated the analysis into an interactive Power BI dashboard.
5. **Visualization:** Presented key metrics and comparisons in a consolidated reporting interface.

## Key Findings

### 1. Appointment Analysis

The appointment dataset contains 200 appointments across different appointment types, doctors, and time slots.

**Appointment status**
- No-show: 52 (26%)
- Cancelled: 51 (25.5%)
- Scheduled: 51 (25.5%)
- Completed: 46 (23%)

Cancellations and no-shows together account for 51.5% of appointments, compared with 23% completed.

**Appointment volume by hour**
- 3 PM was the busiest hour, with 28 appointments.
- 4 PM had the lowest volume, with 15 appointments.

**Appointment type**
- Checkup had the highest volume (45) and the most completed appointments (16).
- Emergency had the lowest volume (29).
- Consultation had the most cancellations (15) and the fewest completed appointments (4).
- Therapy had the most no-shows (15), while Follow-up had the fewest (6).

**Doctor-level findings**
- D005 handled the highest appointment volume (29), including 10 scheduled appointments and 9 no-shows.
- D001 and D003 had the highest number of completed appointments, with 6 each.
- D002 had the most cancellations (8).
- D007 had the fewest scheduled appointments (1).

### 2. Treatment & Revenue Analysis

The treatment dataset contains 200 treatments across five categories, generating **$551,249.85** in total revenue.

**Treatment volume and revenue**
- Chemotherapy had the highest volume, with 49 treatments (24.5%), and the highest revenue ($128,855.68).
- MRI and Physiotherapy had the lowest treatment volume, with 36 each.
- MRI generated $116,098.16, the second-highest total revenue.

**Revenue and average cost**
- MRI averaged $3,224.95 per treatment, the highest among the five categories.
- Physiotherapy averaged $2,761.61.
- X-Ray averaged $2,698.87.
- ECG had the lowest average treatment cost, at $2,532.22.

Although X-Ray had more treatments than MRI (41 versus 36), MRI generated more revenue. This illustrates how differences in average treatment cost can affect total revenue.

**Complexity tier analysis**
- Basic Screening had the highest overall average cost ($3,148.97).
- Standard Procedure averaged $2,657.79.
- Advanced Protocol had the lowest average cost ($2,522.46).

Advanced Protocol was the lowest-cost tier for four of the five treatment categories: Chemotherapy, ECG, MRI, and X-Ray. Physiotherapy differed, with Standard Procedure having the highest average cost ($3,140.29).

These results describe the dataset's recorded pricing patterns and do not establish why the costs differ.

### 3. Doctor Staffing & Workforce Demographics

The workforce dataset contains 10 doctors across three branches and three specializations.

**Branch distribution**
- Central Hospital: 4 doctors (40%)
- Eastside Clinic: 3 doctors (30%)
- Westside Clinic: 3 doctors (30%)

**Specialization**
- Pediatrics: 5 doctors
- Dermatology: 3 doctors
- Oncology: 2 doctors

**Experience and seniority**
- Average experience across doctors: 21.5 years
- Pediatrics had the highest average experience (24 years).
- Oncology averaged 23.5 years.
- Dermatology averaged 16 years.
- Senior doctors accounted for 7 of the 10 doctors (70%).

**Specialty coverage**
- Central Hospital had no Oncology doctors.
- Eastside Clinic had no Dermatology doctors.
- Westside Clinic had no Pediatrics doctors.

These figures show differences in specialty distribution between branches in the dataset.

### 4. Patient Demographics & Registration Trends

The patient dataset contains 50 unique patients.

**Age distribution**
- Middle-aged/adult: 22 patients (44%)
- Young adults: 18 patients (36%)
- Older patients: 10 patients (20%)

**Gender distribution**
- Male: 31 patients (62%)
- Female: 19 patients (38%)

Male patients outnumbered female patients across all three age groups. The largest difference was among young adults, with 13 male and 5 female patients.

**Insurance providers**
- MedCare Plus: 18 patients
- Wellness Corp: 16 patients
- Pulse Secure: 10 patients
- Health India: 6 patients

MedCare Plus had the highest patient count, while Health India had the lowest.

**Patient registration trend**
- 2021: 21 patients
- 2022: 17 patients
- 2023: 12 patients

Registrations declined by approximately 43% from 2021 to 2023.

**Insurance provider and age**
MedCare Plus and Wellness Corp each had 7 young adult patients. MedCare Plus had more middle-aged patients (8 versus 5), while Wellness Corp had more older patients (4 versus 3).

### 5. Billing & Payment Analysis

The billing dataset contains 200 bills across three payment methods.

**Payment method volume**
- Credit Card: 75 bills (37.5%)
- Insurance: 64 bills (32%)
- Cash: 61 bills (30.5%)

**Payment status by method**
- Credit Card had the highest number of pending bills (28) and paid bills (24).
- Cash and Credit Card each had 23 failed bills.
- Insurance had 21 failed bills.
- Cash had the fewest pending bills (18).
- Paid bills were relatively similar across methods: Cash (20), Credit Card (24), and Insurance (20).

These comparisons highlight differences in recorded billing status by payment method.

## Dashboard

The Power BI dashboard consolidates the project's findings into visual summaries and interactive views.

**Dashboard features**
- KPI cards for important summary metrics
- Appointment status and volume visualizations
- Treatment volume and revenue comparisons
- Doctor staffing and specialization summaries
- Patient demographics and registration trends
- Billing status and payment method comparisons
- Interactive slicers for exploring the available data

<img width="1341" height="756" alt="image" src="https://github.com/user-attachments/assets/14e3c5a6-9e35-4093-9d03-fc8a85099512" />


## Key Takeaways

This project demonstrates how multiple datasets can be prepared and analyzed to reveal patterns across hospital operations, staffing, patient demographics, treatment revenue, and billing.

The Excel workbook provides the detailed analytical foundation, while the Power BI dashboard offers a visual and interactive way to explore the results.

The findings are descriptive and limited to the records analyzed. They should not be interpreted as causal explanations or representative of hospitals beyond this dataset.



## Project Skills Demonstrated

- Data cleaning and preparation
- Exploratory Data Analysis
- Excel PivotTables and PivotCharts
- KPI reporting
- Data visualization
- Power BI dashboard development
- Analytical communication

**Project focus:** Hospital Operations | Data Analytics | Business Intelligence
