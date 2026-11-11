# Tech Mahindra – Business Performance & Company Analysis Dashboard

An interactive Power BI project designed to analyse company-level business performance, financial trends, workforce distribution, technology popularity, and client-industry distribution.

The project contains two dashboard pages:
1. **Executive Summary** – a high-level view of overall business performance.
2. **Detailed Company Analysis** – a deeper analysis of revenue, profit, employees, technology, and client industries.

---

## Dashboard Preview

### 1. Executive Summary

![Executive Summary Dashboard](images/Dashboard1.png)

This page provides an overview of the key business metrics and performance trends.

**Key metrics displayed**
- Total Profit
- Total Revenue
- Total Employees
- Total Projects
- Profit Margin %

**Visualisations**
- Revenue by Company
- Profit by Company
- Employees by Company
- Profit trend by Year
- Revenue trend by Year
- Business insights panel

**Interactive filters**
- Company
- Year
- Country
- Technology
- Quarter

### 2. Detailed Company Analysis

![Detailed Company Analysis Dashboard](images/Dashboard2.png)

This page focuses on company-level performance and business composition.

**Key metrics displayed**
- Total Profit
- Total Revenue
- Total Employees
- Profit Margin %
- Company Employees

**Visualisations**
- Revenue Growth Trend
- Profit Growth Trend
- Employees vs Revenue
- Technology Popularity
- Client Industry Distribution
- Business insights panel

**Interactive filters**
- Company
- Year
- Industry
- Technology
- Quarter

---

## Project Objectives

- Monitor overall revenue, profit, employee strength, and project volume.
- Compare business performance across companies.
- Analyse year-wise revenue and profit trends.
- Explore workforce distribution across companies.
- Identify popular technologies represented in the dataset.
- Understand the distribution of clients across industries.
- Present key findings through an interactive and easy-to-understand dashboard.

## Tools & Technologies

- **Microsoft Power BI Desktop** – data modelling, DAX measures, visualisations, and dashboard development.
- **Power Query** – data import and transformation.
- **DAX** – calculations and business metrics.
- **Dataset** – the source dataset included in this repository.

> Update this section if additional tools or data sources were used.

---

## Repository Structure

Keep the repository organised using the following structure. Adjust the filenames to match the files you upload.

```text
tech-mahindra-business-dashboard/
│
├── README.md
│
├── dashboard/
│   └── Tech_Mahindra_Analytics.pbix
│
├── data/
│   └── source_dataset.xlsx
│
└── images/
    ├── executive-summary.png
    └── detailed-company-analysis.png
```

**Suggested image filenames**

Rename the two dashboard screenshots before uploading:
- `executive-summary.png` – first dashboard screenshot.
- `detailed-company-analysis.png` – second dashboard screenshot.

If your dataset is a CSV file, place it in the `data/` folder and update its filename in this README.

---

## How to Use the Project

1. Clone or download this repository.
2. Open the `.pbix` file from the `dashboard/` folder using Power BI Desktop.
3. If Power BI asks for the source data location, update the data-source path to the dataset in the `data/` folder.
4. Refresh the data if required.
5. Use the slicers at the top of each page to filter the report.
6. Explore the charts and visuals to compare business performance.

**Note:** The dashboard may require the original dataset and compatible source-file paths to refresh successfully. The published screenshots are included as previews.

---

## Key Business Questions

This dashboard is intended to help explore questions such as:

- Which company contributes the most revenue and profit?
- How do revenue and profit change over time?
- How does employee strength compare across companies?
- What is the relationship between employee count and revenue?
- Which technologies have the highest popularity in the dataset?
- Which industries account for the largest share of clients?
- Do the results change when the company, year, country, technology, industry, or quarter filters are applied?

## Important Data Notes

- All figures and insights should be interpreted in the context of the uploaded source dataset, its definitions, and its reporting period.
- KPI values shown in the screenshots are dashboard outputs; they are not independently verified figures.
- Check the source data's units, currency, date coverage, and aggregation level before using the results for business decisions.
- Confirm that measures such as **Profit Margin %**, employee totals, and revenue/profit totals use the intended calculation and aggregation.
- Do not treat correlation or visual comparison as proof of causation.

## Author

**Harshit Kumar Pandey**\
MBA -- Business Analytics\
Interested in Data Analytics, Business Intelligence, and data-driven
decision-making.

------------------------------------------------------------------------

If you find this project useful, feel free to ⭐ the repository.

## Disclaimer

This dashboard is a data-analytics portfolio/academic project. Company names and labels are used to describe the dataset and dashboard subject. The analysis is based on the dataset provided with this repository and should not be interpreted as an official company report or as independently audited financial information.
