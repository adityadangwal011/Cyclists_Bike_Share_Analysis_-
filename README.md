# Cyclistic Bike-Share Data Analysis

**Overview**

This project is part of my Capstone project for the Cyclistic Case Study. The primary goal of this analysis is to understand how annual members and casual riders use Cyclistic bikes differently. The findings from this analysis will provide actionable insights to improve business decisions and user experience.

**Business Task**

The main business question this analysis seeks to answer is: How do annual members and casual riders use Cyclistic bikes differently?

**Project Structure**

Data: Contains the raw and cleaned datasets used in the analysis..

Reports: Contains the final analysis report, key findings, and recommendations.

Scripts: R scripts for data cleaning, analysis, and visualization.

README.md: Overview of the project and instructions for running the analysis.

**Data Sources**

The data used in this analysis comes from Cyclistic’s public bike-share dataset, which includes rider behavior over a 12-month period. Each dataset contains the following key variables:

Ride ID
Rideable Type
Start and End Time
Start and End Station
Member Type (Casual or Annual)
Ride Duration

**Tools Used**

R: Used for data analysis and visualization.
RStudio: Integrated development environment (IDE) for R.
RMarkdown (Rmd): For creating reproducible reports that include code, analysis, and visualizations.

**Final Conclusion**

The analysis of Cyclistic bike-share data has provided valuable insights into the usage patterns of casual riders versus annual members. Key observations include:

Casual riders prefer longer rides and are more active during weekends and summer months. Their usage of classic and electric bikes is balanced, with increased electric bike usage during warmer weather.

Annual members show consistent usage throughout the week, especially on weekdays. They tend to favor classic bikes significantly more than electric bikes, suggesting a preference for cost-effective, reliable commuting options.

Seasonal trends show that both casual and annual riders experience a decrease in ridership during colder months, with peaks during summer.

**Recommendations**

Based on these insights, the following recommendations are proposed:

Increase Promotion of Electric Bikes: Encourage more electric bike usage, particularly among annual members, by offering promotions or incentives that highlight the benefits of electric bikes for both short and long trips.

Targeted Marketing Campaigns: Design marketing campaigns aimed at casual riders, with a focus on weekend and seasonal promotions to capitalize on their higher activity during these periods.

Enhance Member Engagement: Implement loyalty programs or additional perks for annual members to encourage year-round ridership and maintain engagement during off-peak seasons.

Improve Seasonal Strategies: Adjust bike availability and maintenance schedules to align with seasonal trends, ensuring optimal service during peak periods and addressing the drop in ridership during colder months.

**Limitations**

It is important to acknowledge the following limitations in this analysis:

Data Accuracy: The analysis relies on the accuracy of the input data, including ride start and end times and rideable type classifications. Any inconsistencies or inaccuracies in the dataset may affect the results.

Contextual Factors: External factors such as weather conditions, special events, or changes in service availability were not considered, and these may have influenced ridership patterns.

Assumptions in Data Analysis: The conclusions drawn are based on observed patterns and statistical analysis. Assumptions made during data processing, such as the exclusion of certain data points or the classification of ride types, may impact the insights.

Limited Scope: The analysis primarily focuses on ride length, frequency, and rideable type. Other factors, such as trip purpose or rider demographics, were not included and could offer additional insights.

**Feedback and Next Steps**

As this is my first project handling a year’s worth of data, I recognize that there are areas where my conclusions or findings may require further refinement. Specifically:

Data Processing: Certain assumptions were made during data cleaning, especially around parsing date information and handling missing values. Future projects may explore more advanced methods for handling missing or erroneous data to improve accuracy.

Ride Duration: The calculation of ride length excluded negative or unrealistic values. While necessary, this might have skewed the overall results and impacted some insights. Further research could investigate better approaches to deal with outliers and anomalies.

Visualization Choices: The visualizations used in this analysis may not fully capture the complexity of the data. With more experience, I plan to explore different graph types to present trends more clearly and in greater detail.

I welcome any feedback or corrections to help improve my understanding and approach for future projects.
