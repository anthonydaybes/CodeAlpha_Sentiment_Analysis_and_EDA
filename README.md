# CodeAlpha Data Analytics Internship: Tasks 2, 3 & 4

An end-to-end product insights project combining Exploratory Data Analysis (EDA), interactive Data Visualization, and NLP Sentiment Analysis on customer feedback.

## 📋 Project Overview
This project uncovers patterns, public trends, and anomalies within consumer review data using an Amazon Consumer Reviews dataset (34,000+ records). The core objective is to analyze customer text reviews and validate whether calculated emotional sentiment aligns with the user's explicit star ratings.

This project uncovers patterns, public trends, and anomalies within consumer review data using an Amazon Consumer Reviews dataset. The core objective is to analyze customer text reviews and validate whether calculated emotional sentiment aligns with the user's explicit star ratings.

### 💾 Dataset Source
The dataset used for this project is public and can be downloaded directly from Kaggle:
* **Dataset Link:** [Kaggle - Consumer Reviews of Amazon Products](https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products)
* **File Used:** `1429_1.csv`

### Completed Tasks:
* **Task 2: Exploratory Data Analysis (EDA):** Profiled dataset dimensions, handled missing values, and performed structural analysis on consumer rating distributions.
* **Task 3: Data Visualization (Tableau Dashboard):** Created an interactive Executive Dashboard mapping out sentiment volumes and validating rating behaviors.
* **Task 4: Sentiment Analysis (NLP):** Utilized Python's NLTK VADER Lexicon to compute polarity compound scores, categorizing reviews into Positive, Neutral, and Negative sentiments.

## 🛠️ Tech Stack & Tools
* **Language:** Python 3
* **Libraries:** Pandas, NLTK (VADER), Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Anaconda
* **BI Tool:** Tableau (Desktop / Public)

## 📊 Key Findings & Dashboard Interactivity
* Higher explicit customer star ratings strongly correlate with an increasing VADER compound sentiment score (scaling up from 0.0 to 0.6+).
* The dataset is heavily weighted toward positive consumer satisfaction.
* Using the interactive filter on the Tableau dashboard, selecting "Negative" instantly exposes specific product groups requiring performance adjustments or manufacturing optimization.

## 🚀 How to Run the Project
1. Clone this repository.
2. Open the `.ipynb` notebook file in Jupyter.
3. Install dependencies: `pip install pandas nltk matplotlib seaborn`.
4. Run all cells to process the text and generate the structured dataset.
5. Import `Amazon_Reviews_With_Sentiment.csv` into Tableau to interact with the dashboard sheets.
