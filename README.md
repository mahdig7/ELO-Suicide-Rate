# MIT Emerging Talent
# Exploratory Data Analysis and Visualization on Suicide Rate (1985 – 2016) Dataset
## Overview
Understanding suicide rates is of paramount importance as it is a significant public health issue with far-reaching consequences. By analyzing this dataset, we can gain valuable insights into the factors associated with suicide and develop effective prevention strategies. However, the complexities involved in studying suicide make it a challenging problem to tackle.
The motivations for exploring this dataset and defining specific project questions arise from the need to address the alarming global suicide rates and their impact on individuals, families, and communities. Preliminary exploratory data analysis (EDA) helps us understand the dataset's structure, identify trends, patterns, and potential relationships, and formulate research questions.

## Problem Statement
The goal of this project is to gain insights into global suicide rates and understand the factors associated with them. Through exploratory data analysis and visualization, I aim to uncover patterns, trends, and potential correlations within the dataset.
To reach these goals, I will perform thorough exploratory data analysis using various insightful questions and visualizations. The preliminary EDA will help define the project question and guide our analysis. By examining the dataset from different angles and asking specific questions, I can uncover meaningful insights and tell a comprehensive story about global suicide rates.

## The Dataset
The dataset used in this project is downloaded from the Kaggle.com website and was mainly obtained from the World Health Organization (WHO).
The suicide dataset provides comprehensive information on suicide rates across different countries, years, genders, age groups, and economic factors. It includes variables such as 'country', 'year', 'sex', 'age', 'suicides_no', 'population', 'suicides/100k_pop', 'country-year', 'gdp_for_year', 'gdp_per_capita', and 'generation'.
https://www.kaggle.com/datasets/russellyates88/suicide-rates-overview-1985-to-2016

## Cleaning
<ul>
<li> New names were assigned to specific columns in the dataframe, making it easier to work with and refer to those columns in subsequent analyses or visualizations.
<ul><li>"suicides/100k pop" is renamed to "suicides_pop".</li>
<li>"HDI for year" is renamed to "HDI_for_year".</li>
<li>" gdp_for_year ($) " is renamed to "gdp_for_year".</li>
<li>" gdp_per_capita ($) " is renamed to "gdp_per_capita".</li>
<li>"gdp_per_capita ($)" is also renamed to "gdp_per_capita".</li></ul>
<li> The column "HDI for year" was removed from the dataset due to the presence of a significant amount of missing data. Specifically, approximately two-thirds of the entries in the "HDI for year" column were missing. </li>
<li>	The data for the year 2016 was removed from the dataset. This decision was made because only a few countries had any data available for that particular year, and even among those countries, there were significant missing values in the data. </li>
</ul>

## Challenges and Limitations
<ul>
<li> The challenge lies in the complexity of the problem and the multiple variables involved. Suicide rates are influenced by a combination of socio-economic, cultural, and psychological factors, making it a multi-dimensional issue.</li>
<li> The dataset does not include comprehensive data from all countries, potentially limiting the generalizability of the findings.</li>
<li> The analysis primarily focuses on descriptive statistics and visualizations, with limited exploration of causal relationships or in-depth statistical modeling.</li>
<li> The dataset may lack certain relevant variables that could provide additional context for understanding suicide rates.</li>
</ul>

## Key findings:
<ul>
  <li> Suicide rates vary significantly across countries, with some countries experiencing higher rates than others. Russia has the highest suicide rate among the selected countries, accounting for a significant proportion of the total suicides. Also, Eastern European countries, such as Ukraine and Poland, are also represented in the top 10, indicating a relatively higher suicide rate in this region.</li>
  <li> There are notable differences in suicide rates across different time periods, suggesting temporal trends and potential factors influencing suicide rates. Based on the analysis, the period between 1997 and 2004 stands out as the period with the highest peak in suicide rates per 100,000 population. And, there is a noticeable decreasing trend in suicide rates after the year 2009. </li>
  <li> Age and gender play a significant role in suicide rates, with distinct patterns observed across different age groups and between males and females. The age group of 35-54 years shows the highest number of suicide rates over time.</li> 
  <li> Males generally have higher suicide rates compared to females. </li>
  <li> Economic factors, such as GDP per capita, have been explored in relation to suicide rates, indicating a potential correlation. There appears to be a negative correlation between GDP per capita and suicide rates. As GDP per capita increases, the total number of suicides generally decreases.</li>
</ul>
