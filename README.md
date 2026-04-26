# Exploratory Data Analysis of Airbnb Listings in New York (2024)

## Project Overview
This project conducts Exploratory Data Analysis (EDA) on Airbnb listings in New York to identify key trends and patterns. It utilizes libraries such as Pandas, NumPy, Matplotlib, and Seaborn for data cleaning, visualization, and analysis.


<img width="1828" height="860" alt="AirBnbImage" src="https://github.com/user-attachments/assets/e949444c-feb4-40d5-ac03-629118bfd371" />

📊 Airbnb NYC EDA Project
🎯 Objective
Analyze Airbnb data to understand prices, room types, and availability
Study host behavior and listing patterns
Identify unusual (outlier) prices
Provide useful insights for guests and hosts


📁 Dataset
Contains 20,765 rows and 22 columns
Key columns:
id – unique listing ID
name – listing title
host_name – host name
neighbourhood_group – location (borough)
latitude / longitude – location coordinates
price – price per night
room_type – type of room
reviews_per_month – average reviews
availability_365 – availability in a year

⚙️ Steps Performed
1. Data Cleaning
Handled missing values
Fixed data types
Removed extreme price values (outliers)
2. Exploratory Data Analysis (EDA)
Room Types
Most listings are Entire home/apartment
Location Analysis
Manhattan has highest prices
Brooklyn comes next
Price Distribution
Most listings fall between $50 – $300
Availability
Listings with higher availability often have more reviews
Hosts
Some hosts manage multiple listings
3. Visualization
Bar charts → room types & locations
Histograms → price distribution
Boxplots → outliers
Heatmaps → correlation between features
Pairplots → relationships between variables
🔍 Key Insights
Manhattan is the most expensive area
Entire homes are costlier than private/shared rooms
Few listings have extremely high prices (outliers)
Budget options are mostly private rooms
Some hosts operate multiple listings (professional hosts)
🧠 Conclusion

This analysis helps understand Airbnb trends in NYC and provides insights for:

Guests → finding affordable stays
Hosts → pricing and listing strategies
