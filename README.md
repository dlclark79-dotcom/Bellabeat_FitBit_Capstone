# Bellabeat_FitBit_Capstone
Bellabeat Case Study: Optimizing Marketing StrategyA Data Analysis Capstone Project for the Google Data Analytics Professional Certificate.  

## Project Overview  
This project focuses on providing data-driven recommendations to Bellabeat, a high-tech company that manufactures health and wellness smart products for women. 
Using public fitness data, I analyzed key consumer usage trends to advise Bellabeat's marketing strategy and app development, ultimately aiming to increase user engagement and growth.  

## Business Task  
Analyze smart device usage data to identify key trends and translate these findings into three actionable recommendations for how Bellabeat can optimize its marketing and increase user adoption.  

## Key Insight  
The analysis revealed an Activity Gap: While users consistently wear their devices and track sleep, less than 2% of daily tracked activity minutes fall into the Very Active category. 
This gap suggests an opportunity for Bellabeat to market targeted interventions focusing on moderate-to-high intensity activity goals.  

## Tools and Methodology  
This analysis followed the standard data analysis process (Ask, Prepare, Process, Analyze, Share, Act).  

| Phase | Tool/Language | Key Packages | Methodology | 
| --- | --- | --- | --- |
| Preparation & Process | R | Tidyverse (especially dplyr and readr) | Loaded, cleaned, and wrangled daily and hourly activity data. Checked for duplicates, defined active user groups, and aggregated metrics. |
| Analysis & Share | R | ggplot2, lubridate | Segmented users into groups (e.g., Sedentary, Lightly Active, Highly Active). Visualized key relationships, including the correlation between steps/activity and sleep patterns. |
| Reporting | R Markdown | N/A | Generated a comprehensive report detailing methodology and specific business recommendations. |

## Data Source  
The dataset used for this analysis is the publicly available FitBit Fitness Tracker Data (CC0: Public Domain), provided by Mobius and collected via a third-party distributor (Kaggle). 
This dataset includes daily activity, sleep, and weight metrics for 33 unique users.  

## Key Findings and Business Recommendations  
The analysis led to three primary recommendations for Bellabeat's C-suite:  

| Recommendation | Strategy | Supporting Data/Rationale |
| --- | --- | --- |
| 1. Drive High-Intensity Engagement | Implement a Goal-Setting Feature in the Bellabeat app that encourages users to achieve a set amount of Active Zone Minutes (high-intensity activity). | Only 1.7% of daily activity minutes were categorized as Very Active, indicating low engagement in intense exercise despite high device ownership. |
| 2. Prioritize Sleep Health Scores | Focus marketing and in-app messaging on Sleep Quality and Recovery as a key selling point, integrating it with activity advice. | Sleep tracking demonstrated high, consistent user engagement. Bellabeat can leverage this by linking sleep metrics to daily energy levels. |
| 3. Utilize Weekly Tracking Summaries | Send targeted weekly personalized summary emails to reinforce consistency and show progress. | Usage patterns showed that consistency drops off after the initial weeks, indicating a need for nudges to maintain engagement. |

## Visualizations  
! [Activity Levels in Users](Bellabeat Activity.jpeg)
This visualization shows the distribution of users across different activity levels, clearly highlighting the large proportion of Lightly Active and Sedentary users who are ripe for motivation.  
Insight: The goal is to move users from the 'Lightly Active' group into the 'Fairly Active' and 'Very Active' segments through targeted app features.  

## Repository Contents  
- Bellabeat_rmd.Rmd: The complete R Markdown file containing all code for data cleaning, analysis, and visualization.
- Bellabeat_rmd.html: The final generated report detailing the findings and recommendations.
