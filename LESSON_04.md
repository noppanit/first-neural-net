# Lesson 4 — Full model comparison

This lesson combines everything you have learned:

1. Load and explore the Advertising CSV.
2. Split data into training (120 rows), validation (40), and test (40).
3. Standardize inputs using *training data only*.
4. Train **linear regression** as a simple baseline.
5. Train a **PyTorch neural network** with ReLU, Adam and early stopping.
6. Compare both models with a mean-only baseline using MAE, RMSE and R² on the same held-out test data.
7. Plot training curves, actual vs predicted values, and write your own conclusion.

Start with `notebooks/04_full_model_comparison.ipynb`.

Keep in mind: 200 rows is small, so a neural network is not guaranteed to win. The point is learning a sound and reproducible workflow.
