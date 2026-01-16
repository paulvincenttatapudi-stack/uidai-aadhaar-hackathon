UIDAI Aadhaar Enrolment Analysis
Project Overview

This project analyzes the UIDAI Aadhaar Enrolment Open Dataset to identify geographical, demographic, and time-based enrolment patterns across India. The objective is to transform large-scale public enrolment data into meaningful and actionable insights that can support planning, monitoring, and operational decision-making.

Participant Details

Name: TATAPUDI PAUL VINCENT

Hackathon: UIDAI Hackathon

Team ID: UIDAI_6761

Problem Statement

The Aadhaar enrolment dataset contains aggregated enrolment information across states, districts, PIN codes, and age groups. Due to its large volume and distributed nature, it is difficult to directly interpret trends and regional variations.

This project aims to analyze Aadhaar enrolment data to uncover regional concentration, demographic participation, and temporal trends, enabling data-driven insights for administrative and operational planning.

Dataset Description

Source: UIDAI Aadhaar Enrolment Open Data (Official)

Format: CSV files generated via UIDAI APIs

Attributes:

Date of enrolment

State

District

PIN code

Age-wise categories:

0–5 years

5–17 years

18 years and above

The dataset represents officially published aggregated enrolment statistics released by UIDAI for public analysis.

Methodology

The analysis followed a structured data analytics workflow:

Data collection from UIDAI open data sources

Consolidation of multiple CSV files into a unified dataset

Data cleaning to handle missing values and inconsistent formats

Feature engineering to compute total enrolments

Exploratory analysis across states, districts, and time periods

Visualization of trends and regional comparisons

Exploration of a regression-based approach for short-term forecasting

The forecasting model implementation and outputs are available in the project notebook.

Key Insights

A small number of states contribute over 50 percent of total Aadhaar enrolments, indicating regional concentration.

Enrolments in the 18 years and above age group dominate overall registrations.

Enrolment activity exhibits clear time-based patterns.

Monthly trends indicate periods of increased enrolment activity.

Certain districts consistently emerge as high-enrolment regions.

Age-group distribution highlights varying participation levels across demographics.

Visualizations

The following visualizations support the analysis:

Top 10 States by Aadhaar Enrolments

Monthly Aadhaar Enrolment Trend (2025)

Age-wise Distribution of Aadhaar Enrolments

Forecasting

A regression-based forecasting approach was implemented to estimate Aadhaar enrolment trends for the next 30 days. Forecasting assists in anticipating future enrolment demand and supports proactive planning of enrolment infrastructure.

Impact and Conclusion

This project demonstrates how large-scale public data can be transformed into actionable insights using data analytics. The findings can assist UIDAI and related stakeholders in identifying high-demand regions, supporting data-driven resource allocation, monitoring demographic participation trends, and improving operational planning.

Tools and Technologies

Python

Pandas

Matplotlib

Jupyter Notebook

Repository Structure
├── aadhaar_analysis.ipynb
├── api_data_*.csv
├── top_states.png
├── monthly_trend.png
├── trends_with_spikes.png
├── requirements.txt
└── README.md

GitHub Repository

Code, datasets, notebooks, and visualizations are available at:
https://github.com/paulvincenttatapudi-stack/uidai-aadhaar-hackathon

How to Use

Clone the repository

Install dependencies using requirements.txt

Execute the Jupyter Notebook to reproduce the analysis and visualizations
