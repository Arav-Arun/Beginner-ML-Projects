# Twitter Sentiment Analysis

A beginner-friendly notebook that classifies short posts as **positive** or **negative**.
It covers text cleaning, TF-IDF features, logistic regression, evaluation, feature inspection,
and predictions on new text.

## Run it

Start Jupyter from the repository root, open `twitter_sentiment_analysis.ipynb`, and choose **Run all**. Install the required dependencies first:

```bash
python -m pip install jupyter numpy pandas matplotlib seaborn scikit-learn
jupyter lab
```

The notebook reads the included `data/twitter_sentiment.csv` file. It does not need a social-media API, credentials, or a runtime download.

## What to expect

- Runtime: usually under a minute after the dataset is available.
- Task: binary sentiment only; neutral and mixed opinions are outside this demo.
- Output: accuracy metrics, a confusion matrix, an influential-words plot, and prediction examples.

The full dataset, code, explanations, and generated plots are included in this repository.
