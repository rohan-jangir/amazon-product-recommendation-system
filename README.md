# Amazon Product Search Engine and Recommendation System

This project implements a search engine and product recommendation system using the Amazon product dataset. It utilizes Natural Language Processing (NLP) techniques, including tokenization and stemming, as well as a TF-IDF vectorizer for calculating the cosine similarity between product titles and descriptions.

## Features

- **Product Search**: Users can enter a product name to find similar products based on their titles and descriptions.
- **Recommendation System**: Ranks products based on their similarity to the user's query, providing the top 10 relevant results.
- **Interactive Web App**: Built with Streamlit for a user-friendly interface.

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK (Natural Language Toolkit)
- Scikit-learn (for TF-IDF and cosine similarity)
- Streamlit (for the web app)
- PIL (Python Imaging Library for handling images)

## Search for Products
* Enter the product name in the input field and click on the "Search" button.
* The app will display the top 10 products that are most similar to your query based on their titles and descriptions.

## Data Preprocessing
* The project loads the Amazon product dataset and removes unnecessary columns.
* It creates a new column with stemmed tokens from the product titles and descriptions to facilitate similarity calculations.
