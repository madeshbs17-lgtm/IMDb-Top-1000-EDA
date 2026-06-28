# 🎬 IMDb Top 1000 Movies - Exploratory Data Analysis

## 📖 Overview

This project presents an Exploratory Data Analysis (EDA) of the IMDb Top 1000 Movies dataset using Python. The analysis focuses on understanding movie ratings, revenue, directors, actors, genres, and runtime through data cleaning and visualization.

## 📂 Dataset

* **Dataset:** IMDb Top 1000 Movies
* **Source:** Kaggle
* **Records:** 1,000 Movies

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📋 Data Preparation

The following preprocessing steps were performed:

* Loaded the dataset using Pandas
* Removed the `Poster_Link` column
* Checked dataset information and summary statistics
* Identified missing values
* Checked for duplicate records
* Converted `Gross` to a numeric data type
* Converted `Released_Year` to a numeric data type
* Converted `Runtime` from text to numeric values

## 📊 Analysis Performed

### Dataset Exploration

* Dataset overview
* Data types
* Shape of the dataset
* Summary statistics
* Missing value analysis
* Duplicate record check

### Visualizations

* Top 10 Directors by Gross Revenue (1990–2000)
* Top 10 Directors by Average IMDb Rating
* Most Successful Lead Actors by Gross Revenue
* Gross Revenue vs IMDb Rating
* Number of Votes vs IMDb Rating
* Number of Votes vs Gross Revenue
* Top 10 Movie Genres
* Runtime Trends Over the Years
* Top Genres by Gross Revenue

## 🔍 Key Objectives

* Explore relationships between movie ratings and revenue.
* Analyze the impact of audience votes on commercial success.
* Identify successful directors and lead actors.
* Examine genre-wise revenue trends.
* Study how average movie runtime has changed over the years.

## 🚀 How to Run

1. Clone this repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the Jupyter Notebook and run all cells.

## 📁 Repository Structure

```text
IMDb-Top-1000-EDA/
│── Movie_Dataset.ipynb
│── imdb_top_1000.csv
└── README.md
```

## 📌 Note

This project was created for learning and practicing Exploratory Data Analysis (EDA) techniques using Python and the IMDb Top 1000 Movies dataset.
