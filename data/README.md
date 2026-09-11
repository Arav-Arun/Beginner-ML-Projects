# Local project data

Every notebook in this repository reads its dataset from this folder. No notebook downloads data at runtime.

- `spam_emails.csv` — email text and spam/ham labels
- `twitter_sentiment.csv` — labeled social-post sentiment examples
- `movielens/` — local ratings (`ratings.csv`) and movie metadata (`movies.csv`) used by the recommender
- `ipl_matches.csv` — ball-by-ball first-innings score records
- `flipkart_reviews.csv` — product reviews and ratings

Note: The handwritten digit and cat vs dog classifiers load standard MNIST and CIFAR-10 datasets directly via TensorFlow/Keras.

Run a notebook from the repository root, or from its project folder, and data paths will resolve automatically.
