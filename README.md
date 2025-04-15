# Film Reviews Sentiment Analysis

This project is part of the Dicoding course "Learn Machine Learning Development". It focuses on sentiment analysis of movie reviews collected from [Letterboxd.com](https://letterboxd.com/).  
The goal is to classify each review as positive, neutral, or negative.

## 🎬 Movie List

The dataset includes reviews for the following 10 films:

- *Dune* (2021)
- *Interstellar* (2014)
- *2001: A Space Odyssey* (1968)
- *Blade Runner 2049* (2017)
- *Joker: Folie à Deux* (2024)
- *Venom* (2018)
- *Don't Worry Darling* (2022)
- *The Gift* (2015)
- *Oppenheimer* (2023)
- *Barbie* (2023)

## 📁 Project Structure

- `data-scraping.ipynb` — Notebook for scraping reviews from Letterboxd.
- `all_film_reviews.csv` — Combined dataset of all collected reviews.
- `modelling.ipynb` — Notebook for preprocessing, training, and evaluating the sentiment analysis model.
- `requirements.txt` — List of required Python packages.

## ⚙️ Setup Environment - Shell/Terminal
```bash
mkdir film-reviews-sentiment-analysis
cd film-reviews-sentiment-analysis
pipenv install
pipenv shell
pip install -r requirements.txt
```

## 🧠 Models Overview

The models that are used in this project are: 
1. Machine Learning Model with **Logistic Regression** Algorithm with an accuracy of **94.28%**
2. Deep Learning Model with **LSTM** Algorithm with an accuracy of **82.85%**
3. Pre-trained Model with **BERT** with an accuracy of **91.69%**
