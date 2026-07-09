# Digital Marketing Campaign Performance Analysis

![Excel](https://img.shields.io/badge/Microsoft_Excel-Statistical_Analysis-217346)
![Tableau](https://img.shields.io/badge/Tableau-Data_Visualization-005570)
![Statistics](https://img.shields.io/badge/Statistics-Hypothesis_Testing-orange)
![Regression](https://img.shields.io/badge/Regression-Linear_Model-green)
![Analytics](https://img.shields.io/badge/Business-Analytics-blueviolet)

---

# Project Overview

This project analyzes the performance of **Facebook and AdWords digital marketing campaigns** to identify which platform delivers better conversion performance.

The analysis combines **Excel statistical analysis** and **Tableau visualization** to evaluate campaign effectiveness, test whether performance differences are statistically significant, and understand the relationship between clicks and conversions.

The final goal is to provide **data-driven recommendations for marketing budget allocation and campaign optimization**.

---

# Business Problem

A marketing team is running advertising campaigns across multiple digital platforms but needs evidence-based insights to answer:

* Which platform generates higher conversions?
* Are conversion differences statistically significant?
* Which platform has a stronger relationship between clicks and conversions?
* Where should marketing budget be allocated to maximize campaign performance?

---

# Project Objectives

The main objectives of this analysis are:

* Compare Facebook and AdWords campaign performance.
* Analyze conversion efficiency across platforms.
* Perform statistical hypothesis testing.
* Measure the relationship between clicks and conversions.
* Build a regression model to understand conversion trends.
* Provide actionable recommendations for marketing decisions.

---

# Dataset

The dataset contains digital advertising campaign metrics for:

* Facebook campaigns
* AdWords campaigns

### Key Metrics:

| Metric       | Description                                   |
| ------------ | --------------------------------------------- |
| Impressions  | Number of times advertisements were displayed |
| Clicks       | Number of user interactions with ads          |
| Conversions  | Number of successful outcomes                 |
| Cost Metrics | Campaign spending information                 |

---

# Tools & Technologies

## Microsoft Excel

Used for:

* Data preparation
* Descriptive statistics
* Correlation analysis
* Scatter plots
* Two-sample t-test
* Statistical interpretation

## Tableau

Used for:

* Data visualization
* Regression analysis
* Trend line modeling
* Business storytelling

---

# Data Analysis Workflow

The project followed the following analytical process:

```
Data Understanding
        ↓
Data Preparation
        ↓
Exploratory Data Analysis
        ↓
Statistical Testing
        ↓
Regression Analysis
        ↓
Business Insights
        ↓
Recommendations
```

---

# Statistical Analysis

## 1. Descriptive Statistics

Performance comparison between Facebook and AdWords:

| Metric                        | Facebook | AdWords | Insight                                               |
| ----------------------------- | -------: | ------: | ----------------------------------------------------- |
| Average Clicks                |    44.05 |   60.38 | AdWords generated more clicks                         |
| Average Conversions           |    11.74 |    5.98 | Facebook generated nearly double conversions          |
| Conversion Standard Deviation |     2.92 |    1.63 | Facebook showed higher variation and growth potential |

### Key Insight

Although AdWords generated more clicks, Facebook produced significantly higher conversions, indicating stronger conversion efficiency.

---

# 2. Correlation Analysis

Correlation was used to measure the relationship between clicks and conversions.

### Results:

| Platform | Correlation (r) | Interpretation               |
| -------- | --------------: | ---------------------------- |
| Facebook |            0.87 | Strong positive relationship |
| AdWords  |            0.45 | Moderate relationship        |

### Insight

Facebook conversions were more strongly associated with clicks, making campaign outcomes more predictable.

---

# 3. Hypothesis Testing

A two-sample t-test was performed to determine whether the difference in conversion performance between Facebook and AdWords was statistically significant.

### Hypothesis:

**Null Hypothesis (H₀):**
There is no significant difference in average conversions between Facebook and AdWords.

**Alternative Hypothesis (H₁):**
There is a significant difference in average conversions between Facebook and AdWords.

### Result:

* p-value < 0.05
* Reject H₀

### Conclusion:

The difference in conversion performance between platforms is statistically significant.

---

# 4. Linear Regression Analysis

A simple linear regression model was created in Tableau to analyze the relationship between Facebook clicks and conversions.

### Regression Equation:

```
Facebook Conversions = 0.204371 × Facebook Clicks + 2.76793
```

### Interpretation:

* Every additional click is associated with approximately **0.2 additional conversions**.
* The strong correlation supports the reliability of the relationship.
* The model provides insight into expected conversion changes as campaign engagement increases.

---

# Tableau Regression Visualization

<img width="1161" height="469" alt="Facebook Regression Analysis" src="https://github.com/user-attachments/assets/b190d3bf-e415-4e8d-be5d-33ed02cfcacc" />

### Tableau Public Dashboard

https://public.tableau.com/app/profile/sumaya.mateen/viz/Book1_17622622567270/RegressionModelFB

---

# Key Business Insights

## Campaign Performance

* Facebook achieved higher average conversions compared with AdWords.
* AdWords generated more clicks but converted users less effectively.
* Facebook demonstrated stronger conversion predictability.

## Statistical Findings

* Statistical testing confirmed a significant difference between platforms.
* Facebook performance showed stronger relationship between engagement and conversions.

---

# Business Recommendations

Based on the analysis:

### 1. Optimize Marketing Budget Allocation

Increase investment in Facebook campaigns due to stronger conversion performance.

### 2. Improve AdWords Conversion Funnel

Investigate:

* Audience targeting
* Landing page experience
* Ad relevance

to improve conversion efficiency.

### 3. Use Regression Insights for Planning

Use the regression relationship to estimate expected conversion changes from increased campaign engagement.

### 4. Monitor Campaign KPIs

Track:

* Click-through rate
* Conversion rate
* Cost per conversion
* Return on advertising spend (ROAS)

for continuous optimization.

---

# Business Impact

| Impact Area            | Outcome                                               |
| ---------------------- | ----------------------------------------------------- |
| Marketing Strategy     | Identified higher-performing advertising channel      |
| Decision Making        | Supported budget decisions using statistical evidence |
| Campaign Optimization  | Provided insights into conversion drivers             |
| Performance Monitoring | Established measurable campaign KPIs                  |

---

# Skills Demonstrated

* Business Analytics
* Data Cleaning
* Exploratory Data Analysis
* Statistical Analysis
* Hypothesis Testing
* Correlation Analysis
* Linear Regression
* Excel Analytics
* Tableau Visualization
* Data Storytelling
* Business Recommendations

---

# Repository Structure

```
Digital-Marketing-Campaign-Analysis

│
├── Data
│   └── Digital_Campaign_Performance.xlsx
│
├── Report
│   └── Campaign_Performance_Analysis.pdf
│
├── Images
│   └── Regression_Analysis.png
│
└── README.md
```

---

# Files Included

| File                              | Description                                                         |
| --------------------------------- | ------------------------------------------------------------------- |
| Digital_Campaign_Performance.xlsx | Excel workbook containing campaign metrics and statistical analysis |
| Campaign_Performance_Analysis.pdf | Detailed analysis report and findings                               |

---

# Project Context

**Focus Area:** Marketing Analytics, Statistical Analysis, Business Decision Making

This project demonstrates an end-to-end analytical approach to transforming campaign data into actionable business insights.
