# Airplane Acquisition Risk Assessment

**Author:** Antony Amunia Wala

## Overview

This project analyzes the NTSB aviation accident dataset to provide data-driven recommendations for a company expanding into the aviation industry. The primary goal is to identify aircraft models with the lowest historical risk to guide the company's initial purchasing strategy. The analysis involves comprehensive data cleaning, feature engineering, and visualization to translate raw data into actionable business insights.

## Business Understanding

A corporation is diversifying its portfolio by entering the commercial and private aviation sector. As the primary stakeholder, the head of this new division lacks domain expertise and needs to understand the potential risks associated with operating different aircraft. The key business question is: **Which aircraft models present the lowest risk for an initial fleet acquisition?** This analysis aims to answer that question with clear, data-driven recommendations.

## Data Understanding and Analysis

### Data Source and Description
The dataset is sourced from the **National Transportation Safety Board (NTSB)** and contains records of civil aviation accidents in the United States. To ensure the findings are relevant to modern safety standards and aircraft, the analysis was focused on incidents occurring from **the year 2000 to the present**.

A custom **‘Risk Score’** was engineered to measure the severity of each incident by giving more weight to accidents involving serious or fatal injuries. This provides a more accurate picture of risk than simply counting the number of incidents.

### Visualizations

Three key insights were visualized in the dashboard:

1.  **Lowest-Risk Aircraft Models:** Identifies common aircraft with the best historical safety records.
2.  **Incident Severity by Engine Type:** Shows that reciprocating engines, while frequent, are involved in less severe incidents on average.
3.  **The Impact of Adverse Weather on Incident Severity:** Starkly illustrates that incidents in bad weather (IMC) are dramatically more severe.

## Interactive Dashboard

An interactive dashboard was created in Tableau to allow stakeholders to explore the findings dynamically. The dashboard provides an at-a-glance overview of aircraft risk profiles and allows for filtering by various parameters.

**[Click here to view and interact with the live dashboard on Tableau Public](https://public.tableau.com/app/profile/antony.wala/viz/AirplaneAquisitionRiskAssesment/Dashboard1)**

## Conclusion

The analysis provided a clear flight path for a risk-averse acquisition strategy. The conclusions are based on the following three key findings:

1.  **Specific models have proven safety records:** The data clearly shows that a distinct group of common aircraft, particularly models like the **Cessna 152** and **Piper PA-18**, have a demonstrably lower average risk score.
2.  **Reciprocating engines are a prudent initial choice:** While incidents involving reciprocating engines are frequent, their average severity is significantly lower than that of more complex turbine engines, making them a safer initial investment.
3.  **Adverse weather is the greatest risk multiplier:** The most critical finding is that incidents in bad weather (IMC) are dramatically more severe than those in good weather (VMC).

Based on these findings, the primary business recommendation is to **begin the fleet with reciprocating-engine aircraft from the list of lowest-risk models, and to invest heavily in an advanced pilot training program focused on adverse weather conditions.**