# Regression & Classification from Scratch

A hands-on notebook covering linear regression, logistic regression, regularization, and evaluation metrics — implemented both from scratch (NumPy) and with scikit-learn, on synthetic datasets.

## Contents

| # | Exercise | Topic | Key Techniques |
|---|----------|-------|-----------------|
| 1 | Salary Predictor | Linear Regression from scratch | Gradient descent, feature scaling, RMSE, R² |
| 2 | Feature Weights Tell a Story | Linear Regression (sklearn) | Coefficient interpretation, bar chart |
| 3 | Spam Detector | Logistic Regression from scratch | Sigmoid, binary cross-entropy, decision boundary |
| 4 | When Accuracy Lies | Imbalanced classification | Accuracy vs. precision/recall/F1, lazy baseline |
| 5 | Ridge vs Lasso Showdown | Regularization | L1 vs L2, feature selection, alpha sweep |
| 6 | ROC by Hand | Model evaluation | Manual TPR/FPR/AUC vs. `roc_auc_score` |
| 7 | Gradient Descent Tuner | Optimization | Fixed vs. decaying learning rate |

## What's inside each exercise

- **Synthetic data generation** using `numpy.random.default_rng` for reproducibility
- **From-scratch implementations** of gradient descent for both linear and logistic regression
- **Evaluation**: RMSE, R², precision, recall, F1, confusion matrices, ROC/AUC
- **Visualizations**: loss curves, actual-vs-predicted plots, decision boundaries, ROC curves, regularization paths

## Requirements

```bash
pip install numpy matplotlib scikit-learn
```

## Usage

Open `Regression.ipynb` in Jupyter Notebook, JupyterLab, Google Colab, or VS Code, and run all cells top to bottom. Each exercise is self-contained — you can also run sections independently.

## Notes

- All datasets are synthetically generated, so results are fully reproducible (fixed random seeds).
- Exercise 6's manual AUC calculation includes the ROC curve's boundary points (0,0) and (1,1) to match `sklearn.metrics.roc_auc_score`.
- Exercise 5 sweeps `alpha = [0.001, 0.01, 0.1, 1, 10]` for Ridge and Lasso; check the printed "zero weights" table to see at which alpha Lasso approaches the true number of informative features.

## License

Add a license of your choice (e.g., MIT) if you plan to share this publicly.
