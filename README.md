# Exploratory Data Analysis of Airbnb Listings in New York (2024)

## Project Overview
This project conducts Exploratory Data Analysis (EDA) on Airbnb listings in New York to identify key trends and patterns. It utilizes libraries such as Pandas, NumPy, Matplotlib, and Seaborn for data cleaning, visualization, and analysis.


<img width="1828" height="860" alt="AirBnbImage" src="https://github.com/user-attachments/assets/e949444c-feb4-40d5-ac03-629118bfd371" />

# 📊 Airbnb NYC EDA Project

## 🎯 Objective
- Analyze Airbnb data to understand prices, room types, and availability  
- Study host behavior and listing patterns  
- Detect unusual (outlier) prices  
- Provide insights for guests and hosts  

---

## 📁 Dataset
- Total records: 20,765  
- Total features: 22  

### Important Columns:
- id – unique listing ID  
- name – listing title  
- host_name – host name  
- neighbourhood_group – location (borough)  
- latitude / longitude – location coordinates  
- price – price per night  
- room_type – type of room  
- reviews_per_month – average reviews  
- availability_365 – availability in a year  

---

## ⚙️ Steps Performed

### 1. Data Cleaning
- Handled missing values  
- Fixed data types  
- Removed extreme price values  

### 2. Exploratory Data Analysis (EDA)
- Analyzed room types distribution  
- Compared prices across neighborhoods  
- Studied availability trends  
- Checked host listing patterns  

### 3. Data Visualization
- Bar charts for room types and locations  
- Histograms for price distribution  
- Boxplots for outliers  
- Heatmaps for correlation  

---

## 🔍 Key Insights
- Manhattan has the highest prices, followed by Brooklyn
- Entire homes/apartments are more expensive than private/shared rooms
- Most listings are priced between $50 – $300
- Private rooms are budget-friendly options
- Strong positive correlation between number_of_reviews and reviews_per_month
- Listings with more beds tend to have higher prices
- Most features show weak correlation with each other
- Some listings have very high prices (outliers) and were handled
- Listings with higher availability often receive more reviews
- Some hosts manage multiple listings, indicating professional hosting

---

## 🧠 Conclusion
These insights help guests choose better stays and help hosts optimize pricing. 
This project helps understand Airbnb trends in NYC and provides useful insights for better decision-making.
