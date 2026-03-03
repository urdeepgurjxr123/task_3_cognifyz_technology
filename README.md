# 📍 Location-Based Restaurant Analysis  
### Cognifyz Technologies – Machine Learning Internship (Task 4)

---

## 📌 Project Overview

This project performs a **Location-Based Analysis** of restaurants using geographical and statistical techniques.  
The objective is to analyze restaurant distribution, ratings, cuisine trends, and price segmentation based on location data.

---

## 🎯 Objective

- Analyze restaurant distribution using Latitude & Longitude
- Identify city-wise restaurant concentration
- Calculate average ratings by city
- Analyze price range distribution
- Identify popular cuisines
- Discover geographic patterns and insights

---

## 📂 Dataset Information

- Total Records: **9551**
- Total Columns: **21**
- Key Columns Used:
  - City
  - Locality
  - Latitude
  - Longitude
  - Aggregate rating
  - Cuisines
  - Price range

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 🔎 Step-by-Step Implementation

---

## ✅ Step 1: Import Required Libraries

Imported Pandas for data handling and Matplotlib/Seaborn for visualization.

---

## ✅ Step 2: Load Dataset

Loaded the CSV dataset into a Pandas DataFrame and verified the shape and previewed the data.

---

## ✅ Step 3: Data Cleaning

Removed missing values using `dropna()` to ensure clean and reliable analysis.

---

## ✅ Step 4: Select Relevant Columns

Selected only location and rating related columns for focused analysis:
- City
- Locality
- Latitude
- Longitude
- Aggregate rating
- Cuisines
- Price range

---

## ✅ Step 5: City-wise Restaurant Count

Calculated the number of restaurants per city using `value_counts()` and visualized the Top 10 cities using a bar chart.

**Insight:** Metro cities show higher restaurant concentration.

---

## ✅ Step 6: Average Rating by City

Grouped the dataset by city and calculated the mean aggregate rating.

**Insight:** Some cities have fewer restaurants but higher average ratings.

---

## ✅ Step 7: Price Range Distribution

Used count plots to analyze the distribution of different price ranges.

**Insight:** Mid-range restaurants dominate the dataset.

---

## ✅ Step 8: Cuisine Distribution

Identified the Top 10 most common cuisines using value counts and visualized them.

**Insight:** Popular cuisines are concentrated in major cities.

---

## ✅ Step 9: Rating vs Price Analysis

Analyzed average rating across different price ranges.

**Insight:** Mid-range restaurants often maintain better ratings compared to premium segments.

---

## ✅ Step 10: Geographical Distribution (Scatter Plot)

Plotted Latitude vs Longitude using a scatter plot to visualize restaurant spread.

**Insight:** Restaurants are geographically clustered in high-density urban areas.

---

# 📊 Key Insights

- High population cities have higher restaurant density.
- Restaurant quality does not always correlate with quantity.
- Mid-range restaurants tend to receive strong customer ratings.
- Cuisine popularity varies by region.
- Restaurants are clustered around commercial and urban zones.

---

# 📌 Conclusion

This project successfully performed a location-based restaurant analysis using Python.  
The analysis provided meaningful insights into restaurant concentration, pricing patterns, cuisine distribution, and rating trends across different cities.

The findings can help businesses understand market density, customer preferences, and regional demand patterns.

---

# 🚀 Internship Information

Organization: Cognifyz Technologies  
Domain: Machine Learning  
Task: Location-Based Analysis  

---

# 👨‍💻 Author

[Deepak vikal]

