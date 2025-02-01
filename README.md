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

**PowerBi Details**
**Dashboard**
1. I've created two main slides for the dashboard: Dashboard and Dashboard Details.
2. In the Dashboard slide, I have included the counts for total crimes, severe crimes, non-severe crimes, the number of arrests, and the number of non-arrests.
 The dashboard also includes interactive filters, allowing you to explore the data by Year, Crime Type (Primary Type), Location, Arrest Status, Domestic vs. Non-Domestic, and incidents of time Additionally, 
3. by clicking the i icon next to the arrest rate, you'll be taken to the Dashboard Details page for more in-depth crime information. You can easily return to the main dashboard by clicking the back button.
4. On the Dashboard page, I’ve included several visual elements:
    i. A Location Map to show where crimes are happening geographically.
   ii. A Donut Chart to visualize the distribution of crime types.
  iii. A Tree Map to provide detailed crime information.
   iv. A Stacked Bar Chart that displays crime trends across months
5. One of the most valuable features is the Tree Map, which allows us to identify areas with the highest crime rates and highlight the most common crime types in those areas.

**Other pages Details**

1. _Trends Over Time:_
This section displays crime trends in a line chart, broken down by year, month, and day. 

2. _Peak Crime Hours:_
This heatmap shows the number of crimes reported each hour, broken down by day. 

3. _Crime Hotspots:_
This section presents a geographical map of crime locations, helping to identify high-risk areas. 

4. _Distribution of Crime Types: _
This section displays the distribution of crime types across various locations using a horizontal bar chart.

5. _Severity Analysis: _
This section shows the severity of crimes. 
I have created a new column named "Severity" to categorize crimes as either "Severe" or "Non-severe" based on their primary type in DAX. 
From this analysis, the count of theft is high.

6. _Arrest Rates:_
On this page, I have added a donut chart showing the total number of arrests. 
I have also calculated arrest rates across different locations, primary types, and time periods using a grouped chart.

7. _Domestic vs. Non-Domestic: _
I have added a grouped chart to show the count of domestic and non-domestic crimes in each location.

8. _Location Description: _
I have created a stacked bar chart to visualize the distribution of each crime across different locations. 

9. _Seasonal Trends:_
I have included line charts to show crime rates across different times of day, seasons, and periods. 
For the season, I added a new column named "Season" using DAX code. 

**Requirements**
1. pandas
2. sqlalchemy
3. psycopg2
4. Power BI Account
