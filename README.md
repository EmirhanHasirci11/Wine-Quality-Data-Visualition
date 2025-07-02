# 🍷 Wine Quality Data Visualization

### 📊 Exploratory Data Analysis on Physicochemical Properties of Wine

This project explores and visualizes the **Wine Quality** dataset, focusing on how physicochemical properties such as acidity, alcohol, pH, and sulfur dioxide influence the final quality score of red and white wines.  
The aim is to extract meaningful insights through visual analytics and statistical examination.

---

## 📁 Dataset Information

The dataset includes various chemical and physical properties of wines, along with a quality score (ranging from 0 to 10).  
Main features:

- `fixed acidity`
- `volatile acidity`
- `citric acid`
- `residual sugar`
- `chlorides`
- `free sulfur dioxide`
- `total sulfur dioxide`
- `density`
- `pH`
- `sulphates`
- `alcohol`
- `quality` (target)

**Source**: [UCI Wine Quality Dataset](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset)

---

## 📊 Visualizations Included

### 1. Quality Score Distribution
- Pie chart showing the distribution of wine quality scores
- Legend includes percentage for clarity

### 2. Correlation Analysis
- Heatmap showing pairwise correlations between features
- Horizontal bar chart showing correlation with `quality`

### 3. Histograms of All Features
- Subplots for each numeric feature
- Includes KDE curves for distribution shape

### 4. Grouped Feature Averages
- Bar chart showing mean values of features per quality level

---

## 🔍 Key Insights

- `Alcohol` and `sulphates` positively correlate with wine quality.
- `Volatile acidity` negatively correlates with wine quality.
- Most wines are rated 5 or 6, showing slight class imbalance.

---

## 🛠️ Technologies Used

| Tool          | Purpose                |
|---------------|------------------------|
| Python        | Programming language   |
| Pandas        | Data processing        |
| Seaborn       | Statistical plotting   |
| Matplotlib    | Data visualization     |
| NumPy         | Numerical computing    |

---
## 📓 View the Notebook on Kaggle

You can explore the full interactive notebook on Kaggle here:

👉 [Wine Quality Data Visualization on Kaggle](https://www.kaggle.com/code/emirhanhasrc/wine-quality-data-visualition)

> This version includes all visualizations and analysis directly runnable in a Kaggle environment with the dataset already integrated.

