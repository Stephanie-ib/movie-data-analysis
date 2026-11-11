# movie-data-analysis
# 🎬 Movie Industry Data Analysis & Correlation Study

An end-to-end Exploratory Data Analysis (EDA) project examining a 40-year dataset of movies (1980–2020) to uncover the key drivers behind box office success and financial profitability[cite: 6].

---

## 📋 Project Overview
Understanding what makes a movie financially successful is a classic challenge in the entertainment industry. This project utilizes Python to explore a dataset of **7,668 movies** across **15 variables** (including budget, gross earnings, user scores, genres, and directors) to analyze trends, check data quality, and visualize key correlations[cite: 6].

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation & Cleaning:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib

---

## 🔍 Key Project Workflow & Steps

1. **Data Loading & Inspection:**
   * Loaded a dataset spanning 1980 to 2020 with 7,668 rows and 15 columns[cite: 6].
   * Inspected data types, column structures, and overall dataset health.

2. **Data Cleaning & Quality Control:**
   * Handled missing values across key financial and categorical features (identifying a 28% missing rate in production budgets and 2% in gross earnings)[cite: 6].
   * Managed duplicate rows using `drop_duplicates()` to maintain dataset integrity[cite: 6].

3. **Exploratory Data Analysis (EDA) & Visualization:**
   * Utilized boxplots to detect and analyze financial outliers in movie budgets and gross revenues[cite: 6].
   * Built regression plots (`sns.regplot`) to examine relationships between variables—such as the correlation between film budgets, user votes, and total gross earnings[cite: 6].
   * Examined top-grossing films across the 40-year timespan (including blockbusters like *Avatar*, *Avengers: Endgame*, and *Titanic*)[cite: 6].

---

## 💡 Key Insights & Findings
* **Budget & Gross Correlation:** Production budget exhibits a strong positive relationship with overall box office gross revenue.
* **Votes Matter:** User engagement and vote counts strongly correlate with financial success, highlighting the impact of audience reach and popularity.
* **Data Completeness:** Managing missing data (particularly regarding historical budgets from older films) is a critical prerequisite for accurate movie industry modeling.

---

## 🚀 Getting Started

If you'd like to run or review the notebook locally:

1. Clone the repository:
   ```bash
   git clone [https://github.com/Stephanie-ib/movie-data-analysis.git](https://github.com/Stephanie-ib/movie-data-analysis.git)
