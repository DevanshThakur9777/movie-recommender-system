#  Movie Recommendation System (Content-Based Filtering)

##  Project Overview
This project is a Content-Based Movie Recommendation System built using the TMDB 5000 Movies dataset.  
It recommends movies based on similarity between movie features such as genres, keywords, cast, and crew.

The goal of this project is to help users discover similar movies based on a given movie title.

---

##  Dataset Used
- TMDB 5000 Movies Dataset
- TMDB 5000 Credits Dataset

Both datasets are merged to extract important features like:
- Genres
- Keywords
- Cast
- Crew
- Movie metadata

---

##  How It Works

1. Data Preprocessing:
   - Merging movies and credits datasets
   - Extracting useful fields from JSON-like data

2. Feature Engineering:
   - Combining genres, keywords, cast, and crew into a single feature set

3. Model Building:
   - Creating a similarity matrix between movies
   - Finding top similar movies using similarity scores

4. Recommendation:
   - Input a movie name
   - Output top 5 similar movies

---

##  Example

**Input:**
Batman Begins

**Output:**
- The Dark Knight  
- The Dark Knight Rises  
- Batman v Superman: Dawn of Justice  
- The Prestige  
- Man of Steel  

---

##  Model Evaluation

The model was evaluated using Precision@K metric:

- Precision@5 = 0.8

This means 80% of recommended movies were relevant to the input movie.

---

## 🛠 Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab

---

##  Key Features
- Content-based recommendation system
- Uses movie metadata for similarity
- Fast and efficient recommendations
- Simple and scalable ML pipeline

---

##  Future Improvements
- TF-IDF based vectorization for better accuracy
- Deep learning-based embeddings (NLP models)
- Web app using Streamlit
- Hybrid recommendation system (Content + Collaborative filtering)

---

##  Author
This project was built as part of an AI/ML learning journey to understand recommendation systems and practical machine learning workflows.

---

##  Result
A working recommendation system that suggests similar movies with good accuracy and real-world applicability.
