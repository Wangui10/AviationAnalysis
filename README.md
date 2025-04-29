# AVIATION SAFETY ANALYSIS

## BUSINESS OVERVIEW

In this project, we analyze historical aviation accident data from the National Transportation Safety Board (NTSB) to extract meaningful insights and actionable business recommendations aimed at reducing aircraft risk and improving overall safety. You can access the data from; [kaggle](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)

## PROJECT GOAL
To indentify which aircraft categories for example ;commercial,private have lower injury severity.
To provide clear recommendations for the initial aircraft purchase decisions.

## BUSINESS UNDERSTANDING
The Project aims to:
- Minimize investment risk when expanding into aviation.
- Select aircraft that are reliable, safe, and cost-effective.
- Optimize long-term operational costs by reducing the likelihood of accidents, failures, or unexpected maintenance


# DATA UNDERSTANDING AND ANALYSIS
  ## Checking for missing values,replacing missing values and dropping missing values
 - The data appears to have a large number of missing values especially in the latitude,longitude,air carrier,schedule and publication date just to mention a few.
 - Therefore, for the categorical columns eg; weather condition the values were replaced with "unknown" 
 - For the numerical category the values were replaced by "0".
 - Some columns were replaced by the median eg; number of engines.
 - Opted to drop columns with massive missing numbers after concluding that the action will not affect my analysis outcome eg; latitude,longitude,schedule,air carrier and FAR columns.
 - After completion we had no missing values. This is helpful when manipulating the data now.

 ## Checking for outliers
 The other step is checking for outliers in the numerical category. Opted to cap the outliers by implementing the IQR formula (Inter-quantile range). This helps to reduce the influence of extreme values without completely removing the data points.



 # INTERACTIVE DASHBOARD
Here are some of the visualizations in relation to the dataset.This dashboard provides insights revolving around injury severity to aircraft category,accident number per year and the broad phase of flight to aircraft damage trends enabling users to interact with the data.


https://public.tableau.com/views/Phase1Project_17459212446410/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


 # CONTACT
 For any queries or feedback,reach out to lilianwangui266@gmail.com.
