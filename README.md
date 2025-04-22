# 🎬 Movies Correlation Analysis Project

This project aims to explore the relationships between different numerical features in a dataset of movies using correlation analysis. The goal is to identify which features are most strongly related to each other and derive insights that could be useful in movie analytics or recommendation systems.

## 📂 Dataset

The dataset used is `movies.csv`, which contains the following relevant columns:
- `budget`
- `gross`
- `score`
- `votes`
- `runtime`
- and more...

The data is pre-cleaned to remove null values and irrelevant columns for correlation analysis.

## 🔍 Key Steps

1. **Importing Libraries**: Includes standard data science packages like `pandas`, `seaborn`, `matplotlib`, and `numpy`.

2. **Data Cleaning**:
   - Removed missing/null values
   - Dropped irrelevant or non-numerical columns for correlation

3. **Exploratory Data Analysis (EDA)**:
   - Analyzed distributions
   - Sorted and filtered data for insights

4. **Correlation Matrix & Heatmap**:
   - Computed Pearson correlation coefficients
   - Visualized correlations using a heatmap

## 📊 Findings

- Strong positive correlation between `budget` and `gross`.
- `Votes` also showed a significant correlation with `gross`.
- Other features like `score` had a weaker but noticeable correlation.

## 📌 Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/movies-correlation-analysis.git
   cd movies-correlation-analysis
