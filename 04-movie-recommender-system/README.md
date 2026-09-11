# Movie Recommender System

A complete introduction to collaborative filtering with movie ratings. The notebook builds
a user-user rating predictor, evaluates it on held-out ratings, recommends unseen movies,
and finds movies with similar audience patterns.

## Run it

Start Jupyter from the repository root, open `movie_recommender_system.ipynb`, and choose **Run all**. Install the dependencies first:

```bash
python -m pip install jupyter numpy pandas matplotlib seaborn scikit-learn
jupyter lab
```

The notebook reads its local ratings and movie metadata from `data/movielens/`.

## What to expect

- Runtime: usually under a minute.
- Method: memory-based collaborative filtering; no deep learning or API key is needed.
- Output: rating charts, MAE/RMSE, personalized suggestions, and an item-similarity demo.

The full dataset, code, explanations, and plots are included in this repository.
