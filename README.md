# **🎬 Netflix Data Analysis – Exploratory Data Analysis (EDA)**


This project performs an in-depth Exploratory Data Analysis (EDA) on the Netflix Titles dataset. It uncovers meaningful insights about content trends, genres, ratings, durations, and global distribution to support content strategy and decision-making.

## 📌 Project Overview

This project aims to:

Analyze Netflix’s movie and TV show catalog

Study genre dominance and viewer preferences

Understand rating distributions and audience segmentation

Explore global content contributions (countries producing the most titles)

Analyze content release trends across years

Examine movie durations and TV show season counts

Identify patterns useful for strategy, recommendations, and content planning

## 📁 Dataset

Source: Netflix Titles dataset

Format: CSV

Records: 8,800+ titles

Key Features:

type, title, director, cast

country, rating, listed_in (genres)

duration, release_year

date_added

Cleaning steps performed:

Removed duplicates

Filled missing values in country, rating, date_added

Extracted numeric duration

Split genres

Converted dates to proper datetime formats

## 🛠 Technologies Used

Python

Pandas – data cleaning & manipulation

NumPy – numerical operations

Matplotlib & Seaborn – data visualization

Jupyter Notebook – analysis environment

## 📊 Key Insights Extracted

🔹 1. Genre Distribution

Drama, Comedy, Documentaries dominate Netflix’s library

Genre diversity is high, supporting a broad audience base

🔹 2. Release Year Trends

Major surge in content after 2015

Indicates rising investment in originals and acquisitions

🔹 3. Country Contributions

USA leads significantly

India, UK, Canada, Japan follow

Strong global expansion patterns observed

🔹 4. Content Ratings

TV-MA & TV-14 dominate → mature audience focus

🔹 5. Durations & Engagement

Movies mostly between 80–120 minutes

TV Shows vary; many have 1–2 seasons (binge-friendly)

## 📈 Visualizations Included

Genre bar charts

Release year trends

Country-wise content distribution

Rating distribution

Movie duration histograms

TV seasons count

Genre evolution over years

Ratings vs Duration correlations

Monthly/Yearly addition trends

## 📘 Project Files in Repository
File	Description
netflix_data_analysis.ipynb	Full Python analysis & visualizations
netflix_titles.csv	Dataset used for analysis
README.md	Documentation
🚀 Future Improvements

Add clustering for viewer preference segmentation

Build a recommendation engine

Integrate user watch-time / engagement data

Dashboard using Power BI / Tableau

💡 Conclusion

This analysis provides strong insights into Netflix’s evolving content library, enabling better content strategy decisions, audience targeting, global planning, and recommendation systems.

👤 Author

Inigoanand L
Data Analyst | Python | SQL | Visualization
