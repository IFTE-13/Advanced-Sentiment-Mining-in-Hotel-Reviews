# Advanced Sentiment Mining in Hotel Reviews

### Comparative Sentiment Classification and Topic Modeling with Classical and Transformer-Based Methods

## Overview

This project explores large-scale hotel review analysis using **Natural Language Processing (NLP)** and **Machine Learning** techniques. The study focuses on extracting meaningful insights from hotel reviews through sentiment classification, topic modeling, and comparative analysis between traditional machine learning approaches and transformer-based deep learning models.

The project utilizes a dataset of over **515,000 TripAdvisor hotel reviews** and applies an end-to-end NLP pipeline including preprocessing, vectorization, exploratory analysis, sentiment prediction, and topic extraction.

---
## System Architecture
<p align="center">
  <img width="807" height="909" alt="Screenshot 2026-05-20 135213" src="https://github.com/user-attachments/assets/a4dac62d-78e7-4649-8742-56fec0fc027c" />
</p>

---

## Features

- Text preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Sentiment analysis on hotel reviews
- TF-IDF vectorization
- Classical machine learning models
- Transformer-based NLP models (BERT)
- Topic modeling using LDA
- Performance comparison of models
- Data visualization and insights extraction

<p align="center">
  <h4> NLP pipeline </h4>
  <img width="752" height="575" alt="Screenshot 2026-05-20 135259" src="https://github.com/user-attachments/assets/f3c2f4ba-f9c3-4551-a802-c42ca22a5668" />
</p>

---

## Technologies Used

### Programming Language
- Python

### Libraries & Frameworks
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- SpaCy
- Gensim
- Transformers (Hugging Face)
- PyTorch
- WordCloud

---

## Dataset

The dataset contains hotel reviews collected from TripAdvisor and includes:

- Review text
- Ratings
- User feedback
- Sentiment-related information

Dataset size:
- **515K+ reviews**

---

## ⚙️ NLP Pipeline

### 1. Data Preprocessing
- Lowercasing
- Removing punctuation
- Stopword removal
- Tokenization
- Lemmatization

### 2. Exploratory Data Analysis
- Review distribution
- Sentiment distribution
- Frequent words visualization
- Word clouds

### 3. Feature Engineering
- Bag of Words (BoW)
- TF-IDF Vectorization
- Embedding-based representations

### 4. Sentiment Classification
Implemented models include:
- Logistic Regression
- Naive Bayes
- Random Forest
- Support Vector Machine (SVM)
- BERT-based Transformer Models

### 5. Topic Modeling
- Latent Dirichlet Allocation (LDA)
- Topic interpretation and visualization

---

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/IFTE-13/Advanced-Sentiment-Mining-in-Hotel-Reviews.git
cd Advanced-Sentiment-Mining-in-Hotel-Reviews
```

### Create Virtual Environment
```bash
python -m venv venv
```

### Activate Environment
```bash
# Windows
venv\Scripts\activate
```
```bash
# Linux / macOS
source venv/bin/activate
```

### Install Dependencies
```bash
pip install -r requirements.txt
```
---

## Run the Notebook

### Launch Jupyter Notebook:
```bash
jupyter notebook
```

### Open
```bash
hotel_review_nlp_analysis.ipynb
```

---

## Future Improvements
- Fine-tuning transformer models
- Multi-language sentiment analysis
- Real-time review prediction API
- Deployment using Streamlit or Next.js
- Explainable AI integration

---

## Contributing

Contributions are welcome.

Feel free to:
- Fork the repository
- Create a feature branch
- Submit a pull request
