<div align="center">

# 🎬 Movie Recommendation System

**An AI-Powered Intelligent Movie Suggestion Platform**

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge\&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?style=for-the-badge\&logo=streamlit)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-AI-green?style=for-the-badge)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

</div>

<br />

## 📖 Project Description

The **Movie Recommendation System** is an intelligent information filtering system that suggests movies based on user preferences, similarity between movies, and predicted ratings.

This project combines **Content-Based Filtering** and **Collaborative Filtering** techniques to deliver accurate and personalized movie recommendations. It also provides an interactive web interface using Streamlit for real-time user interaction.

Inspired by real-world systems used by platforms like Netflix, Amazon, and YouTube, this project demonstrates how recommendation engines enhance user experience and engagement. 

---

## ✨ Features

* 🎯 **Content-Based Recommendation**
  Suggests movies similar to a given movie using metadata like cast, genres, and keywords.

* 🤝 **Collaborative Filtering**
  Predicts user ratings using a trained SVD (Singular Value Decomposition) model.

* 🎥 **Interactive UI**
  Built with Streamlit for a simple and user-friendly interface.

* 📊 **Real-Time Predictions**
  Provides instant movie recommendations and predicted ratings.

* 🧠 **Machine Learning Integration**
  Uses cosine similarity and SVD for intelligent recommendations.

* ⚡ **Efficient Processing**
  Handles large datasets and computes recommendations dynamically.

---

## 🛠️ Tech Stack

* **Language:** Python
* **Frontend/UI:** Streamlit
* **Libraries & Tools:**

  * NumPy
  * Pandas
  * Scikit-learn
  * Surprise (SVD Model)
  * Pickle
  * Requests

---

## 🚀 Installation & Setup

### 📌 Prerequisites

* Python 3.x
* pip (Python package manager)

---

### ⚙️ Steps

1. **Clone the repository**

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the application**

```bash
streamlit run app.py
```

4. **Open in browser**

Go to:
👉 http://localhost:8501

---

## 💻 Usage

* Enter a movie name in the input field.
* Rate the movie using the slider.
* Click on **"Recommend"**.
* Get:

  * 🎬 Similar movie recommendations
  * ⭐ Predicted rating using collaborative filtering

---

## 📂 Project Structure

```bash
movie-recommendation-system/
├── app.py                      # Streamlit application
├── MovieRecommendationSystem.ipynb  # Model development notebook
├── datasets/                  # Movie datasets
├── surprise_model.pkl         # Trained SVD model
├── LICENSE                    # License file
├── README.md                  # Project documentation
```

---

## 🧠 How It Works

### 🔹 Content-Based Filtering

* Uses metadata like:

  * Cast
  * Director
  * Genres
  * Keywords
* Converts them into text features
* Applies **Count Vectorizer + Cosine Similarity**
* Recommends similar movies

### 🔹 Collaborative Filtering

* Uses **SVD (Singular Value Decomposition)**
* Learns user preferences from ratings
* Predicts ratings for unseen movies

---

## 📊 Datasets

* **TMDB Movie Metadata (~5,000 movies)**
* **Movies Dataset (~45,000 movies, 26M ratings)**

These datasets provide rich information like movie details, ratings, and user interactions. 

---

## 🔮 Future Improvements

* 🎯 Personalized user login system
* 🌐 Deploy on cloud (Streamlit Cloud / AWS)
* 📈 Improve recommendation accuracy
* 🎥 Add movie posters and trailers
* ⚡ Optimize performance for large-scale systems

---

## 📜 License

This project is licensed under the **MIT License**.

---

<div align="center">

⭐ *If you like this project, consider giving it a star!*

</div>
