# Ghana Banking Sector Crisis Analysis (2017–2019)

## Project Overview

This project investigates the causes, corporate governance failures, financial impact, and regulatory response surrounding Ghana's banking sector cleanup between 2017 and 2019.

Using financial and regulatory information from the Bank of Ghana, Ministry of Finance, and IMF publications, the analysis examines 17 financial institutions, including collapsed commercial banks, specialized deposit-taking institutions, and surviving banks.

The project uses financial ratio analysis, correlation analysis, and a custom institutional risk scoring framework to assess financial distress and identify patterns associated with institutional failure.

## Tools and Technologies

- **Microsoft Power BI:** Interactive dashboards, KPI tracking, and data visualization.
- **Microsoft Excel:** Financial ratio analysis, correlation analysis, and risk score calculations.
- **Data Sources:** Bank of Ghana reports, regulatory announcements, Ministry of Finance documents, and IMF publications.

## Key Analytical Findings

### 1. Financial Distress Indicators

- Non-Performing Loan (NPL) ratio showed a strong positive correlation with institutional collapse (r = +0.91).
- Collapsed commercial banks recorded an average NPL ratio of 31.6%.
- Capital Adequacy Ratio (CAR) showed a strong negative correlation with institutional collapse (r = -0.88).
- uniBank and Beige Bank recorded negative capital adequacy ratios of -12.4% and -8%, respectively.

### 2. Corporate Governance and External Auditing

The analysis identified a strong association between external audit firm category and institutional survival.

- All banks in the sample audited by Big Four firms survived.
- All commercial banks in the sample audited by local audit firms collapsed.

These findings describe the project sample and do not establish that audit firm category caused institutional failure.

### 3. Related-Party Lending

The analysis identified related-party lending as an important factor in institutional financial distress.

- uniBank: GHS 5.3 billion in related-party lending.
- Beige Bank: GHS 1.2 billion in related-party lending.

The analysis examines the relationship between insider lending, collateral practices, and institutional financial stability.

### 4. Economic and Employment Impact

The banking sector cleanup had significant financial and social implications.

The project examines reported estimates including:

- GHS 21 billion in government financial support.
- More than 3.2 million affected depositors.
- Approximately 6,760 direct banking job losses.

## Custom Institutional Risk Scoring Framework

I developed a weighted Overall Risk Score on a scale of 1–10 using three financial indicators:

| Indicator | Weight |
|---|---:|
| Non-Performing Loan Ratio | 45% |
| Capital Adequacy Ratio | 35% |
| Liquidity Ratio | 20% |
| Total | 100% |

The framework combines these indicators to assess institutional financial vulnerability and estimate risk levels.

The model flagged distressed institutions with estimated collapse probabilities ranging from 95% to 99%.

These estimates represent outputs from the project's analytical framework, not official regulatory probabilities.


- ## Project Files

### 1. Python Analysis
Python notebook containing the data analysis, calculations, and analytical procedures.

### 2. PowerPoint Presentation
Project presentation covering the banking sector cleanup, financial distress indicators, corporate governance issues, correlation analysis, and key findings.

### 3. Power BI Dashboard
Dashboard visualization presenting the financial indicators, institutional comparisons, and risk assessment results.

## Project Structure

- `python/` - Python analysis notebook.
- `presentation/` - PowerPoint presentation.
- `dashboard/` - Power BI dashboard screenshot.

Power BI dashboard screenshots will be added here.

## Conclusion

The analysis highlights the importance of asset quality, capital adequacy, liquidity management, and corporate governance in maintaining financial sector stability.

The project demonstrates the application of financial analysis, data modelling, risk assessment, and business intelligence techniques to a real-world financial sector case study.
