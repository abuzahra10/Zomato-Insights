# Restaurant Data Analysis Project

This project involves exploratory data analysis (EDA) on a restaurant dataset to answer specific business and consumer behavior questions. It focuses on how different restaurant features influence customer ratings, votes, and average costs across different cities and cuisines.

## 📊 Project Objectives

- Clean and preprocess raw restaurant data.
- Investigate the effect of restaurant features (e.g., online order, book table) on customer engagement metrics.
- Analyze how pricing differs between specialized and fusion restaurants across cities.
- Explore cuisine diversity and its relationship to restaurant ratings and pricing.

## 🧪 Research Questions

1. **What is the relationship between restaurant features (online_order, book_table) and customer ratings/votes?**
   - Restaurants with table booking receive significantly higher votes than those without.
   - Online ordering has a less pronounced impact on votes.

2. **How does the average cost (for two people) differ between specialized and fusion restaurants?**
   - Analysis includes city-wise comparisons and cost trends.

3. **What is the effect of cuisine diversity on restaurant popularity and pricing?**
   - Focuses on single vs. multi-cuisine restaurants.

## 🧼 Data Cleaning

- Removed missing values and duplicates.
- Normalized text features (e.g., restaurant names, cuisines).
- Converted currency and pricing fields to numerical formats.

## 🔍 Tools & Libraries Used

- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib & Seaborn** – data visualization
- **Plotly** – interactive plots

## 📁 Project Structure

```bash
├── DE_PROJECT.ipynb       # Main analysis notebook
├── data/                  # Directory for raw and cleaned data files (not included here)
├── README.md              # Project overview and documentation
