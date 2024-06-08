# Twitter Analysis
![](tweet_welcome_page.PNG)


## Introduction
The purpose of this project is to demonstrate the power of storytelling through knowledge rendering analysis and visualization.
This analysis unveils hidden insights surrounding the 30 days learning activity that took place on twitter platform.


### The report consists of 4 pages
1. Welcome page
2. Summary
3. Details
4. dashboard

You can interact with the dashboard [here](https://app.powerbi.com/groups/me/reports/3cbe3a9e-4547-4408-9882-8734c1154848/ReportSection?experience=power-bi)


## Skills Demonstrated
1. Data Cleaning and Transformation
2. Quick Measures
3. Relationship Modeling
4. Data Visualization
5. Filters and Tooltips
6. Page Navigation


## Problem Statement
This project is set to analyze and visualize tweets, top handles, devices, tools, and word clouds to uncover patterns in each of these categories.


## Data Sourcing
Scraped data was extracted from Github and imported into Power Query Editor for cleaning and transformation

## Data Cleaning & Transformation
Power Bi Power Query Editor was used for cleaning and transformation. There were no blanks and errors, however, I transformed the date column using split by delimiter. I renamed the added column and changed type to reflect data accurately.

### Cleaned Data
![](twitter_cleaned_data.PNG)

Data was loaded into power Bi and two extra tables were created as "Date table" and "Popular users."

### Additional Tables
Data table                                    |                                Popular Users
:---------------------------------------------|--------------------------------------------:
![](date_measure.PNG)                         |               ![](popular_users_measure.PNG)

A many to one relationship was established between the tables trough modeling process.

### Modeled Tables
![]()







