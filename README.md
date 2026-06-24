# Codveda Technology - Data Analytics Internship 📊

This repository contains my completed tasks for the **Data Analytics Internship** at [Codveda Technology](https://codveda.com).

## 🏢 About Codveda
Codveda Technology specializes in web development, app development, digital marketing, SEO optimization, AI/ML automation, and data analysis solutions.

## 📋 Internship Tasks Overview

The internship is divided into 3 levels, with 3 tasks per level. Any 2 tasks per level fulfill the requirement.

---

## ✅ Level 1 (Basic) — Completed

| Task | Description | Tools |
|------|-------------|-------|
| **Task 1** | Data Cleaning and Preprocessing | Python, pandas |
| **Task 2** | Exploratory Data Analysis (EDA) | Python, pandas, matplotlib, seaborn |
| **Task 3** | Basic Data Visualization | Python, matplotlib, seaborn |

**Dataset Used:** Iris Dataset (`iris.csv`)

### Key Highlights
- Cleaned dataset by handling missing values and removing duplicate rows
- Standardized categorical text formatting
- Performed statistical analysis (mean, median, mode, standard deviation)
- Visualized feature distributions and relationships using histograms, boxplots, and scatter plots
- Identified strong correlation between petal length and petal width (0.96)

📁 [View Level 1 Files](./Level1)

---

## ✅ Level 2 (Intermediate) — Completed

| Task | Description | Tools |
|------|-------------|-------|
| **Task 1** | Regression Analysis | Python, scikit-learn, pandas |
| **Task 2** | Time Series Analysis | Python, pandas, matplotlib, statsmodels |
| **Task 3** | Clustering Analysis (K-Means) | Python, scikit-learn, matplotlib, seaborn |

**Datasets Used:** House Prediction Dataset, Stock Prices Dataset (AAPL), Iris Dataset

### Key Highlights
- Built a Linear Regression model to predict house prices (MEDV), achieving an R² score of ~0.67
- Identified `RM` (rooms) and `LSTAT` (% lower status population) as the strongest predictors of house price
- Analyzed AAPL stock price trends (2014–2018) using moving averages (MA-20, MA-50) to smooth daily volatility
- Performed seasonal decomposition (trend, seasonality, residuals) on AAPL closing prices using statsmodels
- Applied K-Means clustering on the Iris dataset, using the Elbow Method to confirm the optimal number of clusters (K=3)
- Visualized clusters in 2D, closely matching the dataset's three natural species groups

📁 [View Level 2 Files](./Level2)

---

## ✅ Level 3 (Advanced) — Completed

| Task | Description | Tools |
|------|-------------|-------|
| **Task 1** | Predictive Modeling (Classification) | Python, scikit-learn, pandas |
| **Task 3** | NLP - Sentiment Analysis | Python, nltk, TextBlob |

**Datasets Used:** Customer Churn Dataset, Social Media Sentiment Dataset

### Key Highlights
- Preprocessed customer churn data (label encoding for categorical features, feature scaling)
- Trained and compared three classification models: Decision Tree, Logistic Regression, and Random Forest
- Random Forest performed best, and after hyperparameter tuning with GridSearchCV achieved **95.5% accuracy**, **97.2% precision**, and an F1-score of **0.82**
- Identified that accuracy alone was misleading on this imbalanced dataset — Logistic Regression scored 86% accuracy but only 21.6% recall, missing most actual churners
- Preprocessed social media text (tokenization, stopword removal, lemmatization) and applied TextBlob for sentiment scoring
- Classified posts into Positive, Negative, and Neutral sentiment, then visualized results with bar charts and word clouds highlighting key terms per sentiment category

📁 [View Level 3 Files](./Level3)

---

## 🎉 Internship Summary

| Level | Tasks Completed |
|-------|------------------|
| Level 1 (Basic) | 3/3 ✅ |
| Level 2 (Intermediate) | 3/3 ✅ |
| Level 3 (Advanced) | 2/3 ✅ |

All internship requirements have been fulfilled (minimum 2 tasks per level). This repository documents the complete data analytics workflow — from data cleaning and exploratory analysis to predictive modeling, time series analysis, clustering, and natural language processing.

---

## 🛠️ Tools & Technologies
- **Language:** Python 3.12
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels, nltk, TextBlob
- **Environment:** Jupyter Notebook, VS Code

## 👤 Author
**Jishan**
- LinkedIn: [linkedin.com/in/jishann](https://linkedin.com/in/jishann)
- GitHub: [github.com/nijishann](https://github.com/nijishann)
- CSE Student, Port City International University

## 📜 License
This project is for educational purposes as part of the Codveda Technology internship program.

---
*#CodvedaJourney #CodvedaExperience #FutureWithCodveda*
