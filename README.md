# 📰 Fake News Detection Project

## 📌 Project Overview
This project leverages Natural Language Processing (NLP) and Machine Learning to automatically identify whether a news article is real or fake. In an era where misinformation spreads rapidly, this tool provides an automated way to verify the authenticity of textual content by analyzing linguistic patterns.

---

## 🚀 Features

### 🧹 Text Preprocessing
- Cleaning raw data by removing stopwords, punctuation, and performing stemming/lemmatization to normalize text.

### 🔢 Vectorization
- Converting text into numerical data using techniques like:
  - TF-IDF
  - CountVectorizer

### 🤖 Multiple Classifiers
Implementation and comparison of various machine learning algorithms:
- Logistic Regression  
- Naive Bayes  
- Passive Aggressive Classifier  

### 📊 Performance Metrics
Detailed evaluation using:
- Accuracy  
- Precision  
- Recall  
- F1-score  

to ensure model reliability.

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, NLTK, Matplotlib, Seaborn  
- **Tools:** Jupyter Notebook / Google Colab  

---

## 📂 Dataset

The project utilizes the **Fake and Real News Dataset** (commonly sourced from Kaggle), which consists of:

- **True.csv:** Contains authentic news articles from reputable sources.  
- **Fake.csv:** Contains fabricated or misleading news articles.  

---

## ⚙️ Installation & Usage

### 1. Clone the repository:
```bash
git clone https://github.com
cd Fake-News-Detection
```
2. Install dependencies:
   ```
   pip install pandas numpy scikit-learn nltk matplotlib seaborn
   ```
3. Run the project:
Open the Jupyter Notebook and run all cells:
```
jupyter notebook Fake_News_Detection.ipynb
```
