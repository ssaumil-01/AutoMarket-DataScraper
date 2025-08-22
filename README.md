# AutoMarket-DataScraper

## 📌 Project Overview

**AutoMarket-DataScraper** is a data engineering project where I collected and processed large-scale used car listings from [CarDekho.com](https://www.cardekho.com). The goal was to build a structured dataset of used cars across multiple Indian cities that can be further utilized for **data analysis, visualization, and machine learning applications** (e.g., price prediction, trend analysis).

## 🚗 Key Features

- Scraped **18,000+ used car listings** from CarDekho across different Indian cities.
- Automated data collection using **Selenium** and **BeautifulSoup**.
- Designed preprocessing pipelines to clean and structure the raw scraped data.
- Generated a final dataset suitable for **EDA (Exploratory Data Analysis)** and **Machine Learning tasks**.

## 🛠️ Tools & Technologies

- **Python**
- **Selenium** → Automated browsing and data extraction.
- **BeautifulSoup** → HTML parsing for structured data scraping.
- **Pandas** & **NumPy** → Data preprocessing and cleaning.
- **Jupyter Notebook** → Interactive development and documentation.

## 📂 Repository Structure

```
AutoMarket-DataScraper/
│
├── Web Scraping.ipynb        # Notebook for web scraping with Selenium & BeautifulSoup
├── Data Preprocessing.ipynb  # Notebook for cleaning and preprocessing scraped dataset
├── README.md                 # Project documentation
└── dataset/                  # (Optional) Final preprocessed dataset
```

## 🔍 Workflow

1. **Web Scraping**

   - Collected raw HTML content of car listings.
   - Extracted details such as brand, model, price, year, fuel type, transmission, mileage, location, etc.

2. **Data Preprocessing**

   - Removed missing/duplicate records.
   - Standardized inconsistent values (e.g., price formats, mileage units).
   - Encoded categorical features.
   - Final dataset prepared with **clean 18K+ entries**.

## 📊 Applications

This dataset can be used for:

- Market trend analysis of used cars in India.
- Predictive modeling for used car prices.
- Consumer insights and buyer behavior studies.
- Visualizing car distribution by city, brand, and features.

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Install dependencies:

```bash
pip install -r requirements.txt
```

### Run the Notebooks

1. Open **Web Scraping.ipynb** → Run all cells to perform scraping (requires ChromeDriver setup).
2. Open **Data Preprocessing.ipynb** → Run all cells to clean and preprocess dataset.

## 📌 Future Enhancements

- Add visualization dashboards (e.g., Streamlit / Power BI).
- Extend scraping to include more attributes (e.g., seller type, car condition).
- Build a machine learning model for **used car price prediction**.

