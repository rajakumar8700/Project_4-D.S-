# 🎥 Anime Recommendation System

This project builds an **Anime Recommendation System** using machine learning and data analysis on the [Anime Dataset](anime.csv).  
It analyzes anime ratings, genres, and user preferences to generate meaningful recommendations.  

---

## Dataset
- **Source:** Anime dataset (`anime.csv`)  
- **Key Columns:**
  - `anime_id`: Unique identifier for each anime  
  - `name`: Title of the anime  
  - `genre`: Anime genres (e.g., Action, Comedy, Drama)  
  - `type`: Format (TV, Movie, OVA, Special)  
  - `episodes`: Number of episodes  
  - `rating`: Average user rating  
  - `members`: Number of community members engaged  
---

## Tools & Libraries

- `pandas` – Data processing and manipulation  
- `numpy` – Numerical operations  
- `matplotlib` – Data visualization  
- `seaborn` – Statistical data visualization  
- `scikit-learn` – Machine learning (cosine similarity, recommendation models)  
- `statistics` – Standard Python library 
- `operator` – Standard Python library  
- `warnings` – Standard Python library  

---

## Methodology
1. **Data Cleaning & Preprocessing**  
   - Handled missing values (e.g., unknown episode counts).  
   - Converted genres into structured features.  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of anime types, ratings, genres, and episodes.  
   - Visualizations to uncover trends.  

3. **Recommendation System**  
   - Built using **Collaborative Filtering** & **Cosine Similarity**.  
   - Recommends anime based on user preferences and similarity scores.  

---

## Key Insights
- **Most common genres:** Action, Comedy, Drama.  
- **Highest average ratings:** Long-running TV anime often maintain popularity.  
- **Episodes trend:** 12–26 episode TV series dominate seasonal releases.  
- **User preferences:** Similar users rate anime alike, making collaborative filtering effective.  

---
## Screenshot
<img width="1420" height="676" alt="image" src="https://github.com/user-attachments/assets/70de63f0-6609-4c1f-9337-c7e0dccfc53f" />

