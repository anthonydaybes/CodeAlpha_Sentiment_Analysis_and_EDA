# CodeAlpha Data Analytics Internship: Tasks 2, 3 & 4

An end-to-end product insights project combining Exploratory Data Analysis (EDA), interactive Data Visualization, and NLP Sentiment Analysis on customer feedback.

## 📋 Project Overview
This project uncovers patterns, public trends, and anomalies within consumer review data using an Amazon Consumer Reviews dataset (34,000+ records). The core objective is to analyze customer text reviews and validate whether calculated emotional sentiment aligns with the user's explicit star ratings.

### 💾 Dataset Source
The dataset used for this project is public and can be downloaded directly from Kaggle:
* **Dataset Link:** [Kaggle - Consumer Reviews of Amazon Products](https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products)
* **File Used:** `1429_1.csv`

---

## 🛠️ Tech Stack & Tools
* **Language:** Python 3
* **Libraries:** Pandas, NLTK (VADER), Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Anaconda
* **BI Tool:** Tableau Desktop

---

## 📊 Completed Tasks & Deliverables

### 1. Task 2: Exploratory Data Analysis (EDA)
* Profiled dataset dimensions and inspected data types.
* Handled missing values systematically within the text and metadata fields.
* Conducted structural analysis on consumer rating distributions to understand data balance.

### 2. Task 3: Data Visualization (Tableau Dashboard)
* Developed an executive dashboard layout containing multiple high-impact worksheets.
* Included a **Sentiment Distribution** breakdown to track total customer feedback volumes.
* Created a **Sentiment Validation by Rating** visual to graph how average text sentiment matches up with explicit star choices.
* **Deliverable:** The fully packaged interactive dashboard is saved in this repository as `Amazon_Sentiment_Dashboard.twbx`.

### 3. Task 4: Sentiment Analysis (NLP)
* Utilized Python's `NLTK VADER Lexicon` to clean, tokenize, and process unstructured text feedback.
* Computed exact continuous polarity scores (`-1` to `+1`) for each individual review.
* Segmented customer statements into defined qualitative metrics: **Positive**, **Neutral**, and **Negative**.

---

## 🚀 Key Insights
* **Model Validation:** The calculated backend text sentiment scores perfectly validate user star choices, scaling smoothly upward from a neutral/low baseline for 1-star reviews up to a highly positive `0.6+` compound score for 5-star reviews.
* **Business Application:** By utilizing interactive filtering on the dashboard, selecting low-sentiment segments instantly isolates specific product items requiring material or manufacturing optimization.

## 📁 How to Run the Files
1. **Python Code:** Open `CodeAlpha_Sentiment_Analysis_and_EDA.ipynb` in Jupyter Notebook to view the full cleaning and NLP modeling pipeline.
2. **Tableau Dashboard:** Download `Amazon_Sentiment_Dashboard.twbx` to open and interact with the executive visualizations directly in Tableau.
## This Project is fully made with AI 
