# 🌦️ Weather Data Analysis

## 📌 Project Overview

This project analyzes weather data using **Python and Pandas** to understand temperature, humidity, visibility, wind speed, and different weather conditions.

The goal of this project is to practice **data cleaning, exploratory data analysis (EDA), data manipulation, and basic data visualization** using a real-world weather dataset.

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

---

## 📂 Dataset

The dataset contains weather observations with information such as:

* Date/Time
* Temperature
* Dew Point Temperature
* Relative Humidity
* Wind Speed
* Visibility
* Atmospheric Pressure
* Weather Condition

---

## 🧹 Data Cleaning

The following cleaning steps were performed:

* Checked for missing values
* Checked for duplicate records
* Converted `Date/Time` into datetime format
* Renamed the `Weather` column to `Weather Condition`
* Created additional columns such as **Month** and **Hour**

---

## 🔍 Analysis Questions

I used Pandas to answer the following questions:

1. Which weather conditions occur most frequently?
2. What is the average temperature?
3. What are the hottest and coldest recorded temperatures?
4. What percentage of observations have visibility below 10 km?
5. What percentage of observations have humidity above 80%?
6. Which weather condition has the highest average temperature?
7. Which weather condition has the lowest average visibility?
8. Which month has the highest average temperature?
9. What is the average temperature for each hour of the day?

---

## 📊 Visualizations

The analysis includes visualizations such as:

* Weather condition frequency
* Temperature distribution
* Average temperature by month
* Average temperature by hour

These visualizations help identify patterns and relationships in the weather data.

---

## 💡 Key Findings

The findings are based on the results obtained during the analysis.

Examples of findings include:

* The most frequently occurring weather condition was **Clear**.
* The average temperature was **[8.7981°C**.
* The highest recorded temperature was **33°C**.
* The month with the highest average temperature was **7**.

---

## 📁 Project Structure

```text
Weather-Data-Analysis/
│
├── Weather Data.csv
├── Weather_Data_Analysis.ipynb
├── README.md
│
└── images/
    ├── weather_distribution.png
    ├── temperature_distribution.png
    ├── monthly_temperature.png
    └── hourly_temperature.png
```

---

## 🎯 What I Learned

Through this project, I practiced:

* Loading datasets using Pandas
* Understanding dataset structure
* Handling missing values
* Working with datetime data
* Filtering and grouping data
* Using aggregation functions such as `mean()`, `max()`, and `min()`
* Creating new columns
* Calculating percentages
* Finding correlations
* Creating basic visualizations
* Communicating data findings

---

## 🚀 Conclusion

This project helped me understand the basic workflow of a **Data Analyst** project, from loading and cleaning raw data to analyzing it, visualizing patterns, and communicating insights.
