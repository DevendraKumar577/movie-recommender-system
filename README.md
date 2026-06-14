#  Movie Recommendation System

A content-based Movie Recommendation System built using Python, Pandas, Scikit-Learn, and Streamlit. The application recommends similar movies based on movie features and displays movie posters using the TMDB API.

##  Live Demo

🔗 https://movie-recommender-system-devash.streamlit.app/

##  Features

- Movie search through dropdown menu
- Content-based recommendation engine
- Top 5 similar movie recommendations
- Movie poster fetching using TMDB API
- Interactive web interface built with Streamlit

##  Tech Stack

- Python
- Pandas
- NumPy
- Scikit-Learn
- Streamlit
- TMDB API
- Pickle

##  Project Structure

```text
movie-recommender-system/
│
├── app.py
├── movie_list.pkl
├── similarity.pkl
├── requirements.txt
├── README.md
```

##  Installation

Clone the repository:

```bash
git clone https://github.com/Devendrakumar577/movie-recommender-system.git
```

Move into the project directory:

```bash
cd movie-recommender-system
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

##  How It Works

1. Movie metadata is processed and transformed into feature vectors.
2. Cosine similarity is calculated between movies.
3. When a user selects a movie, the system finds the most similar movies.
4. Recommended movie posters are fetched from the TMDB API and displayed.

##  Sample Output

- Select a movie from the dropdown.
- Click **Show Recommendation**.
- View the top 5 recommended movies along with their posters.

##  Future Improvements

- Hybrid recommendation system
- User authentication
- Movie ratings and reviews
- Search by genre, actor, or director
- Personalized recommendations

##  Author

**Devendra Kumar**

- GitHub: https://github.com/Devendrakumar577
