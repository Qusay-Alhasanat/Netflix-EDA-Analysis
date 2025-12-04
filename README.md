# Netflix Data Analysis — Data Science Portfolio Project
**Entry-level / Learning Project**  

This project is part of my learning journey in Data Science. The goal is to clean, explore, and analyze Netflix's catalog dataset to uncover trends and insights about content production, genres, duration, and audience categories.

---

## Dataset
The dataset `netflix_titles.csv` contains information about Netflix titles, including:  
- Show ID, Title, Type (Movie or TV Show)  
- Director, Cast, Country  
- Date Added, Release Year  
- Rating, Duration, Genres (`listed_in`), Description  

The cleaned dataset `netflix_cleaned.csv` includes additional features:  
- `year_added`, `month_added`  
- `category` (Kids, Teens, Adults, Unknown)  
- `is_Recent` (1 if released >= 2015, else 0)  
- `duration_min` for movies  
- `duration_seasons` for TV shows  
- `main_genre` for simplified genre analysis

---

## Notebook
The analysis is available in `Netflix_EDA.ipynb`, which contains:  
1. Data cleaning and preparation  
2. Feature engineering  
3. Exploratory Data Analysis (EDA) with visualizations  
4. Insights and key findings

---

## Key Insights
- Netflix has more movies than TV shows in the dataset.  
- Most content is targeted at Adults, but a significant portion is available for Kids.  
- Movies generally last 90–120 minutes; TV shows are mostly 1–2 seasons.  
- Netflix focuses on recent content (post-2015 releases).  
- Top genres include Dramas, International Movies, and Comedies.  

These insights were derived through visualizations and analysis in the notebook.

---

## Dashboard & Reporting
- A **Power BI dashboard** can be created using `netflix_cleaned.csv` for interactive trend exploration.  
- Visualizations and charts from the notebook can be exported as images for reporting purposes.  

---

## How to Run
1. Open `Netflix_EDA.ipynb` in **Jupyter Notebook**.  
2. Ensure `netflix_titles.csv` is in the `data/` folder.  
3. Run all cells sequentially to reproduce the cleaned dataset and visualizations.  
4. Save `netflix_cleaned.csv` for future analysis or dashboard integration.

---

## Author
**Qusay — Data Science Portfolio Project (Entry-level / Learning Project)**  
[🔗 LinkedIn Profile](https://www.linkedin.com/in/qusay-alhasanat)  
[🔗 GitHub Profile](https://github.com/Qusay-Alhasanat)  
[📧 Email Me](mailto:qusay.alhasanat1@gmail.com)
