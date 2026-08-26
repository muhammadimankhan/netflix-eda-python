# 🎬 Netflix Movies & TV Shows — Data Cleaning & Exploratory Data Analysis

## 📌 Project Overview

This project performs end-to-end **data cleaning and exploratory data analysis (EDA)** on the Netflix Movies & TV Shows dataset containing **8,800+ titles** sourced from Kaggle. The goal is to uncover patterns, trends, and insights hidden in Netflix's content catalog through professional visualizations and structured analysis.

---

## 📂 Dataset

- **Source:** [Kaggle — Netflix Movies and TV Shows by Shivam Bansal](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File:** `netflix_titles.csv`
- **Size:** 8,800+ records × 12 columns
- **Content:** Title, type, director, cast, country, date added, release year, rating, duration, genre

---

## 🧹 Data Cleaning Steps

| Step | Action |
|------|--------|
| 1 | Removed duplicate records |
| 2 | Filled missing Director values with 'Unknown Director' |
| 3 | Filled missing Cast values with 'Unknown Cast' |
| 4 | Filled missing Country values with 'Unknown Country' |
| 5 | Filled missing Rating values with mode |
| 6 | Dropped rows with missing Date Added |
| 7 | Parsed and standardized date_added column |
| 8 | Extracted Year and Month from date_added |
| 9 | Split Duration into numeric value and unit |

---

## 📊 Analysis & Visualizations

| Chart | Description |
|-------|-------------|
| Missing Value Heatmap | Visual map of missing data before cleaning |
| Content Type Distribution | Movies vs TV Shows — count and percentage |
| Content Added Per Year | Yearly trend by content type |
| Top 10 Countries | Most prolific content-producing countries |
| Top 10 Genres | Most common genres on Netflix |
| Rating Distribution | Content rating breakdown |
| Movie Duration Distribution | Histogram with mean line |
| Monthly Content Trend | Which months Netflix adds most content |
| Top 10 Directors | Most prolific directors on Netflix |

---

## 💡 Key Insights

- **Movies** make up the majority of Netflix's catalog
- **United States** is the top content-producing country by a significant margin
- **International Movies** is the most common genre
- Netflix adds the most content in **Q4 (October–January)**
- Average movie duration is approximately **90–100 minutes**
- **TV-MA** is the most common content rating

---

## 🛠️ Tools & Libraries

```
Python 3.10
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
```

---

## 📁 Repository Structure

```
netflix-eda-python/
│
├── Netflix_EDA_Muhammad_Iman_Khan.ipynb   # Main analysis notebook
├── netflix_titles.csv                      # Dataset (download from Kaggle)
├── charts/
│   ├── 01_missing_values_heatmap.png
│   ├── 02_content_type_distribution.png
│   ├── 03_content_added_per_year.png
│   ├── 04_top_countries.png
│   ├── 05_top_genres.png
│   ├── 06_rating_distribution.png
│   ├── 07_movie_duration_distribution.png
│   ├── 08_monthly_content_trend.png
│   └── 09_top_directors.png
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/muhammadimankhan/netflix-eda-python.git
cd netflix-eda-python
```

2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows) and place `netflix_titles.csv` in the root folder

4. Open the notebook
```bash
jupyter notebook Netflix_EDA_Muhammad_Iman_Khan.ipynb
```

---

## 👤 Author

**Muhammad Iman Khan**
- LinkedIn: [linkedin.com/in/muhammadimankhan](https://linkedin.com/in/muhammadimankhan)
- GitHub: [github.com/muhammadimankhan](https://github.com/muhammadimankhan)
- Email: muhammadimankhan1@gmail.com

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
