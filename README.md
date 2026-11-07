# Analysis_of_social_media_in_students
### An Exploratory Data Analysis & Machine Learning Project

## About the Project

Analysis of Social Media in Students is a data science project that explores the impact of social media usage on students' mental health, sleep patterns, addiction levels, and academic performance.

The project combines primary data collected through Google Forms with a secondary Kaggle dataset to identify trends, correlations, and meaningful insights using Python, Machine Learning, and Tableau.

## Objectives

- Analyze daily social media usage patterns among students.
- Examine the relationship between social media usage and addiction levels.
- Investigate the impact of social media on academic performance.
- Explore the association between social media usage, sleep duration, and mental health.
- Apply machine learning algorithms to analyze and predict addiction scores.
- Develop interactive dashboards to communicate analytical findings.

## Tech Stack

- **Programming:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Dashboard Development:** Tableau
- **Web Development:** HTML, CSS, JavaScript
- **Data Collection:** Google Forms, Google Sheets
- **Dataset Source:** Kaggle

## Dataset

The project uses two data sources:

1. Primary Dataset – Survey responses collected from college students using Google Forms.
2. Secondary Dataset – Student social media dataset obtained from Kaggle.

The datasets were cleaned, preprocessed, and merged into a consistent structure for analysis.

### Key Features

| Feature | Description |
|---|---|
| Age | Student's age |
| Gender | Student's gender |
| Academic_Level | Academic level |
| Country | Country |
| Avg_Daily_Usage_Hours | Daily social media usage |
| Most_Used_Platform | Preferred social media platform |
| Affects_Academic_Performance | Academic performance impact |
| Sleep_Hours_Per_Night | Average sleeping hours |
| Mental_Health_Score | Mental health score |
| Relationship_Status | Relationship status |
| Conflicts_Over_Social_Media | Social media-related conflicts |
| Addicted_Score | Addiction score |

## Project Workflow

### 1. Data Collection
- Collected student responses through Google Forms.
- Obtained additional data from Kaggle.
- Combined datasets after standardizing their structure.

### 2. Data Cleaning & Preprocessing
- Handled missing and inconsistent values.
- Standardized column names and data types.
- Processed categorical variables.
- Applied one-hot encoding to social media platforms.

### 3. Exploratory Data Analysis (EDA)
Performed analysis to identify:
- Social media usage trends.
- Most popular social media platforms.
- Addiction score distribution.
- Mental health patterns.
- Sleep duration trends.
- Academic performance relationships.

### 4. Machine Learning

**Simple Linear Regression**

Analyzed the relationship between daily social media usage and addiction scores.

Regression equation:

`Addicted_Score = 1.39 + 1.82 × Avg_Daily_Usage_Hours`

**Multiple Linear Regression**

Developed a regression model to analyze addiction scores using:

- Academic Level
- Average Daily Usage Hours
- Academic Performance Impact
- Sleep Hours
- Mental Health Score
- Social Media Conflicts

The dataset was divided into training and testing sets using a 70:30 split.

An additional regression analysis was performed with Mental Health Score as the target variable.

### 5. Tableau Dashboards

Developed three dashboards to present analytical insights.

- **Dashboard 1 – KPI Overview:** Average addiction score, mental health score, daily usage hours, and sleep duration.
- **Dashboard 2 – Usage Analysis:** Social media platform preferences, usage patterns, and student demographics.
- **Dashboard 3 – Advanced Insights:** Relationships between social media addiction, mental health, sleep, and academic performance.

### 6. Website Development

Created a website using HTML, CSS, and JavaScript to showcase the project and its findings.

Website sections:
- About
- KPIs
- Basic Insights
- Advanced Insights
- Findings
- About Me

## Key Insights

| Metric | Average |
|---|---:|
| Mental Health Score | 6.19 |
| Addiction Score | 6.36 |
| Daily Usage | 4.8 Hours |
| Sleep Duration | 6.8 Hours |

The Simple Linear Regression analysis indicated a positive association between daily social media usage and addiction scores.

The project further explores how sleep patterns, mental health, academic performance, and social media-related conflicts relate to addiction levels.

*These findings represent exploratory analysis and statistical associations, not causal conclusions.*

## Project Screenshots

Add your Tableau dashboard screenshots in the `Images` folder and display them here.

### Dashboard 1 – KPI Overview

![KPI Dashboard](Images/dashboard1.png)

### Dashboard 2 – Social Media Usage Analysis

![Usage Analysis](Images/dashboard2.png)

### Dashboard 3 – Advanced Insights

![Advanced Insights](Images/dashboard3.png)

## Future Enhancements

- Experiment with advanced machine learning algorithms.
- Improve model performance through feature engineering.
- Incorporate larger and more diverse datasets.
- Develop an interactive analytics application.
- Explore classification models for addiction-level prediction.

## Skills Demonstrated

- Data Collection and Preprocessing
- Exploratory Data Analysis
- Statistical Analysis
- Machine Learning
- Linear Regression
- Data Visualization
- Dashboard Development
- Data Storytelling
- Web Development

## Author

**Kulpreet Kaur**

BCA Graduate | Aspiring Data Scientist

**Technical Skills:** Python | SQL | Tableau | Power BI | Machine Learning | Data Analytics

---

⭐ If you find this project interesting, consider giving this repository a star!
