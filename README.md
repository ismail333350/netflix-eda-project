# 🎬 Netflix Data Analysis Project

This project explores the **Netflix dataset** using Python to uncover patterns, insights, and trends about Netflix's catalog — including genres, countries, and content type distributions.

---

## 📁 Project Overview

The main goal of this analysis is to:
- Clean and preprocess Netflix data for accurate analysis
- Perform exploratory data analysis (EDA) to understand content trends
- Visualize insights using Python’s data visualization libraries

---

## 🧹 Data Cleaning

Key steps performed:
- Filled missing values in important columns (`director`, `cast`, `country`, `rating`, etc.)
- Removed duplicates to ensure data integrity
- Standardized date and text formats
- Handled nulls in categorical fields by replacing them with `"Unknown"` or `"Not Available"`

---

## 📊 Exploratory Data Analysis (EDA)

The EDA focuses on answering key business questions such as:
1. **Movies vs TV Shows** – Which type dominates Netflix’s catalog?
2. **Content Over Time** – How has Netflix’s content library grown by year?
3. **Genre Insights** – What are the most common genres on Netflix?
4. **Country Analysis** – Which countries produce the most Netflix titles?
5. **Creator Insights** – Which directors and actors appear most frequently?

---

## 📈 Visualizations

The notebook includes:
- Line plots showing content growth over the years  
- Bar charts for top genres and countries  
- Heatmaps and pie charts for categorical comparisons  
- Seaborn-styled visualizations for clean and modern visuals  

---

## 🧰 Tools and Libraries

- **Python 3.x**
- **Pandas** – Data cleaning and manipulation  
- **Matplotlib & Seaborn** – Visualization and styling  
- **NumPy** – Numerical operations  
- **Jupyter Notebook** – Interactive exploration  

---

## 💡 Key Insights

- Netflix’s catalog is dominated by **Movies**, but **TV Shows** have increased sharply in recent years.  
- **Drama, Comedy, and Documentary** are the top genres globally.  
- The **United States and India** contribute the largest number of titles.  
- **Director Rajiv Chilaka** is one of the most frequent creators on the platform.  

---

## 📎 File Description

| File | Description |
|------|--------------|
| `analysis.ipynb` | Main notebook containing cleaning, EDA, and visualizations |
| `netflix_titles.csv` | Original dataset (not included if large) |
| `README.md` | Project documentation (this file) |


