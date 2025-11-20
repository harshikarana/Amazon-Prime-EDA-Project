# Amazon-Prime-EDA-Project
Exploratory Data Analysis on Amazon Prime Video dataset
# 🎬 Amazon Prime Video – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on Amazon Prime Video's movies and TV shows dataset (`titles.csv`) combined with cast & crew information (`credits.csv`).  
The goal is to uncover trends, patterns, and actionable insights that help Amazon Prime (or similar OTT platforms) optimize content strategy, audience targeting, and acquisition decisions.

---

## 📁 Dataset Information

### **1. titles.csv**
Contains metadata of movies & TV shows:
- Title name  
- Type (Movie/Show)  
- Description  
- Release year  
- Age certification  
- Runtime  
- Genres  
- Production countries  
- IMDb score & votes  
- TMDB popularity & score  

### **2. credits.csv**
Contains personnel data:
- Person ID  
- Actor/Director name  
- Character  
- Role type  
- Title ID (links to titles.csv)

---

## 🎯 Business Problem

Amazon Prime hosts thousands of titles, but understanding content performance, genre dominance, popularity indicators, and creator influence is crucial.  
This project aims to answer:

1. Which genres dominate Amazon Prime?
2. How content production evolved over the years?
3. What countries contribute the most?
4. Which actors/directors appear most frequently?
5. What patterns exist in IMDb/TMDB scores?
6. What characteristics define popular or high-rated titles?

---

## 🎯 Business Objective

The objective is to analyze Amazon Prime's content catalog to support:
- **Content acquisition strategy**
- **Original content planning**
- **Regional expansion**
- **User engagement improvement**
- **Recommendation system enhancement**

This is accomplished through data cleaning, transformation, advanced visualizations (15+ charts), and insightful storytelling.

---

## 📊 Key Visualizations (15+)

- Movies vs TV Shows  
- Top 10 Genres  
- Release Year Trends  
- IMDb & TMDB Score Distributions  
- Country-wise Content Map (Choropleth)  
- Sunburst Chart (Type → Genre → Country)  
- Top Actors & Directors  
- Runtime vs IMDb Score  
- IMDb Votes vs Popularity  
- Correlation Heatmap  
- Pair Plot  
- Bubble Chart (Votes vs Score vs Popularity)

---

## 🧹 Data Wrangling

Performed:
- Missing value treatment  
- Type conversions  
- List column creation (genres, countries)  
- Duplicate removal  
- Outlier detection (IQR)  
- Feature transformation  

Result: clean, analysis-ready `titles_df` and `credits_df`.

---

## 📈 Key Insights

- Amazon Prime is **movie-dominated**, but TV shows are rising.
- **Drama, Action, Comedy** are top genres.
- USA leads content production; India, UK, and Canada follow.
- IMDb scores mostly fall between **6–8**.
- Content production increased after **2015**.
- Documentaries & Biographies receive the **highest ratings**.
- Strong correlation: IMDb votes ↔ Popularity.

---

## 📝 Recommendations

- Invest more in high-performing genres (Documentary, Biography).
- Expand into fast-growing markets (India, South Korea, Europe).
- Strengthen partnerships with popular actors/directors.
- Improve marketing for highly-rated but low-popularity titles.
- Optimize content acquisition using data-driven genre scoring.

---

## 🎤 Presentation Included

A full **PPT presentation is generated automatically**  
(Accounting: Summary, Problem, Objectives, Insights, Recommendations, Conclusion)

---

## 💻 Tech Stack

- **Python**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn**  
- **Plotly (interactive visuals)**  
- **WordCloud**  
- **Jupyter/Colab Notebook**

---

## 📦 Project Structure ├── Amazon_EDA.ipynb
├── titles.csv
├── credits.csv
├── README.md
└── Amazon_Prime_EDA_Presentation.pptx (exported) . give ready to downlod readme file


