# C5710-Machine-Learning-Home-Assignment-2

NAME - Sai Swetha Manuguri #700770652 

# Question 7. Decision Tree on Iris — Depth Sweep (scikit-learn)

This repo contains a minimal experiment that trains a `DecisionTreeClassifier` on the classic **Iris** dataset, compares three tree complexities (`max_depth = 1, 2, 3`), and reports **training** and **test** accuracy. It’s a compact demo of model capacity vs. generalization (underfitting ↔ overfitting).

---

## What’s inside

- Loads the Iris dataset from `sklearn.datasets`
- Stratified train/test split (80/20) with a fixed `random_state`
- Trains decision trees with `max_depth ∈ {1,2,3}`
- Prints per-depth **train** and **test** accuracy
- Notes on how to interpret the results (signs of under/overfitting)

---

## Requirements

- Python 3.8+
- scikit-learn ≥ 1.2
- numpy ≥ 1.22

Install:
```bash
pip install scikit-learn numpy

