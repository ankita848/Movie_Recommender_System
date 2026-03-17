# 🎬 Movie Recommender System

A **Content-Based Movie Recommendation System** that suggests similar movies based on movie metadata.
The system processes movie features, creates textual tags, and recommends the **top 5 similar movies** when a user selects a movie from the interface.

The project also includes a **simple web interface built using Streamlit** where users can choose a movie and see recommended movies along with their posters.

---

## 🚀 Features

* Content-based recommendation system
* Suggests **Top 5 similar movies**
* Uses **text processing and similarity comparison**
* Displays **movie posters**
* Simple **interactive UI using Streamlit**

---

## 🧠 How It Works

1. **Feature Engineering**

   * Important features such as genres, keywords, cast, and crew are combined to create a **single tag column**.

2. **Text Processing**

   * Tags are processed using **NLTK stemming** to normalize words.

3. **Vectorization**

   * The processed tags are converted into vectors using **CountVectorizer**.

4. **Similarity Calculation**

   * Cosine similarity is calculated between movie vectors to determine similarity.

5. **Recommendation**

   * When a user selects a movie, the system finds the **5 most similar movies** and displays them.

---

## 🛠 Technologies Used

* **Python**
* **Pandas & NumPy**
* **NLTK (for stemming)**
* **Scikit-learn (CountVectorizer & similarity)**
* **Streamlit (for web interface)**
* **TMDB API (for movie posters)**

---

## 💻 Web Interface

The application uses **Streamlit** to create a simple web interface where:

* Users select a movie from a dropdown menu.
* The system recommends **5 similar movies**.
* Each recommended movie is displayed with its **poster**.

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/movie-recommender-system.git
cd movie-recommender-system
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit app

```bash
streamlit run app.py
```

The app will start and open in your browser at:

```
http://localhost:8501
```

---

## Future Improvements

* Add **more recommendation filters**
* Improve UI design
* Add **search functionality**
* Deploy the project online

---

## 👩‍💻 Author

Ankita Das
