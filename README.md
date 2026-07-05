# Comprehensive-Analysis-of-Academic-Journal-Ranking-Metrics-and-Influencing-Factors

## Academic Journal Ranking Analysis
**Overview**
This project performs an in-depth exploratory data analysis (EDA) on a dataset of academic journals to understand various factors influencing their rankings. We investigate key metrics like SJR-index, CiteScore, and H-index, analyze the impact of publishers and countries, compare Open Access vs. traditional publishing models, and examine performance across different subject areas. The goal is to uncover patterns, correlations, and key insights into what drives a journal's influence in the academic world.

**Dataset**
The analysis utilizes journal_ranking_data.csv, a dataset containing comprehensive information about academic journals. Key features include:

**Ranking Metrics**: SJR-index, CiteScore, H-index, Total Docs., Total Cites 3y.
**Journal Attributes**: Title, Open Access status (OA), Country, Publisher.
**Subject Area Classifications**: Best Quartile, Best Subject Area, and binary indicators for top-level subject areas (Life Sciences, Social Sciences, Physical Sciences, Health Sciences).
**Key Findings and Insights**
**Metric Distributions & Outliers**: Ranking metrics ('SJR-index', 'CiteScore', 'H-index') are heavily right-skewed with significant outliers, indicating that a small number of journals exhibit disproportionately high influence.

**Publisher and Geographic Dominance:**

**Publishers**: Elsevier, Wiley, and Oxford University Press consistently demonstrate superior average ranking metrics among the top publishers, highlighting their strong portfolio of high-impact journals.
**Countries**: The United States, United Kingdom, and Netherlands lead in average ranking metrics, suggesting a concentration of high-quality research output from these regions.
**Open Access vs. Traditional Publishing**: Non-Open Access journals generally show higher average 'SJR-index', 'CiteScore', and 'H-index' compared to Open Access journals in this dataset, implying that traditional publishing models still host journals with higher impact.

**Subject Area Performance:**

'Social Sciences' has the highest count of Q1 (highly-ranked) journals. However, when examining average metrics within Q1 journals, 'Life Sciences' and 'Health Sciences' generally show higher average 'SJR-index', 'CiteScore', and 'H-index', indicating greater impact per journal in these fields.
Metric Correlation: A very strong positive correlation (0.86) exists between 'SJR-index' and 'CiteScore', suggesting they largely measure similar aspects of journal influence. Other strong correlations were also observed among citation-related metrics.

**Technologies Used**
Python 3
Pandas (for data manipulation and analysis)
Matplotlib (for data visualization)
Seaborn (for enhanced statistical data visualization)
