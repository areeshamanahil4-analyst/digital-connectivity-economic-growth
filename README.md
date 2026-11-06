# Digital Connectivity and Economic Growth
### A Comparative Analysis of Pakistan, India and Bangladesh (2010–2024)

## 📌 Project Overview

Does increasing digital connectivity move alongside economic growth?

This project explores the relationship between digital connectivity and economic growth in three South Asian countries: Pakistan, India and Bangladesh, over the period 2010–2024.

Using World Bank data, I analysed internet usage, fixed broadband subscriptions and GDP per capita growth to identify trends, compare countries and explore relationships between these indicators.

## 🎯 Project Objectives

- Analyse digital connectivity trends across three countries.
- Compare internet usage and broadband development.
- Examine GDP per capita growth patterns.
- Explore relationships between digital connectivity and economic growth.
- Build an interactive Power BI dashboard to communicate findings.

## 📊 Dataset

**Source:** World Bank – World Development Indicators (WDI)

| Indicator | Indicator Code |
|---|---|
| GDP per capita growth (annual %) | NY.GDP.PCAP.KD.ZG |
| Individuals using the Internet (%) | IT.NET.USER.ZS |
| Fixed broadband subscriptions (per 100 people) | IT.NET.BBND.P2 |

**Countries:** Pakistan, India and Bangladesh  
**Period:** 2010–2024  
**Total observations:** 45 country-year records

Note: Internet usage data contains three missing observations for Pakistan (2021–2023). These values were not artificially estimated.

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Power BI
- Excel
- World Bank API

## 🔍 Analysis Performed

1. Data collection through the World Bank API.
2. Data cleaning and validation.
3. Exploratory Data Analysis (EDA).
4. Country-wise and year-wise comparisons.
5. Pandemic-period comparison.
6. Correlation analysis.
7. Data visualization using Python and Power BI.

## 📈 Key Findings

**1. Internet Usage Increased**

Between 2010 and 2024, internet usage increased in all three countries:

- India: +57.44 percentage points
- Bangladesh: +49.72 percentage points
- Pakistan: +49.25 percentage points

**2. Broadband Growth**

Bangladesh recorded the largest increase in fixed broadband subscriptions, rising from 0.27 to 8.09 per 100 people.

**3. Economic Growth and Internet Usage**

The overall correlation between GDP per capita growth and internet usage was 0.07, indicating a very weak positive linear relationship in the combined dataset.

**4. Internet and Broadband Relationship**

Internet usage and fixed broadband subscriptions showed a moderate positive correlation of 0.58 in the combined dataset.

*Important: Correlation does not establish causation. These results describe relationships in the observed data, not proof that digital connectivity causes economic growth.*

## 📊 Power BI Dashboard

The project includes an interactive Power BI dashboard with two pages.

- Page 1: Digital connectivity and economic growth overview.
- Page 2: Comparative analysis and relationships between indicators.

Dashboard screenshots and the Power BI file will be available in the repository.

## 💡 Key Learning Outcomes

Through this project, I gained practical experience in:

- Retrieving data using an API for the first time.
- Working with real-world secondary datasets.
- Handling missing values and validating data.
- Performing correlation analysis.
- Translating analytical findings into visual insights.
- Designing interactive dashboards in Power BI.

## 📁 Repository Structure

```text
digital-connectivity-economic-growth/
│
├── data/
├── notebooks/
├── powerbi/
├── images/
├── README.md
└── requirements.txt
```

## 👩‍💻 Author

**Areesha Manahil**

Aspiring Data Analyst | Python | SQL | Excel | Power BI

This project is part of my Data Analytics portfolio, where I focus on solving practical problems, exploring real-world datasets and communicating insights through data.
