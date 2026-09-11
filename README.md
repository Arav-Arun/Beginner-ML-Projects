# Coffee with CodeCell AI and ML Starter Projects

These are complete, beginner-friendly notebooks for learning the basic machine-learning workflow: load data, inspect it, prepare features, train a model, evaluate it, and try a prediction.

## Projects

| #   | Project                                                          | What you learn                                       |
| --- | ---------------------------------------------------------------- | ---------------------------------------------------- |
| 1   | [Spam email classifier](01-spam-email-classifier/)               | Text cleaning, vectorization, binary classification  |
| 2   | [Handwritten digit classifier](02-handwritten-digit-classifier/) | Image pixels, neural networks, multiclass evaluation |
| 3   | [Twitter sentiment analysis](03-twitter-sentiment-analysis/)     | Social-text cleaning, TF-IDF, sentiment labels       |
| 4   | [Movie recommender system](04-movie-recommender-system/)         | Similarity, user-item data, recommendations          |
| 5   | [IPL score prediction](05-ipl-score-prediction/)                 | Regression, categorical features, error metrics      |
| 6   | [Cat vs dog classifier](06-cat-vs-dog-classifier/)               | CNNs, image batches, training curves                 |
| 7   | [Flipkart review sentiment](07-flipkart-review-sentiment/)       | Review cleaning, TF-IDF, confusion matrices          |

## Run a notebook

Run Jupyter from the repository root so every notebook can find the included `data/` folder:

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter lab
```

Open any project notebook and choose **Run all**. For a hosted notebook environment, upload or clone the complete repository first, then set its working directory to the repository root.

## Suggested live-demo path

Start with handwritten digits for an immediate visual result, show spam classification to explain supervised learning, then open either the recommender or IPL notebook to show that ML is useful beyond classification.
