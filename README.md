# Hospital Appointment No-Show Analysis

## Project Overview

This project analyzes hospital appointment data to identify patterns and factors associated with patient no-shows. The goal is to provide actionable insights that can help healthcare providers improve appointment attendance and operational efficiency.

## Tools & Technologies

- Python – Data analysis and exploratory analysis
- Pandas – Data cleaning and manipulation
- Power Query – Data cleaning and transformation
- Power BI – Interactive dashboard and visualization
- SQL – Data querying was explored but not included in the final analysis due to the large dataset size

## Data Cleaning

The dataset was cleaned and transformed using Power Query. This included handling data inconsistencies, creating useful categories, removing invalid records, and preparing the dataset for analysis.

## Analysis

Python was used for exploratory data analysis to understand patterns in patient appointments and no-show behavior.

Key areas analyzed include:

- No-show rate by age group
- No-show rate by gender
- No-show rate by weekday
- No-show rate by waiting days
- No-show rate by SMS reminder
- No-show rate by neighbourhood

## Power BI Dashboard

An interactive Power BI dashboard was developed to present the key findings and allow users to explore appointment no-show patterns.

### Key Metrics

- Total Appointments: 111K
- Show Rate: 80%
- No-Show Rate: 20%
- SMS Reminder Rate: 32%

## Key Findings

The analysis showed that approximately 20% of appointments were missed. No-show rates varied across age groups, waiting periods, weekdays, neighbourhoods, and SMS reminder status.

Longer waiting periods between scheduling and appointments were associated with higher no-show rates, highlighting the importance of reducing unnecessary waiting times.

## Recommendations

1. **Reduce appointment waiting times:** Healthcare providers should consider improving scheduling processes and prioritizing appointments with longer waiting periods.

2. **Improve patient reminders:** The hospital should strengthen SMS reminder strategies and consider additional reminders for patients at higher risk of missing appointments.

## Project Structure

```text
Hospital-Appointment-No-Show-Analysis/
│
├── README.md
├── data/
├── python/
│   └── Hospital_Appointment.ipynb
├── powerbi/
│   └── Hospital_Appointment.pbix
├── images/
│   ├── dashboard.png
│   ├── python_analysis.png
│   └── power_query.png
└── report/
    └── project_report.pdf
