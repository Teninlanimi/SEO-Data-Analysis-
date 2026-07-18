# SEO-Data-Analysis with Python

## Project Overview

This project explores an SEO performance dataset using Python to uncover insights into search performance, click-through rates (CTR), keyword search volume, and content performance. The goal was to investigate common SEO assumptions using exploratory data analysis (EDA) and statistical techniques.

## Objectives

* Clean and prepare SEO data for analysis.
* Explore relationships between search volume, impressions, CTR, and ranking position.
* Test common SEO beliefs using data.
* Create visualizations to communicate findings.
* Draw actionable insights from the analysis.

## Dataset

The dataset contains SEO performance metrics for thousands of webpages, including:

* Search Volume
* Impressions (90 days)
* Clicks (90 days)
* Click-Through Rate (CTR)
* Average Position
* Position Tier
* Content Type
* Trend Direction
* Content Age (Days)

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Google Collab 

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Hypothesis Testing
5. Data Visualization
6. Key Insights

## Key Discoveries

### Discovery 1: High Search Volume ≠ More Traffic

The correlation between keyword search volume and page impressions was almost zero, suggesting that search volume alone is not a reliable predictor of the traffic a page receives.

### Discovery 2: Ranking Position Influences CTR

Pages in higher position tiers consistently achieved higher click-through rates (CTR), confirming that better search rankings generally lead to more user clicks.

### Discovery 3: Content Type Matters

When comparing pages within the same ranking position, some content types consistently attracted lower CTR than others, showing that content format influences user engagement beyond ranking alone.

## Repository Structure

```text
SEO-Data-Analysis/
│
├── notebooks/
│   └── seo_analysis.ipynb
│
├── data/
│
├── images/
│
├── README.md
└── requirements.txt
```

## Future Improvements

* Build predictive models for CTR.
* Develop an interactive dashboard using Streamlit or Power BI.
* Perform feature importance analysis using machine learning models.
* Expand the analysis with additional SEO metrics.

## Author

**Teninlanimi Faith Olajide**

Machine Learning Engineer | Data Science Enthusiast | AI Learner

Thank you for visiting this project. Feedback and suggestions are always welcome.

