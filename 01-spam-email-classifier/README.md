# Spam Email Classifier

A complete TensorFlow project that learns to label an email as **spam** or **ham** (not spam). It includes preparation, exploration, training, evaluation, and prediction in one runnable Google Colab notebook.

## Run it

1. Start Jupyter from the repository root.
2. Open [`spam_email_classifier.ipynb`](spam_email_classifier.ipynb).
3. Choose **Run all** so it can read `data/spam_emails.csv`.

For a local environment, install:

```bash
python -m pip install tensorflow pandas numpy scikit-learn matplotlib
```

## What you will build

- A class-distribution plot
- Reproducible train, validation, and test splits
- A `TextVectorization` vocabulary learned from training text only
- An embedding-based neural network
- Accuracy, precision, recall, F1, a confusion matrix, and learning curves
- A helper that predicts spam probability for new text

The notebook contains the complete workflow; tune its training settings after establishing this reproducible baseline.

## Data and reference

The full dataset, code, and explanations are included in this repository. The notebook reads the CSV from `data/spam_emails.csv` and never downloads data at runtime.

## Scope

This is a classroom demo, not a production spam filter. Real filters need more representative data, adversarial testing, privacy review, monitoring, and careful threshold selection.
