# 🧠 Google Play Store Review Scraper and NLP Analysis Project
This project is designed to scrape reviews from the Google Play Store for a specific application, 'id.flip', and perform natural language processing (NLP) tasks such as text preprocessing, sentiment analysis, and machine learning model training for classification purposes. The primary goal is to collect and analyze user reviews to gain insights into their opinions and sentiments about the application.

## 🚀 Features
- Scrapes reviews from the Google Play Store using the `google_play_scraper` library
- Stores scraped reviews in a CSV file for further analysis
- Performs text preprocessing, including tokenization, stemming, and stopword removal
- Conducts sentiment analysis using NLTK's `SentimentIntensityAnalyzer`
- Trains machine learning models (SVM and Random Forest) for classification tasks using scikit-learn

## 🛠️ Tech Stack
- `google_play_scraper` for scraping Google Play Store reviews
- `csv` and `pandas` for handling CSV operations and data manipulation
- `nltk` for natural language processing tasks
- `sklearn` for machine learning tasks
- `tensorflow` for deep learning
- `Sastrawi` for Indonesian language-specific NLP tasks
- `numpy` for numerical computations

## 📦 Installation
To set up the project, follow these steps:
1. Install the required libraries by running `pip install -r requirements.txt`
2. Download the NLTK data packages by running `python -m nltk.downloader punkt_tab stopwords`
3. Install the `Sastrawi` library by running `pip install sastrawi`

## 💻 Usage
1. Run the `scraper.ipynb` notebook to scrape reviews from the Google Play Store
2. Run the `ProyekNLP.ipynb` notebook to perform NLP tasks and train machine learning models

## 📂 Project Structure
```
project
├── scraper.ipynb
├── ProyekNLP.ipynb
├── requirements.txt
├── ulasan_flip.csv
└── README.md
```

## 📸 Screenshots


