# website-traffic-analysis-sql
This project analyzes website traffic and user behavior using SQL to understand how visitors interact with a website and how different traffic sources contribute to business performance.

---

## Business Problem
The business lacks clear visibility into traffic sources and early user engagement, making it difficult to:
- Evaluate marketing channel performance
- Understand landing page effectiveness
- Identify opportunities for business and financial growth

### Business Goal
To examine website traffic patterns by analyzing:
- Session volume
- Traffic source attribution
- Landing page behavior  

with the objective of boosting sales, reducing acquisition costs, and building a loyal customer base.

---

## Dataset
**Source:** Kaggle – Toy Store E-Commerce Database  

The analysis is based on three relational tables:
- `website_sessions`
- `website_pageviews`
- `orders`

---

## Tools & Technologies
- SQL (PostgreSQL via pgAdmin)
- CSV data sources
- Data visualization with Tableau

---

## Analysis Summary

### Key Findings
- Approximately **18% of sessions are attributed to direct/unknown traffic**, indicating gaps in tracking.
- The **top two landing pages account for nearly 63% of all user sessions**, making them high-impact optimization targets.

### Business Recommendations
- **Improve UTM parameter tracking** to reduce attribution gaps and enable more accurate channel performance analysis.
- **Prioritize optimization of the top two landing pages** to improve engagement, customer experience, and loyalty.

---

## Techniques Used

### Data Acquisition
- Imported data from three CSV files
- Created three relational tables in PostgreSQL:
  - `website_pageviews`
  - `website_sessions`
  - `orders`

### Data Preparation
- Data cleaning techniques:
  - `NOT NULL` constraints
  - `LOWER()`
  - `NULLIF()` and `COALESCE()`

### Data Manipulation
- `LEFT JOIN`
- `COUNT(DISTINCT)`
- `GROUP BY`
- `ORDER BY`
- `ROUND`

### Analytical Methods
- Descriptive analysis
- Frequency counts
- Aggregations
- Percentages and proportions
- Ranking and ordering

---

## Limitations & Future Work
If more time were available, additional analysis would include:
- A/B testing to compare landing page conversion rates
- Funnel drop-off analysis to identify where users disengage

---

## How This Project Is Used
This project is intended for:
- GitHub portfolio showcase
- LinkedIn portfolio sharing
- Demonstrating real-world SQL analysis skills to employers

