# IPL Score Prediction

A beginner deep-learning regression notebook that estimates a first-innings IPL total from the current score, wickets, recent form, teams, and venue.

## Run it

Open [`ipl_score_prediction.ipynb`](ipl_score_prediction.ipynb) from the repository root and select **Run all**. The approximately 9 MB CSV is included at `data/ipl_matches.csv`.

The notebook deliberately splits by match ID, not by row, so a match cannot leak into both train and test data.

## Data and attribution

The full dataset, code, and explanations are included in this repository. Historical model output is for learning only, not betting advice.
