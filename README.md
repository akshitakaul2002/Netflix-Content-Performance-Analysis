# 📊 Netflix Content Performance & Audience Engagement Analysis

## 🔎 Executive Summary

This project performs structured exploratory analysis on Netflix movie data to evaluate genre dominance, audience engagement patterns, rating distribution, and overall content performance.

The objective is to extract business-relevant insights that support strategic content evaluation and decision-making.

---

## 🎯 Business Objective

Streaming platforms invest heavily in content creation. To optimize performance, it is important to understand:

- Which genres dominate the catalog?
- How audience ratings are distributed?
- Whether high-quality content achieves strong engagement?
- How production volume has evolved over time?
- Which titles demonstrate balanced performance?

---

## 📁 Dataset Overview

The dataset contains movie-level features including:

- `genre`
- `vote_average`
- `vote_count`
- `popularity`
- `release_date`

---

## 🧹 Data Preparation

The dataset was prepared through:

- Column standardization  
- Datetime conversion and year extraction  
- Missing value handling (median imputation)  
- Duplicate removal  
- Genre normalization using `explode()`  
- Rating categorization  
- Composite metric creation  

---

## 📊 Analytical Approach

1. Genre Distribution Analysis  
2. Rating Category Distribution  
3. Genre-wise Average Rating  
4. High-Rated but Low-Popularity Detection  
5. Production Trend Analysis  
6. Composite Performance Score Development  

---

## 📈 Key Insights

- Content is concentrated within dominant genres.  
- Most movies fall within moderate rating ranges.  
- Some high-rated movies show lower popularity, indicating engagement gaps.  
- Production trends reveal expansion phases.  
- A composite metric improves performance evaluation reliability.  

---

## 🛠 Tools Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 👩‍💻 Author

Akshita Kaul  
BSc Data Science  
