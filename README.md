# Week-1: Stock and News Sentiment Analysis (AAPL)

## Project Overview
This project explores the relationship between Apple Inc. (AAPL) stock movements and news sentiment. It is divided into three tasks:

1. **Task 1:** Exploratory Data Analysis (EDA) and Git/GitHub workflow  
2. **Task 2:** Quantitative stock analysis using `yfinance` and TA-Lib indicators  
3. **Task 3:** Correlation analysis between news sentiment and daily stock returns

---

## Repository Structure

```

week1-project/
│
├── data/
│   ├── raw_analyst_ratings.csv
│   ├── cleaned_analyst_ratings.csv
│   ├── raw_stock_data.csv
│   └── cleaned_stock_data.csv
│
├── notebooks/
│   ├── task1_stock_analysis.ipynb
│   ├── task2_stock_analysis.ipynb
│   ├── task3_news_stock_correlation.ipynb
│
├── scripts/
├── tests/
├── README.md

````

---

## How to Run

1. Clone the repository:
```bash
git clone <your-repo-link>
cd week1-project
````

2. Create a Python virtual environment:

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

3. Install required packages:

```bash
pip install -r requirements.txt
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Run the notebooks in order:

   * Task 1 → Task 2 → Task 3

---

## Dependencies

* Python >= 3.8
* pandas
* numpy
* yfinance
* matplotlib
* TextBlob
* TA-Lib


## Notes

* All stock data is from Yahoo Finance (AAPL, 2010–2025)
* News data comes from `raw_analyst_ratings.csv`
* Sentiment analysis uses TextBlob polarity scores
* Plots included in notebooks illustrate trends and correlation
