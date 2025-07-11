# Marketing-Campaign-Analysis

## Project Background
The marketing agency involved in this analysis aims to maximize ROI for its clients' ad campaigns. In 2019, two separate advertising campaigns were conducted on Facebook and AdWords. This analysis was undertaken to determine which platform delivers better results in terms of key performance indicators, including ad clicks, conversions, and overall cost-effectiveness. By uncovering these insights, the agency can better allocate its budget and optimize future marketing strategies for its clients.

## Data Overview
The dataset contains 365 records corresponding to each day in 2019. Key features include:
- Date: The date of data collection.
- Facebook Ad Campaign: Information on clicks, conversions, and ad costs for Facebook.
- AdWords Ad Campaign: Similar data for the AdWords platform.
  
Key tables in the dataset:
- Facebook Ad Campaign
- AdWords Ad Campaign

Before conducting the analysis, the dataset underwent quality checks to ensure completeness and consistency.

# Executive Summary 

## Overview of Findings
Facebook Ads outperform AdWords: The average number of conversions from Facebook ads is significantly higher than that of AdWords, with a mean conversion rate of 11.74 compared to 5.98 for AdWords.
Conversion Frequency: Facebook ads show more frequent high-conversion days, while AdWords experiences either low or moderate conversion rates, with notable gaps in conversion numbers.
Correlation between Clicks and Sales: A strong positive correlation (0.87) was found between Facebook ad clicks and sales, indicating that more Facebook ad clicks directly translate into more sales. For AdWords, the correlation was moderate (0.45), suggesting that other factors influence its sales effectiveness.
Cost-Effectiveness (CPC Trends): Advertising costs fluctuate over the year. Notably, May and November show the lowest cost-per-conversion, suggesting more cost-effective periods, while February experiences the highest CPC, warranting a review of ad strategy during that month.
Hypothesis Testing: The hypothesis that Facebook ads generate more conversions than AdWords was strongly supported by statistical analysis, with a T-statistic of 32.88 and a p-value of 9.35e-134.
Predictive Modeling: The linear regression model demonstrates strong predictive power for Facebook conversions, with an R2 score of 76.35%, helping businesses forecast future conversion outcomes based on ad clicks.

## Main Insights:
Facebook Ads Are Highly Effective: With a strong correlation between clicks and conversions, businesses should consider increasing their investment in Facebook advertising to drive more sales.
AdWords Optimization Needed: While AdWords contributes to conversions, its effectiveness is more limited. A deeper analysis of campaign strategies is recommended.
Budget Allocation: To maximize ROI, allocate more budget to months with historically lower CPC values, like May and November, and optimize campaigns during periods of high CPC, such as February.
Weekday Focus: Concentrate ad spend and efforts on Mondays and Tuesdays, consistently showing higher conversion rates.

# Insights Deep Dive

## Ad Clicks Analysis:

All histograms related to clicks and conversions show somewhat symmetrical distributions, indicating relatively even distribution of these metrics.












