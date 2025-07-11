# Water Access Analysis

### Project Overview

This is a dataset for UNICEF Joint Monitoring Programme (JMP) for Water Supply, Sanitation, and Hygiene. The dataset contains estimates on the use of water in 2020. This data analysis project aims to provide insight on the access to water in different countries by analyzing access to water in different areas (national, urban, and rural), looking at population sizes and different income groups.

### Data Sources

Estimates on the use of water dataset: The primary dataset used for this analysis is the "Estimates_on_the_use_of_water_(2020).csv" file, which contains information about each country.

### Tools

Excel- for data cleaning and analysis




### Data Cleaning/Preparation

In the initial data preparation phase, I perfomed the following tasks:
1. Data loading and inspection
2. Handling incorrectly imported cells and missing values
3. Data cleaning and formatting

   
### Exploratory Data Analysis (EDA) 

EDA involved exploring the sales data to answer the following key questions:

- How does the urban population share compare to the rural population?
- What is the tendency and spread of different water access features?
- What does national, urban, and rural access to water look like?
- What is the effect of national population size and urbanization on Gross National Income (GNI) and water access?
  
### Data Analysis

Used excel functions such as: 
- COUNTA 
- ROUNDUP
- QUARTILE
- ABS
- STDEV

### Findings
Some regions have a high share of basic services (e.g., Liechtenstein, Tokelau), while others like Papua New Guinea have significant portions relying on limited sources.
Over 50% of the global population still has limited access to water
There's a huge gap between rural and urban access. This is where interventions are most urgently needed.

### Limitations
The visualizations could not represent the data very well as some values were larger than others. To deal with these outliers, I changed the unit of x-axis, at least in this way we don’t lose the information in our dataset, although the x-axis did not represent the true difference between population sizes. This was a better option than to completely delete the outliers in which we could have lost some important information in some countries 
