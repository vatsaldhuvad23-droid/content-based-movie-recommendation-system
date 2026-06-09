# content-based-movie-recommendation-system
A Content-Based Movie Recommendation System built with Python, Pandas, Scikit-learn, TF-IDF Vectorization, and Cosine Similarity that recommends similar movies based on genres, keywords, cast, director, and taglines.
# 🎬 Movie Recommendation System

A Machine Learning-based Movie Recommendation System that suggests similar movies using Content-Based Filtering. The project analyzes movie metadata such as genres, keywords, cast, director, and taglines, then uses TF-IDF Vectorization and Cosine Similarity to recommend movies related to a user's favorite movie.

---

## 📌 Overview

This project recommends movies based on their content rather than user ratings. By comparing textual features from movie metadata, the system identifies movies that are most similar to the selected movie.

The recommendation process includes:

- Data preprocessing
- Feature engineering
- TF-IDF vectorization
- Cosine similarity calculation
- Fuzzy movie title matching

---

## 🚀 Features

✅ Content-based movie recommendation

✅ Handles spelling mistakes using Difflib

✅ Uses multiple movie attributes for recommendations

✅ Fast similarity computation with Scikit-learn

✅ Simple command-line interface

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Difflib

---

## 📂 Dataset

The dataset contains movie information such as:

- Title
- Genres
- Keywords
- Tagline
- Cast
- Director

Dataset file:

```text
movies.csv
```

---

## ⚙️ How It Works

### 1. Load Dataset

Movie data is loaded using Pandas.

### 2. Data Preprocessing

- Select important features
- Handle missing values
- Combine features into a single text column

Selected Features:

- genres
- keywords
- tagline
- cast
- director

### 3. Feature Extraction

TF-IDF Vectorizer converts textual movie information into numerical vectors.

### 4. Similarity Calculation

Cosine Similarity measures how similar each movie is to every other movie.

### 5. Recommendation Generation

- User enters a movie name
- Difflib finds the closest matching movie title
- System returns the most similar movies

---

## 📁 Project Structure

```text
movie-recommendation-system/
│
├── movie_recommendation.py
├── movies.csv
├── requirements.txt
├── README.md
├── .gitignore
├── LICENSE
```

---

## ▶️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
```

### Navigate to Project Folder

```bash
cd movie-recommendation-system
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Run the Project

```bash
python movie_recommendation.py
```

---

## 📊 Example

Input:

```text
Enter your favourite movie name: Avatar
```

Output:

```text
Movies suggested for you :

1. Guardians of the Galaxy
2. Star Trek
3. John Carter
4. Alien
5. Interstellar
...
```

---

## 🎯 Future Enhancements

- Streamlit Web Application
- Movie Poster Integration
- TMDB API Integration
- Hybrid Recommendation System
- Personalized Recommendations

---

## 📚 Skills Demonstrated

- Data Preprocessing
- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Cosine Similarity
- Content-Based Recommendation Systems
- Python Programming
- Machine Learning Fundamentals

---

## 👨‍💻 Author

**Vatsal Dhuvad**

LinkedIn: https://www.linkedin.com/in/vatsal-dhuvad-7630482b2/
