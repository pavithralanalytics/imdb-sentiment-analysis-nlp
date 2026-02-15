# 🎬 IMDb Sentiment Analysis using NLP

## 📌 Project Overview

This project performs **Sentiment Analysis** on IMDb movie reviews using Natural Language Processing (NLP) and Machine Learning techniques.

The objective is to classify movie reviews as **Positive** or **Negative** based on textual content.

This project was developed as part Data Analytics Project submission.

---

## 📊 Dataset Information

- Dataset Name: IMDb 50,000 Movie Reviews
- Source: Kaggle
- Total Records: 50,000
- Type: Binary Classification (Positive / Negative)
- Balanced Dataset: 25,000 Positive & 25,000 Negative Reviews

📥 Dataset Download Link:
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

⚠️ Note:
The dataset is not included in this repository due to GitHub file size limitations (25MB max).
Please download the dataset from Kaggle and place the file:

IMDB Dataset.csv

inside the project directory before running the notebook.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- TF-IDF Vectorization
- Logistic Regression

---

## 🔎 Project Workflow

1️⃣ Data Loading  
2️⃣ Text Cleaning & Preprocessing  
   - Lowercasing  
   - Removing HTML tags  
   - Removing special characters  
   - Stopword removal  

3️⃣ Feature Engineering  
   - TF-IDF Vectorization (max_features=5000)

4️⃣ Train-Test Split (80% / 20%)

5️⃣ Model Training  
   - Logistic Regression Classifier  

6️⃣ Model Evaluation  
   - Accuracy Score  
   - Classification Report  
   - Confusion Matrix  

7️⃣ Business Insights & Interpretation  

---

## 📈 Model Performance

- Achieved Accuracy: **~87% – 90%**
- Strong precision and recall
- Balanced classification for both sentiment classes

---

## 💼 Business Applications

This model can be used for:

- Customer Review Monitoring
- OTT Platform Feedback Analysis
- Brand Sentiment Tracking
- Product Review Analysis
- Marketing Decision Support
- Early Detection of Negative Customer Experience

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install required libraries:
