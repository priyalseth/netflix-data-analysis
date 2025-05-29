# netflix-data-analysis
Netflix Movies and TV Shows Dataset Analysis Project
# 🎬 Netflix Movies and TV Shows Analysis

This project analyzes the Netflix Movies and TV Shows dataset to uncover insights about content trends, popular genres, countries of origin, and more. 

## 📊 Project Overview

Netflix has become one of the world's largest streaming platforms. This analysis explores:

- Distribution of Movies vs TV Shows
- Top contributing countries
- Yearly trends of content added
- Most common genres
- Most featured directors and actors

The project is performed using Python in Google Colab with Pandas, Seaborn, and Matplotlib.

---

## 📁 Dataset

- **Source**: [Netflix Movies and TV Shows on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File used**: `netflix_titles.csv`
- **Size**: ~6,000+ entries with fields like title, type, country, cast, director, rating, genres, and date added.

---

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 🔄 Data Cleaning

- Removed duplicate rows
- Converted `date_added` to datetime format
- Handled missing values (e.g., director, cast, country, date_added)
- Extracted year/month from `date_added` for trend analysis

---

## 📈 Exploratory Data Analysis (EDA)

Visualizations created:

- ✅ Count of Movies vs TV Shows
- ✅ Top 10 Countries by Number of Titles
- ✅ Trend of Titles Added Each Year
- ✅ Top 10 Most Common Genres
- ✅ Most Featured Directors
- ✅ Most Featured Actors

---

## 💡 Key Insights

- **Movies** form the majority of Netflix content.
- **USA** contributes the largest number of titles.
- There was significant content growth between **2017 to 2020**.
- Most popular genres include ** International movies, Dramas, and Comedies**.
- Directors like `Rajiv Chilaka` and actors like `Anupam Kher` appear frequently.

---

## 📚 How to Run

1. Open the Jupyter notebook (`netflix_analysis.ipynb`) in Google Colab or locally.
2. Upload the `netflix_titles.csv` file.
3. Run all cells to reproduce the analysis and visualizations.

---

## 📌 Author

👤 **Priyal Seth**  
📧 sethshreya1999@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/priyal-seth-2493302a2/) | [GitHub](https://github.com/priyalseth)

---

## 📦 Future Work

- Add interactive visualizations with Plotly
- Build a dashboard using Power BI.
- Explore content ratings by age and region
