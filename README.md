# 📊 Customer Behavior & Rating Prediction

An end-to-end data analytics and machine learning project focused on analyzing customer behavior and predicting product/service ratings using SQL and Python. This project demonstrates business-focused exploratory analysis, feature engineering, sentiment signals, and predictive modeling to generate actionable insights.

---

## 🎯 Project Objective

The goal of this project is to analyze customer behavior and review data to:

* Understand patterns in customer ratings and feedback
* Extract sentiment and keyword signals from text reviews
* Identify drivers influencing customer ratings
* Build machine learning models to predict customer ratings
* Translate analytical findings into business insights

This project simulates a real-world business analytics workflow from raw data to predictive insights.

---

## 🗂 Dataset

The dataset contains customer records including:

* Customer attributes
* Product / service interaction features
* Review text and ratings
* Behavioral and engagement indicators

Text fields are processed using NLP techniques for sentiment and keyword extraction.

---

## 🛠 Tech Stack

**Languages & Libraries**

* Python
* SQL
* Pandas, NumPy
* scikit-learn
* NLTK
* VADER Sentiment
* RAKE (keyword extraction)
* WordCloud
* ydata-profiling / pandas-profiling
* Pillow, scikit-image

**Techniques**

* Data cleaning & preprocessing
* Exploratory Data Analysis (EDA)
* Text preprocessing & NLP
* Sentiment analysis
* Feature engineering
* Supervised machine learning models

---

## 🔎 Analysis Workflow

### Data Preparation

* Cleaned and standardized structured fields
* Handled missing and inconsistent values
* Encoded categorical variables
* Normalized selected numeric features

### Exploratory Data Analysis

* Distribution analysis of ratings and behavior metrics
* Correlation analysis between customer attributes and ratings
* Pattern discovery across engagement variables
* Automated profiling reports generated

### Text & Sentiment Processing

* Tokenization and stopword removal
* Sentiment scoring using VADER
* Keyword extraction using RAKE
* Review signal enrichment for modeling

### Feature Engineering

* Derived sentiment features
* Behavioral aggregates
* Text-based indicators
* Model-ready feature matrix creation

---

## 🤖 Modeling

Multiple ML models were trained and evaluated for rating prediction, such as:

* Regression / classification models (based on rating structure)
* Tree-based models
* Ensemble approaches

Evaluation included:

* Cross-validation
* Error metrics / accuracy metrics
* Feature importance analysis

---

## 📈 Key Insights

* Customer sentiment signals strongly influence predicted ratings
* Specific keyword clusters correlate with high and low ratings
* Behavioral engagement features improve prediction performance
* Combined structured + text features outperform structured data alone

---

## 💼 Business Value

This analysis approach can help organizations:

* Predict customer satisfaction scores
* Detect early dissatisfaction signals
* Improve targeting and retention strategies
* Prioritize product or service improvements
* Support data-driven customer experience decisions

---

## ▶️ How to Run

### Install Dependencies

```bash
pip install nltk
pip install vaderSentiment
pip install wordcloud
pip install pandas_profiling[notebook,html]
pip install ydata_profiling
pip install pillow
pip install skimage
pip install rake_nltk
pip install counter
```

### Run

1. Open the notebook(s) in Jupyter
2. Load the dataset into the data folder
3. Execute cells sequentially
4. Review EDA outputs, sentiment features, and model results

---

## 📌 Repository Structure

```
data/                → raw and processed datasets  
notebooks/           → EDA and modeling notebooks  
reports/             → profiling and visualization outputs  
src/                 → helper scripts (if applicable)  
```

---

## 🚀 Future Improvements

* Hyperparameter tuning
* Model explainability (SHAP / feature attribution)
* Dashboard layer for stakeholder reporting
* Automated pipeline for retraining

---

## 📜 License

This project is for academic and educational use. Add a formal license if distributing publicly.
