# Sentiment-Analysis-on-Out-Of-Vocabulary-OOV-Malaysia-Rojak-Language
Uses algorithms like SNN, KNN, Naive Bayes, Decision Tree, VADER, and BERT to analyse the intricate language  used in Shopee reviews, ensuring accurate interpretation of sentiments for Malaysia Rojak.

## Table of Contents
- [Introduction](#introduction)
- [Methodology](#methodology)
- [Results](#results)
- [License](#license)
- [References](#references)

## Introduction

This project utilises sentiment analysis techniques such as Support Vector Machines, Convolutional Neural Networks, and BERT to evaluate customer feedback from the "W Baju Melayu" store on Shopee. It aims to reveal insights from the diverse mix of Malay and English in customer reviews, enabling informed decisions for enhancing products and services.

## Methodology

### Data Collection

- **Source:** W Baju Melayu store on Shopee [W Baju Melayu Shopee](https://shopee.com.my/wakakagiftshop)
- **Size:** 400 reviews
- **Attributes:** Users ID, Ratings (From 1 to 5), Review

### Data Preprocessing

1. **Data Cleaning and Formatting:** Removing noise and standardising text.
2. **Data Translation:** Converting text from one language to another.
3. **Tokenisation:** Splitting text into individual words or tokens.
4. **Normalisation:** Standardising text by adjusting formats or cases.
5. **Pos-Tagging:** Assigning parts of speech to each word.
6. **Data Stemming:** Reducing words to their root forms.

### Clustering Algorithms

1. **Simple Neural Network:** Basic model learning patterns through layers of neurons.
2. **Naive Bayes:** Probabilistic classifier using Bayes' theorem with independent features.
3. **K-Nearest Neighours(KNN):** Classifies based on the majority class of nearest neighbours.
4. **Decision Tree:** Splits data into branches to make decisions or classifications.
5. **VADER:** Rule-based tool for sentiment analysis in social media text.
6. **BERT:** Transformer model for bidirectional natural language understanding.

## Results

**Logistic regression.** Achieved an F1 score of **0.7778**, indicating a strong balance between precision and recall.

**LSTM model.** Displayed the lowest F1 score of **0.3333**, suggesting challenges in achieving a harmonious trade-off between precision and recall.

## License

This project forms part of an academic course and is intended solely for educational purposes. It may include references to copyrighted materials and any such materials are utilised exclusively for scholarly use. For guidance on sharing or distributing this work, it is advisable to seek consultation from your instructor or institution.

For more details, see the [LICENSE](./LICENSE.txt) file.

## Reference
**Dataset:** [W Baju Melayu Shopee Review](https://shopee.com.my/wakakagiftshop)
