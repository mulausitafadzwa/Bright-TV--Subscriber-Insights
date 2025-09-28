## Project Overview
This project delivers a comprehensive analysis of BrightTV’s subscriber behavior and content consumption trends, designed to assist the Customer Value Management team in achieving its subscription growth objectives for the financial year. By examining detailed user profile and transaction data, the study identifies key drivers of engagement and uncovers opportunities for targeted content delivery.

## Dataset Used 
- <a href="https://github.com/mulausitafadzwa/Bright-TV--Subscriber-Insights/blob/main/User_Profiles.csv">User Profile</a>
- <a href="https://github.com/mulausitafadzwa/Bright-TV--Subscriber-Insights/blob/main/Viewership.csv">Viewership</a>

## Objectives
- Track overall total revenue and customer count
- Analyze viewership distribution across provinces, age cohorts, gender, and race.
- Weekly consumption patterns to identify high and low engagement periods.
- Identify top-performing channels in terms of viewership engagment .
- Audience segmentation to understand which user groups contribute most to viewership.
  
- <a href="https://github.com/mulausitafadzwa/Bright-TV--Subscriber-Insights/blob/main/BrightTV%20Screenshot.png">Dashboard</a>

## Process 
- Reviewed BrightTV’s business case with the objective of growing the subscription base through insights into user behavior and content consumption patterns.
- Defined key analytical questions around demographics, engagement, and content performance.
- Obtained two datasets: Viewership (session-level consumption data) and User Profile (demographic attributes).
- Conducted data cleaning and transformation within Snowflake SQL, including:
  1. Conversion of timestamps from UTC to South African Standard Time (UTC+2).
  2. Standardization of formats and handling of missing values.
  3. Integration of the two datasets on the UserId key.  
- Applied an analytical framework to explore trends across user demographics, time-of-day patterns, and content categories.
- Segmented users into age cohorts, provinces, genders, and races to compare engagement levels.
- Defined calculated metrics such as daily/weekly viewers, percentage contribution by segment, and time-of-day usage buckets.
- Designed and built an interactive Power BI dashboard to present findings.
- Visuals included:
  1. Demographic distribution of viewership.
  2. weekly consumption trends.
  3. Time-of-day usage segmentation.
  4. Content performance by channel 
- Ensured usability by incorporating clear sorting, labeling, and intuitive navigation.
- Interpreted the results to highlight high-value audience groups and peak engagement times.
- Identified underperforming periods and content segments, recommending targeted strategies to increase consumption.
- Proposed initiatives to expand BrightTV’s user base through data-driven engagement tactics.

## Dashboard

<img width="1153" height="647" alt="BrightTV Screenshot" src="https://github.com/user-attachments/assets/3b47425d-7aab-4e3d-8d5b-d214764b6f57" />

## Key Insights 

## Tools Used 
- Snowflake : For data extraction, cleaning, and coding queries to prepare datasets for analysis.
- Microsoft Word : To document the methodology and outline the analytical approach.
- Power BI : To design and develop the interactive dashboard for visualizing insights.
- DAX (Data Analysis Expressions) : To create calculated measures and advanced metrics within Power BI

## Conclusion
