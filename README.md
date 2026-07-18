# Bank Credit Risk Analytics using Microsoft Excel

## Project Overview

This is an end-to-end banking analytics project done entirely in Excel. The goal was to take raw customer banking data, work through it like a bank's risk team would, and end up with a credit risk analysis and dashboard that actually supports a lending decision — not just a bunch of pivot tables sitting there.

The project walks through the full process: data cleaning, feature engineering, advanced formulas, PivotTables/PivotCharts, and a final dashboard.

## What I was trying to do

- Look at customer financial profiles and figure out who's high risk
- Clean and validate the data before touching any analysis
- Build new features that actually mean something for segmenting customers
- Turn the data into interactive PivotTable/PivotChart reports
- Put together a dashboard that tracks the key banking metrics at a glance
- Pull out business insights and recommendations from what I found

## Tools & Excel features used

**Software:** Microsoft Excel 365

**Excel features:** Excel Tables, Data Validation, Conditional Formatting, Named Tables, PivotTables, PivotCharts, Slicers, Dashboard design

**Formulas:** XLOOKUP, INDEX + MATCH, IF / IFERROR, SUMIFS, COUNTIFS, AVERAGEIFS, FILTER, UNIQUE

## Workbook structure

**Raw_data** — the original banking customer dataset, set up as an Excel Table

**Data_Cleaning** — missing value checks, duplicate checks, and general data quality validation before moving on

**Feature Engineering** — built out new business features from the raw data: Age Group, Income Band, Credit Score Band, Debt-to-Income Ratio, Balance Category, Digital Engagement, High Value Customer, and Credit Risk Label

**Formula_Analysis** — this is where I put the advanced formula work: an XLOOKUP customer search panel, INDEX + MATCH, SUMIFS, COUNTIFS, AVERAGEIFS, FILTER, UNIQUE, IFERROR

**Pivot_Analysis** — PivotTables covering customer distribution by credit risk, average income, outstanding debt, loan defaults, mobile banking usage, and customer segments

**Dashboard** — the interactive piece: KPI cards, PivotCharts, slicers, credit risk view, banking performance metrics

**Business_insights** — final write-up: what the analysis found and what I'd recommend based on it

## Key metrics tracked

- Total customers
- High risk customers
- Average credit score
- Average annual income
- Total outstanding debt
- Average loan amount

## What the analysis showed

- Segmenting customers makes it a lot easier to actually understand their financial profiles instead of treating everyone the same
- Credit risk analysis flags which customers need closer monitoring
- Outstanding debt levels give a good read on how exposed the bank is with a given customer
- The engineered features (debt-to-income ratio especially) made the dashboard way more readable than just raw columns would have been
- An interactive dashboard makes it faster to actually use this stuff for decisions, instead of digging through raw data every time

## What I'd recommend based on it

- Tighten up credit assessment for customers flagged as high risk
- Keep an eye on customers carrying higher outstanding debt
- Use the segments to design more targeted financial products instead of one-size-fits-all offers
- Push for more digital banking adoption — it showed up as a meaningful signal in the data
- Actually use dashboards like this one for regular reporting instead of one-off analysis

## Repository contents

```
Bank_Credit_Risk_Analytics/
│
├── Bank_Credit_Risk_Analytics.xlsx
├── credit_risk_dataset.csv
└── README.md
```

## Skills this project covers

Data cleaning, feature engineering, data validation, advanced Excel formulas, customer segmentation, banking analytics, PivotTables, PivotCharts, dashboard design, business reporting

## What I got out of it

This project pushed me to actually apply data cleaning, feature engineering, advanced formulas, and dashboard building to a real-feeling banking dataset instead of just following a tutorial. It's a good example of how far Excel alone can get you when it comes to solving an actual business problem — you don't always need a BI tool to make data usable for decision-making.

## Author

Neerupama Dwarapu
Master of Data Analytics, University of Niagara Falls, Canada
GitHub: https://github.com/DwarapuNeerupama
