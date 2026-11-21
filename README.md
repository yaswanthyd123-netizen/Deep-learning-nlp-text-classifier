# Deep Learning / NLP Text Classifier with PyTorch

A beginner-friendly sentiment analysis project that classifies text as **positive** or **negative**.

## Files
- `Deep_Learning_NLP_Text_Classifier.ipynb` — complete Jupyter Notebook, including preprocessing, training, evaluation, convergence plots, confidence scores, and model saving.
- `sentiment_dataset.csv` — small labelled sample dataset included for an offline demonstration.
- `requirements.txt` — Python dependencies.

## Run locally
1. Install Python 3.10+ and Jupyter Notebook (or use Google Colab).
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `Deep_Learning_NLP_Text_Classifier.ipynb`.
4. Run all cells from top to bottom. Keep the CSV in the same folder as the notebook.

## GitHub upload
1. Create a new **public** GitHub repository (example name: `deep-learning-nlp-text-classifier`).
2. Add the three files from this folder.
3. Commit with a message such as `Add PyTorch NLP sentiment classifier`.
4. Copy the repository URL and submit that public link as the deliverable.

## Notes
The included dataset is small and intended to make the project reproducible without downloading data. It is a demonstration dataset, not a benchmark. For stronger real-world performance, replace it with a larger labelled dataset and document its source.


## Additional generated folders
- `outputs/` — training curves, confusion matrix, evaluation report, and sample predictions.
- `models/` — trained PyTorch checkpoint and fitted TF-IDF vectorizer.
- `screenshots/` — result figures for easy viewing in the GitHub repository (these are figures, not screenshots of the notebook interface).

The saved model artifacts were generated using the included sample dataset. Run the notebook from top to bottom to reproduce the results.
