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

## 🛠Tools & Libraries
- Python   
- Pandas, NumPy – Data processing  
- Matplotlib, Seaborn – Visualization  
- Scikit-learn – Machine learning (similarity, recommendation)  

---

## 🚀 How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/anime-recommendation.git
   cd anime-recommendation
