# Crime Data Analysis and Visualization Project

**Problem Statement**
The increasing complexity and volume of crime data pose challenges for law enforcement agencies and policymakers. This project aims to address these challenges by analyzing a provided dataset of reported crimes in Chicago. By uncovering actionable insights and trends, the project seeks to help law enforcement agencies make informed decisions to allocate resources, predict future crime occurrences, and enhance community safety.

**Introduction**
1. Crime data in Chicago is large and complex.
2. In this project, we want to clean this data and analyze it to find patterns, crime hotspots, and changes in crime over time.
3. This analysis can help law enforcement make better decisions.
4. I worked with crime data to find out where and when crimes happen. I also looked at how arrests are made and how law enforcement can improve. The main idea is to help police and policymakers make better decisions using the data.

**Methods**
Actual Dataset : Crime_Data.csv
This dataset contains 549999 data. In this project I have did below processing
1. Handling Missing Values: 
   Crime data have missing values, errors, or incorrect formats.
2. Cleaning Process:
    1. We filled in missing values with reasonable estimates
    2. Ensured dates, times, and other data were properly formatted.
    3. Fixed short-term in each column.
    4. Example: “CRIM SEX ABUSE BY FAM MEMBER” to “CRIMINAL SEXUAL ABUSE BY
FAMILY MEMBER”
3. Storing Cleaned data in PostgreSQL.
4. Use PostgreSQL to get data in Power BI.
5. Used Exploratory Data Analysis (EDA) to find patterns using Power BI
6. Used Power BI to create visuals for the Interactive Dashboard.
 
**Requirements**
1. pandas
2. sqlalchemy
3. psycopg2
4. Power BI Account
