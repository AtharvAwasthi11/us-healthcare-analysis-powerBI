# 🏥 US Healthcare Analysis Dashboard

[![Power BI](https://img.shields.io/badge/Data_Visualization-Power_BI-yellow?style=flat&logo=powerbi)](https://powerbi.microsoft.com/)
[![Analysis](https://img.shields.io/badge/Domain-Healthcare_Analytics-blue)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## 📌 Project Overview
This repository contains a comprehensive **Power BI Dashboard** designed to analyze the U.S. healthcare industry. The project focuses on transforming raw healthcare data into actionable insights regarding hospital performance, patient demographics, and financial optimization.

By leveraging **DAX (Data Analysis Expressions)** and a robust **Star Schema** data model, this dashboard provides stakeholders with the tools to optimize operational efficiency and improve patient care quality.

---

## 📊 Key Dashboards & Features
The report is structured into several focused analytical views:

* **Executive Summary:** A high-level overview of KPIs including total payments, gross charges, and accounts receivable.
* **Patient Analysis:** Detailed breakdown of demographics (age, gender, region) and lifestyle factors (tobacco/alcohol use, exercise habits).
* **Hospital Performance:** Evaluation of hospital efficiency, admission trends, and discharge rates.
* **Payer-Provider Dynamics:** Analysis of insurance provider contributions and reimbursement ratios.

---

## 🛠️ Technical Stack
* **Tool:** Microsoft Power BI Desktop
* **Data Modeling:** Star Schema (Fact and Dimension tables)
* **ETL Process:** Power Query for data cleaning and transformation
* **Calculations:** DAX for custom measures and KPIs

---

## 📈 Key Insights
1.  **Financial Optimization:** Identified key areas in accounts receivable and insurance adjustments to improve revenue cycles.
2.  **Regional Trends:** Visualized healthcare costs and patient density across different U.S. regions to assist in resource allocation.
3.  **Treatment Efficacy:** Analyzed patient outcomes vs. treatment types to highlight the most cost-effective medical interventions.
4.  **Demographic Impact:** Discovered correlations between lifestyle factors and medical costs across specific age groups.

---

## 🚀 Getting Started
To view and interact with the dashboard:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/AtharvAwasthi11/us-healthcare-analysis-powerBI.git](https://github.com/AtharvAwasthi11/us-healthcare-analysis-powerBI.git)
    ```
2.  **Open the file:**
    Ensure you have [Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed. Open the `.pbix` file located in the root directory.
3.  **Explore:**
    Use the interactive slicers (Year, Region, Payer, Hospital) to filter the data and uncover specific insights.

---

## 📂 Repository Structure
```text
├── Data/                   # Raw or sample datasets
├── US_Healthcare.pbix      # Main Power BI project file
├── Screenshots/            # Dashboard preview images
└── README.md               # Project documentation
