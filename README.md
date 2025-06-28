# 📱 Google Play Store EDA

This project explores app-related data from the Google Play Store to uncover trends, usage patterns, and factors that impact app ratings, installs, and pricing. Through data cleaning, visualization, and feature analysis, the notebook reveals how app categories, size, type, and user reviews correlate with app performance metrics.

The notebook uses Pandas, Seaborn, and Matplotlib to produce clean visual insights and transformations, helping to understand what makes an app popular or poorly rated.

> 📌 This is a portfolio project for data exploration practice. Please contact me before using or distributing any part of this work.

---

## 🔍 Highlights

- Cleaned and transformed data from the Google Play Store
- Removed duplicates and fixed data types (e.g. `Installs`, `Size`, `Price`)
- Visual analysis of:
  - App categories vs average rating
  - Type (Free vs Paid) vs rating/install patterns
  - Correlation between size, installs, price, and reviews
- Distribution and outlier detection using boxplots and histograms
- Insights:
  - Paid apps have slightly higher ratings but fewer installs
  - Games and productivity apps dominate top installs
  - Review count is positively correlated with rating and installs

---

## 📦 Dataset

- **Name**: `google_clean_data.csv`
- **Rows**: ~9,900 cleaned app records  
- **Columns**: App info, size, installs, price, reviews, type, rating, and more  
- **Source**: Originally scraped from Google Play Store (via Kaggle or similar)

---

## 🧪 Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📁 Repository Structure
