# 🎬 Netflix Data Analysis

Exploratory Data Analysis (EDA) of a Netflix movies dataset to uncover trends in genres, popularity, ratings, languages, and release patterns using Python and interactive visualizations.

---

## 📁 Project Structure

```
Netflix-Data-Analysis/
│
├── Netflix_Data_Analysis.ipynb   # Main Jupyter Notebook with full EDA
├── NetflixData.csv               # Dataset used for analysis
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

---

## 📊 Dataset

The dataset (`NetflixData.csv`) contains information about Netflix movies with the following columns:

| Column | Description |
|---|---|
| `Release_Date` | Date the movie was released |
| `Title` | Movie title |
| `Overview` | Brief description of the movie |
| `Popularity` | Popularity score |
| `Vote_Count` | Number of votes received |
| `Vote_Average` | Average rating (out of 10) |
| `Original_Language` | Language the movie was originally made in |
| `Genre` | Genre(s) of the movie |
| `Poster_Url` | URL to the movie poster image |

---

## 🔍 Analysis Performed

- **Data Loading & Preview** — Loading the CSV and inspecting the first few rows
- **Data Cleaning** — Handling missing values and fixing data types
- **Genre Analysis** — Most frequent genres on Netflix
- **Popularity Analysis** — Which genres attract the highest audience engagement
- **Vote & Rating Distribution** — Understanding how movies are rated
- **Language Distribution** — Breakdown of movies by original language
- **Release Year Trends** — Growth in movie releases over time
- **Popularity Distribution** — Skewness in popularity scores

---

## 💡 Key Insights

- **Drama** is the most frequently occurring genre in the dataset.
- **Adventure** movies show the highest average popularity score.
- **Action** and **Science Fiction** also attract high audience interest.
- The number of movie releases increased significantly **after the year 2000**, reflecting the rapid growth of streaming platforms.
- Popularity distribution is **highly skewed** — most movies are average, and only a few become blockbuster hits.

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** — Data manipulation and analysis
- **Plotly Express** — Interactive visualizations
- **Jupyter Notebook** — Development environment

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Netflix-Data-Analysis.git
cd Netflix-Data-Analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch the notebook

```bash
jupyter notebook Netflix_Data_Analysis.ipynb
```

> **Note:** If you're running on Google Colab, upload `NetflixData.csv` to `/content/` before executing the cells.

---

## ☁️ Run on Google Colab

You can open this notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

> Upload `NetflixData.csv` to the Colab session files before running.

---

## 📬 Contact

Feel free to reach out or raise an issue if you have suggestions or questions!
