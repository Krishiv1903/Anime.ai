# 🎌 Anime Intelligence Dashboard
🔗 Live Demo: https://anime-ai-7nfw.onrender.com/

An **AI-powered anime recommendation system** that analyzes user-input genres to
**predict anime quality** and **recommend similar anime** using Machine Learning.

Built with **Flask + TF-IDF + Logistic Regression**, designed with a **modern cyberpunk UI**.

---

## 🚀 Features

* 🎯 **Genre-Based Anime Recommendations**
* 🧠 **Anime Quality Prediction** (Good / Low Rated)
* 📊 **Match Confidence Score**
* 🎥 **Supports Movie & TV Anime**
* ⚡ **Fast similarity search using TF-IDF + Cosine Similarity**
* 🎨 **Modern Tailwind-based dashboard UI**

---

## 🧠 How It Works

### 1️⃣ User Input

* User enters genres (comma-separated)
* Example: `Action, Romance, Sci-Fi`

### 2️⃣ Machine Learning Pipeline

* **TF-IDF Vectorizer** converts genres into vectors
* **Cosine Similarity** finds similar anime
* **Logistic Regression** predicts anime quality

### 3️⃣ Output

* 🏆 Best matching anime
* 📈 Quality prediction with confidence
* 🎬 Full anime details (name, type, rating, episodes)

---

## 🗂️ Project Structure

```
ANIMERECOMMENDATOR/
│
├── templates/
│   ├── index.html          # Genre input page
│   └── index_output.html   # Results dashboard
│
├── anime.csv               # Anime dataset
├── app.py                  # Flask backend
├── logistic_model.pkl      # Trained quality prediction model
├── tfidf_vectorizer.pkl    # TF-IDF vectorizer
├── __pycache__/            # Python cache
```

---

## 🛠️ Tech Stack

### 🔹 Backend

* Python
* Flask
* Pandas
* Scikit-learn
* Joblib

### 🔹 Machine Learning

* TF-IDF Vectorization
* Logistic Regression
* Cosine Similarity

### 🔹 Frontend

* HTML
* Tailwind CSS
* JavaScript
* Jinja2 Templates

---

## 📊 Machine Learning Details

### 🎯 Quality Prediction

* **Target**: High-rated vs Low-rated anime
* **Threshold**: Rating ≥ 7.5 → Good Anime
* **Model**: Logistic Regression

### 🔍 Recommendation Engine

* Uses **genre similarity**
* TF-IDF vectors + cosine similarity
* Top-10 most similar anime returned

---

## ▶️ How to Run Locally

### 1️⃣ Install dependencies

```bash
pip install flask pandas scikit-learn joblib nltk
```

### 2️⃣ Run the Flask app

```bash
python app.py
```

### 3️⃣ Open in browser

```
http://127.0.0.1:5000
```

### 4️⃣ Live at

```
https://anime-ai-7nfw.onrender.com/
```

---

## 🧪 Example Input

```
Action, Adventure, Fantasy
```

### Example Output

* **Predicted Quality**: Good Anime
* **Confidence**: 88.4%
* **Top Recommendation**: Fullmetal Alchemist: Brotherhood

---

## 🎨 UI Preview (Concept)

* Cyberpunk-themed dashboard
* Animated confidence indicators
* Responsive card-based layout
* Clean typography & icons

---

## 🔒 Session Handling

* Uses Flask sessions to persist results
* Secure `SECRET_KEY` for session encryption

---

## 📌 Future Improvements

* 🔍 Search by anime name
* ⭐ User rating filters
* 🎭 Genre weighting
* 📈 Advanced recommendation ranking
* ☁️ Cloud deployment (Render / Railway)

---

## 👨‍💻 Author

**Krishiv Goyal**
Computer Engineering Student
AI • ML • Full-Stack Development

---

## ⭐ If you like this project

Give it a ⭐ on GitHub — it helps a lot!

---
