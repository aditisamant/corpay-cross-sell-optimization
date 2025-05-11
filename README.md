# Corpay: Cross-Sell Strategy Enhancement and Model Building

## Project Overview

In this project, I led the enhancement of Corpay’s Cross-Sell Strategy by applying advanced data analytics and predictive modeling to optimize customer eligibility for the Universal Card program. The goal was to identify customers with high creditworthiness, reduce risk exposure, and ultimately drive revenue growth through better-targeted offerings.

This initiative involved cleaning and preparing data using SQL and Alteryx, engineering relevant features in R, and building classification models using Logistic Regression, Decision Trees, and Random Forests. The results were translated into business recommendations and visualized through an interactive Power BI dashboard.

---

## Business Outcomes

- **Refined Eligibility Criteria**: Revised selection logic using Days Past Due (DPD), NSF (Non-Sufficient Funds) occurrences, and account activity.
- **Targeted Customer Segmentation**: Identified 13 customers for exclusion and 601 customers for inclusion in the Universal Card program.
- **Revenue Uplift**: Projected **15.60% increase** in revenue due to optimized targeting.
- **Executive Dashboard**: Delivered insights via an interactive Power BI dashboard with views of delinquency, write-offs, spend, and revenue.

---

## Tools & Technologies Used

- **SQL**: Structured raw data into aggregated, analyzable views.
- **Alteryx**: Addressed missing values and improved overall data quality.
- **R Programming**:
  - Feature engineering and normalization
  - Multicollinearity mitigation using Variance Inflation Factor (VIF)
  - Predictive model development
- **Power BI**: Built dashboards for business storytelling and executive reporting.

---

## Modeling Techniques

### 1.Logistic Regression
- **Goal**: Classify customers as "Risky" or "Not Risky" based on NSF history.
- **Accuracy**:
  - Training: 89.20%
  - Validation: 89.70%
- **Interpretability**: Provided a transparent model with actionable coefficient analysis.

### 2.Decision Tree
- **Algorithm**: `rpart` with pruning parameter (`cp = 0.007`).
- **Strength**: Clear decision rules for customer risk evaluation.

### 3.Random Forest
- **Configuration**: 500 trees built for higher model stability and accuracy.
- **Insights**: Feature importance ranking supported decision-making.
- **Advantage**: Improved generalization and performance over single models.

---

## Visualizations & Insights

The **Power BI dashboard** includes:
- **Delinquency Trends**: Analyzed by time and customer group.
- **Write-Offs**: Monitored by region and product line.
- **Spending Behavior**: Monthly analysis of customer spend patterns.
- **Revenue Projections**: Comparison between existing and optimized customer segments.
- **Interactivity**: Filters by region, account type, and risk category.

---

## Key Recommendations

1. **Ensure Data Quality**: Maintain regular data updates and validation routines.
2. **Expand Feature Set**: Include additional variables to capture more behavioral signals.
3. **Retrain Models Regularly**: Keep models aligned with evolving customer behavior.
4. **Integrate into CRM**: Use model outputs for personalized marketing and product offers.

---

## Conclusion

Corpay’s initiative to optimize its cross-sell program is a prime example of how data science can drive measurable business value. The models I developed not only enhanced revenue potential but also strengthened credit risk management, providing the company with a strategic edge in decision-making.

---



