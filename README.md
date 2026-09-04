Divvy Bike-Share Analysis

Project Overview

This project analyzes Divvy bike-share trip data to understand differences in riding behavior between annual members and casual riders.

The analysis uses Divvy trip data from Q1 2019 and Q1 2020 to identify patterns in ride duration, usage by day of the week, and differences between member and casual riders.

The goal of the analysis is to generate actionable insights that can help a bike-share organization better understand its rider segments and inform marketing and customer-conversion strategies.

Business Task

Analyze how annual members and casual riders use the Divvy bike-share service differently, with a focus on ride duration and usage patterns.

Business Questions

1. How does ride length differ between members and casual riders?
2. Which days of the week are most popular for each rider type?
3. What patterns can help the organization better understand casual riders and encourage membership?

Dataset

The analysis combines Divvy bike-share trip data from:

- Q1 2019
- Q1 2020

The data includes trip information such as rider type, trip duration, and trip start/end timestamps.

The dataset was cleaned and transformed before analysis to ensure that invalid and negative trip durations did not affect the results.

Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab / Jupyter Notebook

Data Preparation

The analysis included:

- Combining the Q1 2019 and Q1 2020 datasets.
- Standardizing rider-type labels into Member and Casual.
- Creating date, month, year, and day-of-week variables.
- Calculating ride length from trip-duration data.
- Removing invalid and negative ride durations.
- Checking the data for outliers and data-quality issues.
- Comparing riding behavior between member and casual riders.

Key Findings

1. Casual Riders Have Longer Average Ride Durations

After data cleaning, the analysis showed a substantial difference in average ride duration:

Rider Type| Average Ride Length
Member| 795.25 seconds
Casual| 5,372.78 seconds

Casual riders had substantially longer average rides than members, suggesting that their usage patterns are different from those of regular members.

2. Members Ride More Frequently During the Week

Member riding activity was particularly concentrated around Tuesday, reflecting a stronger weekday usage pattern.

3. Casual Riders Are More Active on Weekends

Casual riders showed stronger activity on Saturday and Sunday, indicating that their bike-share usage is more associated with weekend and recreational riding.

4. Rider Type Is an Important Behavioral Segment

The differences in ride duration and day-of-week usage suggest that members and casual riders represent distinct user groups with different patterns of bike-share usage.

Business Recommendations

Based on the findings, the organization could consider:

1. Targeting casual riders with membership promotions that emphasize the benefits of becoming an annual member.
2. Using weekend marketing campaigns to reach casual riders when their usage is strongest.
3. Highlighting membership value for frequent or longer-duration riders, since casual riders demonstrated substantially longer average ride durations.
4. Using weekday-focused messaging for existing members to support continued engagement.

Conclusion

The analysis demonstrates clear behavioral differences between Divvy members and casual riders.

Members showed stronger weekday usage patterns, while casual riders were more active on weekends and had substantially longer average ride durations. These differences provide useful insights for developing targeted membership and engagement strategies.

This project demonstrates practical skills in data cleaning, data transformation, exploratory data analysis, Python programming, statistical summarization, and data-driven business recommendations.

Project File

- "Divvy_Bike-Share_Analysis.ipynb" — Complete analysis and documentation

Disclaimer

This project is an independent analysis conducted for portfolio purposes using publicly available Divvy bike-share data
