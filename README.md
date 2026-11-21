
# E-Commerce Sales & Customer Analysis

## Project Overview

This project explores E-commerce customer and purchasing data to understand business performance, customer characteristics, purchasing behaviour and technology preferences.

Using Microsoft Power BI, the project transforms customer and sales data into an interactive two-page dashboard designed to provide business insights and support data-driven decision-making.

The dashboard combines a high-level performance overview with detailed customer analysis, allowing users to explore both business performance and customer patterns.

## Business Problem

E-commerce businesses need to understand their sales performance, customer composition and purchasing patterns to make informed business decisions.

However, customer and purchasing data can contain valuable information that is difficult to interpret without proper analysis and visualization.

This project addresses the need to organize and analyse e-commerce data to identify meaningful patterns in revenue, customer segmentation, purchasing behaviour and technology usage.


## Project Objectives

-Evaluate overall e-commerce business performance using key performance indicators.
-Analyse revenue contribution across credit card providers.
-Understand customer segmentation based on language, occupation and email providers.
-Examine purchasing patterns across morning and evening periods.
-Explore average purchase prices across relevant customer segments.
-Identify customer technology preferences based on browser and operating system usage.
-Present findings through an interactive Power BI dashboard.

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX

## Key Performance Indicators (KPIs)

- Total Revenue
- Total Customers
- Total Purchases
- Average Purchase Price

## Dashboard Pages & Analysis

### 1. E-Commerce Performance Overview

Provides a high-level summary of business performance and key customer purchasing patterns.

**Key Analysis:**
- Overall business performance through KPI cards.
- Revenue by Credit Card Provider.
- Customer Purchasing Behaviour (AM/PM).
- Customer Distribution by Language.

**Business Focus:** Understanding overall business performance and identifying important revenue and customer activity patterns.
## Dashboard Preview
![E-Commerce Performance Overview](Preview/page1-overview.png)


### 2. Customer & Behaviour Analysis

Provides a deeper exploration of customer characteristics, purchasing behaviour, spending patterns, and technology preferences.

**Customer Segmentation**
- Customer Count by Language.

**Occupation Analysis**
- Top 10 Jobs by Customer Count.

**Email Analysis**
- Customer Count by Email Provider.

**Purchase Behaviour**
- Purchases by AM/PM.

**Spending Analysis**
- Average Purchase Price by relevant customer segments.

**Technology Insights**
- Customer Count by Browser.
- Customer Count by Operating System.
- Browser and Operating System Analysis.

### Dashboard Preview

[Customer & Behaviour Analysis](Customer-Behaviour-Dashboard.png)







## Key Business Questions

This analysis explores the following questions:

1. How is the e-commerce business performing in terms of revenue and purchasing activity?
2. Which credit card providers contribute the most revenue?
3. How are customers distributed across different language groups?
4. Which occupations are most common among customers?
5. Which email providers are most frequently used?
6. Do purchasing patterns differ between morning and evening?
7. How does average purchase price vary across customer segments?
8. Which browsers and operating systems are most commonly used by customers?

## Analytical Considerations

- The dataset does not contain an actual transaction date or timestamp; therefore, daily, monthly, and yearly sales trends cannot be reliably analysed.
- The AM/PM field supports time-of-day purchasing analysis.
- Credit card expiry dates are not treated as transaction dates.
- Customer and purchase counts are interpreted according to the available dataset structure.

## Business Value

The analysis provides insights that can help e-commerce businesses:

- Monitor revenue contribution across payment providers.
- Understand customer composition and segmentation.
- Identify important customer groups for targeted marketing.
- Understand purchasing activity across different periods of the day.
- Explore customer spending patterns.
- Understand the technology platforms used by customers.

## Conclusion

This project demonstrates the application of data analysis and visualization techniques to transform e-commerce data into meaningful business insights.

Through an interactive Power BI dashboard, the analysis brings together business performance, customer segmentation, purchasing behaviour, and technology insights to support informed business decision-making.

## Project Structure

```text
E-Commerce-Sales-Customer-Analysis/
│
├── Dashboard/
│   └── E-Commerce Sales & Customer Analysis.pbix
│
├── Dataset/
│   └── dataset.csv
│
├── Screenshots/
│
├── Preview/
│   ├── page1-overview.png
│   └── page2-customer-analysis.png
│
└── README.md
```

---

**Tools:** Power BI | Power Query | DAX | Data Analysis | Data Visualization

*Turning data into meaningful business insights.*
