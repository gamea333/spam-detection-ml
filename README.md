# spam-detection-ml

Multilingual spam detection model that classifies text as **Spam** or **Ham** (not spam) across English, French, and German.

## Objective

Train a machine learning model to accurately classify text data from three languages — English, French, and German — using the provided dataset and text features.

## Dataset

| File | Description |
|------|-------------|
| `Task_1.csv` | Labeled text samples across English, French, and German |

Labels: `spam` / `ham`

## Notebook

All preprocessing, training, and evaluation is in `spam-detection.ipynb` (Google Colab).

### Pipeline

1. **Data Loading** — Load and inspect `Task_1.csv`
2. **Preprocessing** — Tokenization, stopword removal, TF-IDF vectorization
3. **Multilingual Handling** — Language-agnostic feature extraction
4. **Model Training** — Classification model (Naive Bayes / Logistic Regression / SVM)
5. **Evaluation** — Accuracy, precision, recall, F1-score

## Getting Started

### Run in Colab

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

1. Upload `Task_1.csv` to your Colab session
2. Open `spam-detection.ipynb`
3. Run all cells

### Run Locally

```bash
pip install pandas scikit-learn numpy matplotlib seaborn
jupyter notebook spam-detection.ipynb
```

## Tech Stack

- **Language:** Python
- **Libraries:** scikit-learn, pandas, numpy
- **Environment:** Google Colab / Jupyter Notebook
- **Task:** Binary text classification (Spam vs Ham)

## Results

| Metric | Score |
|--------|-------|
| Accuracy | — |
| Precision | — |
| Recall | — |
| F1-Score | — |

> Fill in your model's evaluation scores after running the notebook.

