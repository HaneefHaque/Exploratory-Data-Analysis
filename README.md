# Exploratory-Data-Analysis

### Project Overview

This exploratory data analysis (EDA) project is using a global tech layoffs dataset to identify patterns and trends in workforce reductions from 2020 onwards. The objective was to uncover which companies, industries, and countries were most affected, and how layoff activity evolved over time. This simulated a real-world scenario in which data-driven insights could inform economic, risk, or policy decisions.

### Data Sources

World Layoff Data: The primary dataset used for this project is the "layoffs.csv" file.

### Process
SQL Analysis: Imported the cleaned dataset into a staging table (layoffs_staging2) and used SQL to:

- Determine the date range and maximum layoff metrics.

- Identify companies with the highest number and percentage of layoffs.

- Aggregate total layoffs by company, industry, and country.

- Track layoffs over time using monthly and yearly groupings.

- Calculate rolling totals to observe cumulative trends.

- Rank the top 5 companies by layoffs per year using CTEs and window functions.

### Result

- Identified key employers with the highest layoffs (both by count and proportion).

- Discovered that the technology sector and the United States experienced the most layoffs overall.

- Revealed peaks in layoffs during specific months and years, suggesting broader economic or sectoral challenges.

- Developed insights that could inform strategic decisions for risk assessment, economic forecasting, or workforce planning.

### Limitations

- Some rows still contained missing values (e.g., total_laid_off, industry), which may affect accuracy.

- Lack of contextual company data (e.g., workforce size, revenue) limited the depth of solvency or risk analysis.

- The dataset may be biased towards larger companies or those with more public reporting.

- Ambiguities in multi-country company operations were not resolved due to data constraints.
