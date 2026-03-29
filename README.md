# 🎬 Netflix Movies vs TV Shows Analysis

A data analysis project exploring and comparing Movies and TV Shows
available on Netflix using Python and its data science libraries.

---

## 📌 About the Project

This project analyzes the Netflix dataset to uncover key insights and trends
between Movies and TV Shows — including content distribution, ratings breakdown,
release trends over the years, top producing countries, and more.

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** — Data loading, cleaning, and manipulation
- **Matplotlib** — Data visualization (bar charts, pie charts, histograms, scatter plots, line charts)

---

## 📂 Project Structure
```
data-science/
│
├── datasets/
│   └── netflix_titles.csv         # Netflix dataset
│
├── notebooks/
│   └── Netflix_Movies_VS_TV_Show.ipynb  # Main analysis notebook
│
└── README.md
```

---

## 📊 Key Analyses Performed

- **Movies vs TV Shows Count** — Bar chart comparing the number of Movies and TV Shows on Netflix
- **Rating Distribution** — Pie chart showing the breakdown of content ratings (TV-MA, PG-13, TV-14, etc.)
- **Movie Duration Distribution** — Histogram of movie runtimes (in minutes)
- **Release Year vs Number of Shows** — Scatter plot of content added over the years
- **Top 10 Countries by Number of Shows** — Horizontal bar chart of most productive countries
- **Movies and TV Shows Released Over Years** — Line chart comparison of Movies vs TV Shows released per year

---

## ▶️ How to Run

1. Clone the repository
```
   git clone https://github.com/your-username/data-science.git
```

2. Navigate to the project folder
```
   cd data-science
```

3. Install required libraries
```
   pip install pandas matplotlib
```

4. Open the notebook
```
   jupyter notebook notebooks/Netflix_Movies_VS_TV_Show.ipynb
```

---

## 📁 Dataset

- **Source:** [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File:** `netflix_titles.csv`
- **Preprocessing:** Rows with missing values in `type`, `release_year`, `rating`, `country`, or `duration` were dropped

---

## 🔍 Key Findings

- Netflix has significantly more **Movies** than TV Shows in its library
- **TV-MA** is the most common content rating on Netflix
- Most movies on Netflix have a duration between **80–120 minutes**
- Content additions on Netflix **peaked around 2018–2020**
- The **United States** produces the most Netflix content, followed by India and the United Kingdom
- Both Movies and TV Shows saw a rapid increase in releases post-2010

---

## 👤 Author

**Aman Raj**
- GitHub: [ELBERTAMAN](https://github.com/ELBERTAMAN/NETFLIX-VISUALIZATION)

