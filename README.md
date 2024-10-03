# Cyclistic Bike-Share Data Analysis Project

## Overview

This project focuses on analyzing the usage patterns of casual riders versus annual members of **Cyclistic**, a bike-share program in Chicago. The goal is to provide insights that will inform marketing strategies to convert casual riders into annual members.

## Project Description

**Cyclistic** operates a bike-share program with a fleet of over **5,800 bicycles** and **600 docking stations** across Chicago. The primary goal of this project is to understand how casual riders and annual members use the bike-sharing service differently.

### Key Objectives

- Analyze trends in bike usage for casual riders and annual members.
- Provide data-driven insights and visualizations to support marketing strategy recommendations aimed at increasing annual memberships.

### Data Sources

The analysis uses **Cyclistic’s Historical Trip Data**, which spans:

- The previous **12 months** (January 1, 2023, to December 31, 2023).
- A total of **12 CSV files**, each containing one month's data.

## Data Preparation

### Data Structure and Organization

- The data is structured and organized into individual CSV files.
- Each dataset contains fields such as `ride_id`, `rideable_type`, `started_at`, `ended_at`, `member_casual`, `ride_length`, `day_of_week`, and `weekday`.

### Data Reliability

- The data is sourced from a real bike-sharing company in Chicago and is deemed **Reliable, Original, Current, and Cited** (ROCCC).
- Some limitations include the lack of financial data and personally identifiable information (PII) due to data privacy regulations.

## Analysis Process

The analysis follows the steps of the data analysis process: **ask, prepare, process, analyze, share, and act**.

### Key Questions

- **How do annual members and casual riders use Cyclistic bikes differently?**

### Key Findings

1. **Average Duration of Rides by Rider Type**
   - Casual riders have longer average ride durations, peaking on weekends.
   - Members maintain consistent average ride durations throughout the week.

2. **Number of Rides by Weekday**
   - Rides peak on **Saturday**, with the lowest ridership on **Sunday**.

3. **Average Ride Length by Weekday**
   - Average ride lengths increase on weekends, while remaining shorter during weekdays.

## Conclusions

- Casual riders tend to take longer trips for leisure, particularly on weekends.
- Members utilize bikes for shorter, consistent trips, likely for commuting purposes.

## Recommendations

1. **Target Casual Riders with Weekend Promotions**: Offer special discounts to encourage weekend usage.
2. **Introduce Membership Options for Recreational Riders**: Create a membership tier for leisure cyclists with specific benefits.
3. **Optimize Bike Availability on Weekdays**: Ensure bike availability near commuter hubs during peak hours.
4. **Promote Off-Peak Hours for Member Riders**: Provide rewards for trips taken during non-peak hours.
5. **Expand Services on Saturdays**: Increase bike availability and maintenance support on Saturdays.
6. **Leverage Ride Data for Targeted Marketing**: Use data to create personalized promotions for both casual riders and existing members.

## Files and Directories

- `data/` - Contains the monthly CSV files used for analysis.
- `notebooks/` - Contains Jupyter notebooks with the analysis code.
- `visualizations/` - Contains visualizations generated from the analysis.

## Getting Started

To run the analysis:

1. Clone the repository:
   ```bash
   git clone [repository_url]
