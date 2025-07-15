# NY-Airbnb-Data-Analysis-Visualization

# 🏨 NYC Airbnb Data Analysis & Visualization

This project explores and visualizes Airbnb listings data from New York City. It provides insights into pricing patterns, availability, neighborhood popularity, and the relationship between room types and prices using Python and popular data visualization libraries.

---

## 📌 Objective

To analyze Airbnb listings in NYC to understand:
- Price distributions across room types and boroughs
- Availability patterns
- Host activity levels
- Neighborhood popularity
- Key correlations between variables

---

## 📁 Dataset

- **File:** `AB_NYC_2019.csv`
- **Rows:** 48,895
- **Columns:** 16
- **Fields include:**  
  `id`, `name`, `host_id`, `neighbourhood_group`, `neighbourhood`, `latitude`, `longitude`, `room_type`, `price`, `minimum_nights`, `number_of_reviews`, `reviews_per_month`, `availability_365`, etc.

---

## 🔍 Exploratory Data Analysis

Key steps:
- Loaded and cleaned dataset (handled nulls, removed IDs)
- Explored distributions, outliers, and summary statistics
- Visualized:
  - Price distribution
  - Room type frequency
  - Neighbourhood popularity
  - Price vs availability
  - Correlation heatmaps
  - Room type pricing across boroughs

---

## 📊 Visualizations

| Chart Type | Description |
|------------|-------------|
| 📈 Histogram | Price distribution of listings |
| 📊 Bar Charts | Room type & neighborhood frequency |
| 🥧 Pie Chart | Share of total price by neighborhood |
| 🧲 Correlation Heatmap | Relationship between numeric variables |
| 🎯 Strip/Point/Joint Plots | Price comparisons by borough & room type |
| 📍 Scatter Plot | Price vs. availability, price vs. reviews |

---

## 📌 Insights

- **Manhattan** has the highest average listing price.
- **Private rooms** dominate the listings, especially in **Brooklyn**.
- Price varies significantly by **neighbourhood group** and **room type**.
- A few listings have extreme prices ($10000+), requiring outlier treatment.
- Most listings are available year-round (365 days).

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Jupyter Notebook**

---

## 🧠 Learnings

- Hands-on EDA techniques
- Visual storytelling using Seaborn & Matplotlib
- Data cleaning & preprocessing best practices
- Identifying outliers and handling missing data
- Exploring multivariate relationships in business datasets

