# Australian Wildfire Data Analysis and Visualization
Wildfire Dataset Analysis and Visualization using Matplotlib, Seaborn, Pandas, Folium, Plotly, and Dash

**Description**

This project analyzes and visualizes wildfire activities in Australia using a historical dataset. By exploring patterns, trends, and creating visualizations, the project aims to gain insights into wildfire behavior across different regions of Australia. The analysis is split into two parts: Part 1 focuses on analyzing wildfire data, and Part 2 involves creating an interactive dashboard for visualizing the findings.

**Dataset**

This dataset includes data on wildfire activities in Australia from 2005 onwards. It provides information on estimated fire areas, fire brightness, radiative power, and more, categorized by region and date.

Variables:
- Region: The seven regions affected by wildfires.
- Date: Dates in UTC, providing data for 24 hours ahead.
- Estimated_fire_area: Daily sum of estimated fire area for presumed vegetation fires with a confidence > 75% (in km²).
- Mean_estimated_fire_brightness: Daily mean of estimated fire brightness for presumed vegetation fires with a confidence > 75% (in Kelvin).
- Mean_estimated_fire_radiative_power: Daily mean of estimated radiative power for presumed vegetation fires with a confidence > 75% (in megawatts).
- Mean_confidence: Daily mean confidence for presumed vegetation fires with a confidence > 75%.
- Std_confidence: Standard deviation of estimated fire radiative power (in megawatts).
- Var_confidence: Variance of estimated fire radiative power (in megawatts).
- Count: Daily number of pixels for presumed vegetation fires with a confidence level > 75% for a given region.
- Replaced: Indicates with a "Y" if the data has been replaced with standard quality data (usually with a 2-3 month lag).

**Project Tasks completed:**
- Part 1: Analyzing Wildfire Activities in Australia
- Task 1.1: Plot a line chart showing the change in average estimated fire area over time.
- Task 1.2: Plot the estimated fire area over the months to identify seasonal patterns.
- Finding: The plot shows a significant peak in fire activity between 2010 to 2013, with a notable rise in fire area after April 2011 and before 2012, correlating with a period of intense wildfires in Australia.
- Task 1.3: Create a bar plot displaying the distribution of mean estimated fire brightness across different regions.
- Task 1.4: Develop a pie chart showing the portion of pixel counts for presumed vegetation fires across regions.
- Task 1.5: Customize the pie plot for better visual representation.
- Task 1.6: Develop a histogram of mean estimated fire brightness to observe the distribution.
- Task 1.7: Create a scatter plot to show the distribution of estimated fire brightness across regions, using the region as a hue.
- Task 1.8: Develop a scatter plot to show the correlation between mean estimated fire radiative power and mean confidence level.
- Task 1.9: Mark all seven regions affected by wildfires on a map of Australia using Folium.
- Part 2: Dashboard for Interactive Visualization
- Task 2.1: Add a title to the dashboard.
- Task 2.2: Add radio items and a dropdown menu for region and year selection.
- Task 2.3: Create two empty divisions for output within the dashboard.
- Task 2.4: Link the output and input components inside the app.callback decorator.
- Task 2.5: Implement the callback function to update the visualizations based on user selections.

**Dashboard Functionality:**

The dashboard allows users to select a specific region and year to dynamically update the visualizations.
- Visualization 1: A pie chart displaying the monthly average estimated fire area for the selected region and year.
- Visualization 2: A bar chart showing the average count of pixels for presumed vegetation fires across months for the selected region and year.
This interactive dashboard provides an intuitive way to explore wildfire data across different regions and years, enabling users to gain deeper insights into seasonal and regional wildfire patterns.

**Findings**
- Seasonal Trends: The peak wildfire activities were observed between 2010 and 2013, with a notable rise in fire area after April 2011, aligning with historical records of severe wildfires in Australia during this period.
- Regional Differences: The distribution of fire brightness and pixel counts varied significantly across regions, highlighting regional vulnerability.
- Correlation Insights: There is a noticeable correlation between fire radiative power and confidence levels, suggesting that areas with higher radiative power are more likely to be accurately detected.

**Requirements**

Python 3.6+
Pandas
Matplotlib
Seaborn
Folium
Dash
Plotly
