#  Movie Recommender System

This project builds a **Movie Recommender System** using **Collaborative Filtering** with the **SVD (Singular Value Decomposition)** algorithm from the `scikit-surprise` library. It predicts user preferences for movies based on historical ratings data.

##  Features

- Collaborative Filtering using SVD
- Data preprocessing (label encoding, genre vectorization)
- Movie recommendations for individual users
- Evaluation using RMSE

##  Technologies Used

- Python
- Pandas
- Scikit-learn
- Surprise Library
- Jupyter Notebook

##  Dataset

The project uses two datasets:

- `ratings.csv`: Contains user ratings for movies (`movieId`, `rating`)
- `movies.csv`: Contains movie metadata including genres

##  Usage

1. Clone the repository or download the notebook.
2. Place `ratings.csv` and `movies.csv` in the same directory.
3. Run the notebook step by step.

##  Evaluation

The system uses **Root Mean Square Error (RMSE)** to evaluate prediction accuracy.

##  Future Enhancements

- Add content-based filtering
- Build a web interface with Streamlit or Flask
- Incorporate user feedback to improve recommendations
