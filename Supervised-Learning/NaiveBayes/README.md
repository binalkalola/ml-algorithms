# Naive Bayes — Exercises

This repository contains solved exercises exploring the **Naive Bayes** algorithm, a supervised learning technique used for classification. Each exercise includes a written explanation followed by a Python implementation using `scikit-learn` and `numpy`.

## 📌 Topics Covered

| # | Exercise | Concepts |
|---|----------|----------|
| 1 | Bayes by Counting | Manual Bayes' theorem calculation, posterior probability |
| 2 | Compare the Three Flavours | GaussianNB vs BernoulliNB, 5-fold cross-validation |
| 3 | Build a Fruit Classifier | Gaussian Naive Bayes implemented from scratch, decision regions |
| 4 | Spam Filter 2.0 | CountVectorizer + MultinomialNB, Laplace smoothing (alpha tuning) |
| 5 | Imbalance Lab | Class imbalance, custom priors, precision/recall/F1 trade-offs |
| 6 | Correlated Features Trap | Feature independence assumption, GaussianNB vs Logistic Regression |
| 7 | Amazon Review Classifier | TF-IDF + MultinomialNB, GridSearchCV hyperparameter tuning |

## 🛠️ Tech Stack

- Python 3
- NumPy
- Pandas
- scikit-learn
- Matplotlib

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/ML-Algorithms.git
   ```
2. Navigate to this folder:
   ```bash
   cd ML-Algorithms/Naive-Bayes
   ```
3. Install dependencies:
   ```bash
   pip install numpy pandas scikit-learn matplotlib
   ```
4. Open the notebook:
   ```bash
   jupyter notebook NaiveBayes_exercises.ipynb
   ```

## 📖 About Naive Bayes

Naive Bayes is a **supervised classification algorithm** based on Bayes' theorem, with a "naive" assumption that all features are conditionally independent given the class label. Despite this simplifying assumption, it performs well in practice — especially for text classification tasks like spam detection and sentiment analysis.

Common variants:
- **GaussianNB** — for continuous features (assumes normal distribution)
- **MultinomialNB** — for discrete/count features (e.g. word counts)
- **BernoulliNB** — for binary/boolean features

## 📄 License

Free to use for learning and reference purposes.
