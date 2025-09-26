<h1 align="center">🧠 Machine Learning for Sentiment Analysis of Online Comments</h1>

<p align="center">
</p>

---

## 📑 Table of Contents
- [Introduction](#-introduction)
- [Methodology](#-methodology)
- [System Workflow](#-system-workflow)
- [Results](#-results)
- [How to Run](#-how-to-run)
- [References](#-references)

**READ DETAIL OF REPORT**  
[https://github.com/huulooc/Sentimance-anaytics/blob/main/report_final.pdf](https://github.com/huulooc/Sentimance-anaytics/blob/main/report_final.pdf)

---

## 📌 Introduction
This project was developed as part of the course **Interdisciplinary Research Methods (Course code: 231PP0801)** at the University of Economics and Law, Faculty of Information Systems.  
The main goal is to **apply and compare Machine Learning models** to analyze customer sentiment in e-commerce comments, thereby supporting businesses in understanding customer behavior and improving decision-making.

---

## 🛠️ Methodology
The project applied **three algorithms** for sentiment classification:
- **Support Vector Machine (SVM)**
- **Decision Tree Classifier**
- **Multinomial Naive Bayes (MultinomialNB)**

Data preprocessing steps:
- Removing special characters, stopwords, emojis, slang, misspellings  
- Normalizing text (lowercasing, handling diacritics, token standardization)  
- Feature extraction with **TF-IDF**  

---

## 🔄 System Workflow
<p align="center">
</p>

Steps:
1. **Data Collection** → Customer comments from e-commerce & social media  
2. **Preprocessing** → Cleaning, tokenization, normalization  
3. **Feature Extraction** → TF-IDF  
4. **Model Training** → SVM, Decision Tree, MultinomialNB  
5. **Evaluation & Visualization** → Accuracy, Precision, Recall, F1-score  

---

## 📊 Results
<p align="center">
</p>

- **SVM**: Best performance (~93% accuracy with 5-fold CV)  
- **MultinomialNB**: Stable (~90% accuracy)  
- **Decision Tree**: Overfitting issues, weaker generalization  

➡️ Final chosen model: **LinearSVC (variant of SVM)**  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
