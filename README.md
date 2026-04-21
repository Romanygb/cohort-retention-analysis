# 📊 Cohort Retention Analysis

Customer retention analysis using cohort methodology to identify patterns and actionable opportunities for improving customer lifetime value in e-commerce.

## 🎯 Project Overview

- **Dataset:** Online Retail Dataset (541,909 transactions, 4,370 customers, 2010-2011)
- **Tools:** Python, Pandas, SQL, PostgreSQL, Seaborn
- **Analysis Type:** Cohort-based retention analysis
- **Business Goal:** Understand why customers don't return and develop retention strategies

## 🔍 Key Findings

### Critical Insights

- **Low baseline retention:** Only 10-20% of customers return after first purchase
- **Exceptional cohort:** January 2011 maintained 40%+ retention (vs 10-15% average)
- **Rapid drop-off:** Most customers lost within 30 days of first purchase

### Visual Analysis

The retention heatmap reveals:
- Strong first-month engagement (100% by definition)
- Sharp decline in month 2 across most cohorts
- Stabilization around 10-15% retention after month 3

## 💡 Business Recommendations

### Immediate Actions
1. **Study January 2011 cohort** - identify what drove 3x better retention
2. **Improve onboarding** - educate new customers on product value
3. **30-day win-back campaign** - re-engage customers before they churn

### Strategic Initiatives
4. Launch loyalty program with rewards for repeat purchases
5. Survey churned customers to identify friction points
6. A/B test second-purchase incentives

### Expected Impact
- Target: Increase month-1 retention from 15% to 25%
- Projected: 30% improvement in customer lifetime value

## 📈 Methodology

**Cohort Definition:** Customers grouped by month of first purchase

**Retention Calculation:**
Retention % = (Customers who purchased in month N / Cohort size) × 100

**Analysis Approach:**
1. Define cohorts based on first purchase date
2. Track purchasing behavior over subsequent months
3. Calculate retention rates for each cohort-month combination
4. Visualize patterns using heatmap
5. Identify anomalies and actionable insights

## 🛠️ Technical Skills Demonstrated

- **Advanced SQL:** CTE (Common Table Expressions), complex JOINs, date manipulation
- **Cohort Analysis:** Customer segmentation, retention metrics, time-based analysis
- **Data Visualization:** Heatmaps with Seaborn, strategic use of color coding
- **Statistical Analysis:** Trend identification, cohort comparison
- **Business Strategy:** Translating data insights into actionable recommendations

## 📁 Files

- `Cohort_Retention_Analysis.ipynb` - Complete analysis with visualizations
- `cohort_retention_full.csv` - Processed retention data

## 📫 Contact

**Roman** | [GitHub](https://github.com/Romanygb)

---

## 🔗 Related Projects

- [Superstore Sales Analysis](https://github.com/Romanygb/superstore-sales-analysis) - Exploratory data analysis

---

*Part of my Data Analyst portfolio demonstrating advanced analytical techniques and business acumen*
