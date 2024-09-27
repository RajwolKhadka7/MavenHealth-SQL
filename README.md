# **Hospital Patient Records SQL Analysis**

## **Project Overview**

This project focuses on analyzing synthetic data from Massachusetts General Hospital, encompassing records of approximately 1,000 patients from the years 2011 to 2022. The dataset was cleaned using Microsoft Excel and queries were extracted using SQL Server Management Studio (SSMS). The dataset includes detailed information on patient demographics, insurance coverage, and medical encounters & procedures. The primary objective is to leverage SQL to extract meaningful insights from the data, which could inform decision-making processes in healthcare management and policy.

## **Dataset Description**

- **Source**: Synthetic data generated for Massachusetts General Hospital.

- **Link To Dataset**: https://mavenanalytics.io/challenges/maven-hospital-challenge/facee4d2-8369-4c87-a55e-e6c7ed2a42d8

- **Timeframe**: 2011-2022

- **Records**: ~1,000 patients

- **Key Features**:

  - **Patient Demographics**: Age, gender, ethnicity, etc.

  - **Insurance Coverage**: Types of insurance, coverage details.

  - **Medical Encounters & Procedures**: Inpatient/outpatient visits, procedures performed, diagnosis codes.

## **Objectives**

- To analyze patient demographics and their correlation with medical procedures and outcomes.

- To assess the impact of different insurance coverage on the frequency and type of medical procedures.

- To explore trends in medical encounters over the years, identifying any significant changes in patient care.

## **SQL Queries**

The repository includes a series of SQL scripts designed to:

1. **Understand Hospital Encounters**: Breakdown of patient demographics, rate of readmission, and claim payment breakdowns

2. **Show Length of Stay (LOS) Insights**: Measuring LOS by health reasons, averages over a series of time, and gender

3. **Assess Claim Costs**: Understanding how the payment of enncounters is broken down.


## **Analysis**

1. **Readmittance rate**: A high readmittance rate (87.68%) indicates a lack of treatment quality and a need for better post-discharge care and follow-up

2. **Uninsured Patients**: The hospital saw 8807 encounters with No Insurance, emphasizing to management on the need to reduce higher costs for uninsured patients.

3. **Discrepancies in Coverage Across Races**: Black (21.88%), Native (15.12%), and Hawaiian (13.62%) populations have signicantly lower coverage proportions, potentially leading to financial strain, increase in debt, and avoidance of necessary medical care across the underrepresented races.

4. **COVID-19 Impacts**: The hospital saw an approximate 15% rise for claim costs in 2020 when compared to 2019, followed by an approximate 11% decrease in the subsequent year. Understanding these trends can help forecast the planning and managing of healthcare resources in the case of a future crisis.

5. **Length of Stay Based On Specific Conditions**: Sepsis (203 hours) and COVID-19 (183 hours) saw the highest average Length of Stay(LOS). By focusing on allocation for both resources and adquate staffing in addition to cost management and process improvements, the hospital can enhance the care provided to patients with severe health conditions while potentially reducing LOS.
