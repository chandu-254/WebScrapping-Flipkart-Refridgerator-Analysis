# WebScrapping & EDA On-Flipkart-Refridgerator-Analysis
🧊 Flipkart Refrigerator Data Analysis using Web Scraping

📌 Project Overview

This project focuses on extracting refrigerator product data from Flipkart using web scraping techniques and performing Exploratory Data Analysis (EDA) to understand pricing trends, product features, and customer preferences.

The goal of this project is to simulate a real-world data analyst task — collecting raw data from a website, cleaning it, and generating meaningful business insights.

🎯 Objectives

> Scrape refrigerator product data from Flipkart
>Clean and preprocess raw scraped data
>Analyze price patterns and feature trends
>Identify popular brands and configurations
>Visualize insights using charts and graphs

🛠️ Tools & Technologies Used

Python

* BeautifulSoup - for web scraping
* Requests – for sending HTTP requests
* Pandas – for data manipulation
* NumPy – numerical operations
* Matplotlib & Seaborn – data visualization

# Data Set Information
________________________________________________________________________________________________________________________________________________________________________________________________________

The dataset was created by scraping Flipkart and includes the following features:

* Dataset: Refridgerator Dataset
* Source: Flipkart Website
* Rows: 984 rows
* Columns: 6

🔄 Project Workflow

1️⃣ Web Scraping

* Sent requests to Flipkart product pages
* Parsed HTML using BeautifulSoup
* Extracted product details such as brand, price, capacity, ratings, etc.
______________________________________________________________________________________________________________________________________________________________________________________________________

2️⃣ Data Cleaning & Manipulations

* Removed null values
* Converted price,Capacity,Ratings,Stars to numeric format
* Handled missing values using fillna method
________________________________________________________________________________________________________________________________________________________________________________________________________
3️⃣ Exploratory Data Analysis (EDA)
After scraping the data, Exploratory Data Analysis (EDA) was performed at three levels: Univariate, Bivariate, and Multivariate to understand product patterns and market trends.

🔹 1️⃣ Univariate Analysis 
  * Brands Distribution
  * Proportion of Refriderator Doors
  * Total Count of Refridgerator with different doors
    
🔹 2️⃣ Bivariate Analysis (Two Variables)
    Bivariate analysis studies the relationship between two variables.
  * Brands Vs Ratings
  * Realation Between Capacity & Price
  * Ratings Vs Stars of Refriderator
  * Brands Vs Price
    
🔹 3️⃣ Multivariate Analysis (More than Two Variables)
    Multivariate analysis examines multiple features together to get deeper insights
  * Pricing trend across brands and capacity
  * Correlated values between features of refridgerators

______________________________________________________________________________________________________________________________________________________________________________________________________
📊 Key Insights

* Max Price of all the Brands dominate the mid-price segment except samsung,LG,Godrej,Haier
* Higher star ratings generally lead to higher prices
* Single Door & Double-door refrigerators are among the most common
* Larger capacity refrigerators are priced significantly higher
______________________________________________________________________________________________________________________________________________________________________________________________________
💡 Skills Demonstrated

✔ Web Scraping
✔ Data Cleaning
✔ Exploratory Data Analysis
✔ Data Visualization
✔ Real-world data handling
