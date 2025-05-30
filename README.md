#  Video Game Sales Analysis

Exploratory data analysis of global video game sales, platforms, genres, and regional patterns. This project helps identify successful game features and informs marketing strategies for upcoming game releases.

---

##  Objective

Analyze historical video game sales data to:

- Identify platform and genre trends
- Evaluate the impact of user and critic reviews on sales
- Compare regional market preferences
- Test hypotheses about average ratings and sales distributions

---

##  Dataset Description

The dataset includes sales and metadata for video games up to 2016:

- `name` — Game title  
- `platform` — Console/platform (e.g., PS4, Xbox One)  
- `year_of_release` — Year released  
- `genre` — Game genre  
- `na_sales`, `eu_sales`, `jp_sales`, `other_sales` — Regional sales (in millions)  
- `critic_score` — Review score from critics (0–100)  
- `user_score` — Review score from users (0–10)  
- `rating` — ESRB rating (e.g., E, T, M)  

---

##  Project Workflow

1. **Data Cleaning & Preprocessing**
   - Rename columns, handle missing values, format data types
   - Address outliers and special cases like "TBD"

2. **Exploratory Data Analysis**
   - Platform lifecycle patterns
   - Global and regional sales by genre and platform
   - Boxplots, distributions, correlation with reviews

3. **Regional User Profiling**
   - Compare top platforms and genres across NA, EU, JP
   - Analyze ESRB impact per region

4. **Hypothesis Testing**
   - Compare user ratings between Xbox One and PC
   - Compare user ratings between Action and Sports genres

---

##  Key Questions Answered

- Which platforms were most successful over time?
- What genres and platforms dominate each region?
- Do critic and user reviews affect game sales?
- Are user ratings consistent across platforms and genres?

---

##  Project Structure

```
video-game-sales-analysis/
│
├── video_game_sales_analysis.ipynb
├── games.csv
├── requirements.txt
└── README.md

```

---

##  Tools & Libraries Used

- Python
- pandas
- numpy
- matplotlib
- scipy
- Jupyter Notebook

---

## Author

David Villanueva  
[LinkedIn](https://www.linkedin.com/in/david-villanueva-59659727)  
[GitHub](https://github.com/lolapaul)
