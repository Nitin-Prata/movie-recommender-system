# 🎬 Movie Recommender System

A Content-Based Movie Recommendation System built using Machine Learning with scikit-learn and IMDB dataset, deployed on Streamlit. This project suggests movies based on the user's favorite movie by analyzing movie similarities.



## ✨ Features

- 🎞️ Recommends top 5 movies based on the selected movie.
- 🎭 Fetches movie posters dynamically from **TMDb API**.
- 🧩 Built using **Content-Based Filtering** ML algorithm.
- ⚡ Fast and interactive web interface with **Streamlit**.
- 🎯 Uses **cosine similarity** for precise recommendations.
- 🌟 Lightweight and easy to deploy.

---

## 🔧 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/movie-recommender-system.git
cd movie-recommender-system
```

### 2. Create and Activate Virtual Environment
```bash
python -m venv venv
venv\\Scripts\\activate  # For Windows
# Or
source venv/bin/activate   # For macOS/Linux
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Application
```bash
streamlit run app.py
```

---

## 💡 How It Works

1. Data Preprocessing:
   - IMDB dataset processed for relevant features.
   - Feature extraction of genres, keywords, cast, and crew.

2. Content-Based Filtering:
   - Uses **cosine similarity** to measure how similar two movies are.
   - Recommends movies based on the closest match.

3. Poster Fetching:
   - Utilizes TMDb API to dynamically fetch posters of recommended movies.

4. Interactive UI:
   - User selects a movie from dropdown; top 5 similar movies are shown with posters.

---

## ⚡ Tech Stack

- Frontend: Streamlit
- Backend: Python
- Machine Learning: scikit-learn (cosine similarity)
- API: The Movie Database (TMDb) API
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - pickle
  - requests
  - streamlit


## 📈 Results

- ✅ Provides top 5 accurate movie recommendations.
- 🎯 Fetches high-quality movie posters via TMDb API.
- ⚡ Real-time recommendations with Streamlit interface.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

### 📝 How to Contribute
- Fork the repository
- Create your feature branch: `git checkout -b feature/YourFeature`
- Commit your changes: `git commit -m 'Add some feature'`
- Push to the branch: `git push origin feature/YourFeature`
- Open a pull request

---

## 📩 Contact

🔗 Nitin Pratap Singh 
📧 nitinpratap997@gmail.com  

---

⭐ If you like this project, give it a star! ⭐

🚀 Happy Coding! 🚀

