Social Media Ad Campaign Analytics Dashboard
Overview

An Excel dashboard analyzing 16,000+ social media advertising campaigns across Facebook, Instagram, Twitter, and Pinterest. Built as a portfolio project during the Atomcamp Data Analytics Bootcamp.

Objective

Analyze campaign performance across platforms using historical data and surface actionable insights to optimize future campaign strategy — covering reach, cost, engagement, and audience targeting.

Data
16,000+ rows, 19 columns
Fields: Campaign ID, Date, Gender, Age Group, Campaign Goal, Duration, Channel Used, Customer Segment, Language, Company, Location, Conversion Rate, Acquisition Cost, ROI, Clicks, Impressions, Engagement Score
Data Cleaning
Removed duplicate rows
Split Target Audience into separate Gender and Age Group columns
Removed stray symbols from Campaign Goal values
Standardized Duration to a clean numeric (days) field
Removed newline characters from the ROI column
Added a calculated Net Profit column (ROI × Acquisition Cost)
Added a calculated Clicks per Day column (Clicks ÷ Duration)
Dashboard Features
Slicers for Location, Channel Used, Campaign Goal, and Customer Segment
Timeline filter for Date
Pivot tables and charts covering:
Campaign goal with highest/lowest engagement scores
Average clicks per month by target audience
Acquisition cost by campaign goal, for the full year
Campaign count by age group, split by gender
Distribution of acquisition cost by location

Key Insights
Increase Sales campaigns generated the highest total engagement score of the four goals, while Product Launch campaigns generated the lowest — a gap worth factoring into future goal-setting for campaigns aiming to build engagement.
Acquisition cost by location is fairly evenly spread across the five cities in the dataset, with Las Vegas running highest and Los Angeles lowest — no single location is a major cost outlier.
Campaign targeting by gender is close to balanced overall (roughly 6,700 campaigns aimed at men vs. 6,600 at women), with the 25–34 age group the most heavily targeted segment for men and 18–24 the most targeted for women.

Tools Used

Microsoft Excel — Pivot Tables, Power Query, Slicers, Timeline, Charts

File

Social_Media_Marketing_Dashboard.xlsx — open in Excel to interact with slicers and filters (GitHub's preview won't render them).

Screenshots
<img width="533" height="317" alt="dashboard (screenshot png)" src="https://github.com/user-attachments/assets/73da8f58-6836-41f4-aa64-79e6b08b27c2" />

(Add dashboard screenshots here once uploaded — ![dashboard](screenshot.png))
