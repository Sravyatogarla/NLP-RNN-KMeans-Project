# NLP-RNN-KMeans-Project

#  NLP Projects: IMDB Sentiment Classification & BBC News Clustering

This repository contains two end-to-end Natural Language Processing (NLP) mini-projects implemented using Deep Learning and Machine Learning techniques. Both projects are focused on real-world text datasets to demonstrate text classification and clustering.

---

## 📘 Project 1: IMDB Movie Review Sentiment Classification

### 🔍 Objective:
Build a sentiment analysis model that classifies IMDB movie reviews as **positive** or **negative** using a **Recurrent Neural Network (RNN)**.

### 🛠️ Key Steps:
- Used TensorFlow Datasets (`imdb_reviews`)
- Preprocessed text using `TextVectorization`
- Built an RNN model with embedding and recurrent layers
- Trained on 25,000 reviews, validated on 25,000
- Predicted sentiment of custom input reviews

---

## 📰 Project 2: BBC News Articles Clustering

### 🔍 Objective:
Perform topic clustering on BBC News article summaries using 3 vectorization methods and evaluate the clustering effectiveness.
---
## 📂 Folder Structure

NLP-Projects/

├── NLP_Project_IMDB_BBC.ipynb # Final combined notebook

├── BBC_News_Articles/ # Folder with 5 subfolders (news categories)

├── README.md

├── requirements.txt (optional)

└── BBCNewsArticlesClustered.csv # Clustered output

---

### 🛠️ Key Steps:
- Loaded `.txt` articles from 5 news categories
- Cleaned and preprocessed the text
- Applied:
  - **Presence/Absence Vectorization**
  - **Count Vectorization**
  - **TF-IDF Vectorization**
- Clustered using **KMeans (k=5)**
- Evaluated with **Silhouette Score**
- Saved clustered data to CSV

---

## 🧪 Tools & Technologies
- Python  
- TensorFlow / Keras  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## ✅ Final Conclusion

This project demonstrates the practical application of Deep Learning and NLP in real-world problems like sentiment classification and topic modeling.  
- **IMDB sentiment model** achieved good accuracy using a simple RNN and vectorization pipeline.  
- **BBC news clustering** revealed that **TF-IDF** vectorization performed best in grouping semantically similar documents based on Silhouette Score.

These experiments emphasize the value of both traditional and deep learning methods in Natural Language Processing workflows.

---

## 🙋‍♀️ Author

**Sravya Togarla**  
Data Science Learner | Edureka Certified  
🌐 GitHub: [Sravyatogarla](https://github.com/Sravyatogarla)  
🔗 LinkedIn: [Sravya Togarla](https://www.linkedin.com/in/sravya-togarla)

---

## 🎓 Project Context

This project was completed as part of the **Edureka Data Science with SQL Certification Course**, where we practiced hands-on learning across Python, Machine Learning, Deep Learning, NLP, and more.

---


