
# 🎥 Movie Recommender System

Welcome to the Movie Recommender System! This project is designed to provide personalized movie recommendations based on user input. By selecting a movie, users can receive a curated list of similar movies, complete with posters, details, and trailers.

## ✨ Features
- **Movie Selection**: Choose a movie from a dropdown menu to get tailored recommendations.
- **Personalized Recommendations**: Receive a list of six similar movies based on the selected title.
- **Movie Posters**: Visualize each recommended movie through its poster.
- **Detailed Info**: View a summary and cast details for the recommended movies.
- **Trailers**: Watch trailers directly within the app.

## 🚀 Live Demo
Check out the live demo of the app here.

## 🛠️ Installation
To run the Movie Recommender System locally, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/midhun24122002/movierecommendersystem.git
    cd movierecommendersystem
    ```

2. **Install dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Download required data**:

    Ensure you have `movie_list.pkl` and `similarity.pkl` files in the project directory.
    You can download the `similarity.pkl` file here.

4. **Run the app**:

    ```bash
    streamlit run app.py
    ```

## 🎬 Usage
- Open your web browser and navigate to `http://localhost:8501`.
- Select a movie from the dropdown menu.
- Discover personalized recommendations with movie posters, details, and trailers.

## 🧑‍💻 Code Overview

### app.py
This is the main file for the Streamlit web app, which handles:
- **Fetching Movie Posters**: Utilizes the TMDb API to display movie posters.
- **Generating Recommendations**: Calculates movie similarity and provides recommendations.
- **Fetching Trailers**: Retrieves YouTube trailers using the TMDb API.
- **User Interface**: Displays the movie selection, recommendations, and related details in a user-friendly manner.

### movie_recommendation_code.ipynb
This Jupyter notebook contains the code used for data preprocessing, computing movie similarities, and generating the `.pkl` files used by the Streamlit app.

## 📄 License
This project is licensed under the MIT License.

## 🙌 Acknowledgments
- Movie data is provided by The Movie Database (TMDb).
- Thanks to Streamlit for the easy-to-use web application framework.

## 📧 Contact
For any questions or feedback, feel free to open an issue or contact via email: arrammidhun2002@gmail.com.
