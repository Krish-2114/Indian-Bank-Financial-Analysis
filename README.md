# Indian Bank Financial Performance Analytics

A Power BI project analysing the financial performance of Indian banks
using RBI bank-level data.

## 📌 Project Overview

This project analyses Indian bank financial data across **FY2015-16 to
FY2024-25** to understand:

-   Bank size and financial scale
-   Asset, deposit and advance growth
-   Profitability
-   Asset quality and NPAs
-   Capital adequacy
-   Overall financial sustainability

The dashboard follows the analytical flow:

**Size → Growth → Profitability → Risk → Capital → Sustainability**

## 📊 Power BI Dashboard

The Power BI report contains three interactive pages:

### 01 --- Overview

Provides a high-level view of a selected bank's: - Assets - Deposits -
Advances - Net Profit - ROA and ROE - Net NPA - CRAR - Key financial
trends

### 02 --- Growth & Profitability

Focuses on: - Asset Growth - Deposit Growth - Advance Growth - Profit
Growth - Growth vs ROA - Net Interest Income vs Operating Expenses - ROA
and ROE trends

### 03 --- Risk & Financial Health

Focuses on: - Net NPA - CRAR - Tier 1 and Tier 2 capital - NPA trends -
Advance Growth vs Net NPA - CRAR vs ROA

The dashboard includes **Bank** and **Financial Year** slicers that work
across all pages.

## 🛠️ Tools & Technologies

-   **Python / Pandas** --- data preparation and analysis
-   **RBI Data** --- source financial data
-   **Power BI** --- data modelling, DAX and dashboard development
-   **Git / GitHub** --- version control

## 📁 Project Structure

``` text
Indian_Bank_Analytics/
│
├── .venv/
│
├── 01_Raw_Data/
│   └── Raw RBI bank data
│
├── 02_Cleaned_Data/
│   └── Cleaned and prepared datasets
│
├── 03_Analysis/
│   └── Analysis and calculated metrics
│
├── .gitignore
├── Indian_Bank_Analytics.pbix
└── Indian_Bank_Analytics_Theme.json
```

## 🎯 Objective

The objective is to use financial data and Power BI to identify banks
that demonstrate **strong growth and profitability while maintaining
healthy asset quality and adequate capital**.

> The analysis describes patterns observed in the data and does not
> imply causal relationships.

## 👤 Author

**Krish Shah**

A portfolio project combining **Financial Analysis, Python, and Power
BI**.
