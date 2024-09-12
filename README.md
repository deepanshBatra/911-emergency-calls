# 911-emergency-calls
This project involves performing an Exploratory Data Analysis (EDA) on a dataset of 911 emergency calls. The objective of the analysis is to uncover trends, insights, and patterns in the data, which could help in understanding emergency call behavior and optimizing response strategies.
Dataset Information
The dataset contains records of 911 emergency calls from a specific region, capturing important information such as the time of the call, the reason for the call, and the location of the caller. The data is used to analyze various aspects of emergency calls, such as:

Call frequency over time
Top reasons for 911 calls
Geographical distribution of calls
Seasonal trends
Key Features:
Timestamp: Date and time of the 911 call
Lat & Lng: Latitude and Longitude of the caller's location
Description: Reason or category of the emergency (e.g., EMS, Fire, Traffic)
Zipcode: Zipcode where the call was made
Township: The township where the 911 call was made
Address: Address of the emergency
Category: Broad category of the emergency (derived from the description)
Objective
The goal of this EDA is to:

Visualize the distribution of 911 calls across different regions.
Identify the most common reasons for emergency calls.
Analyze call patterns over time (e.g., time of day, day of the week, month).
Map the geographic distribution of calls using latitude and longitude data.
Examine seasonal or monthly variations in the frequency of calls.
Analysis Steps
Data Preprocessing: Clean the dataset, handle missing values, and format the timestamp for time-based analysis.
Univariate Analysis: Analyze the distribution of individual features like Category, Zipcode, and Township.
Bivariate & Multivariate Analysis: Explore relationships between multiple features, such as how different types of emergencies are distributed geographically.
Time-Series Analysis: Analyze the call volume over different time periods (hourly, daily, monthly) to find temporal patterns.
Geospatial Analysis: Map the locations of calls to observe geographical trends.
Correlation Analysis: Check for any significant correlations between features.
Tools & Libraries
The analysis was performed using the following tools and libraries:

Python: For data manipulation and analysis.
Pandas: For data handling and preprocessing.
Matplotlib & Seaborn: For data visualization and plotting.
Plotly: For interactive geospatial analysis.
Geopandas: For geographical plotting of data points.
NumPy: For numerical computations.
Folium: For creating interactive maps.
Visualizations
This project includes the following visualizations:

Call Distribution by Reason: Bar charts and pie charts showing the most common reasons for 911 calls.
Time-Series Plots: Line plots showing call trends over different time frames (hours, days, months).
Heatmaps: Heatmaps of call volumes by hour and day of the week.
Geospatial Maps: Mapping the locations of emergency calls with latitude and longitude data.
Zipcode/Township Analysis: Distribution of calls by zipcode and township.
Insights
Call Volume Peaks: The majority of calls occur during specific times of the day, typically in the late afternoon and early evening.
Most Common Call Reasons: EMS (Emergency Medical Services) calls represent the highest percentage of emergency calls, followed by traffic accidents.
Geographic Patterns: Certain areas, based on latitude and longitude data, experience a higher volume of calls, often in highly populated regions.
Seasonal Trends: There are noticeable peaks during certain months, possibly due to weather-related emergencies.
Conclusion
The EDA provided valuable insights into the nature and behavior of 911 emergency calls. These findings could help emergency services allocate resources more efficiently and predict peak times for specific types of emergencies.
