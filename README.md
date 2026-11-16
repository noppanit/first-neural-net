# First Neural Net — Advertising Sales Lab

Learn machine learning **from zero**, one small pull request at a time. No previous ML experience needed.

## Learning roadmap
1. **Lesson 1:** Load and understand a CSV dataset — rows, columns, features, targets, averages, missing values.
2. **Lesson 2:** Explore graphs and learn what linear regression predicts.
3. **Lesson 3:** Build a tiny neural network with PyTorch and compare it to linear regression.

## Getting started
Install Python 3.10+, then run:
```bash
git clone https://github.com/noppanit/first-neural-net.git
cd first-neural-net
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\\Scripts\\activate
pip install -r requirements.txt
jupyter lab
```

Start in `notebooks/01_meet_the_data.ipynb`, run cells with **Shift+Enter**, and answer the exercises.

## Dataset
The included `data/Advertising.csv` is the classic 200-row Advertising sample from [ISLR-python](https://github.com/JWarmenhoven/ISLR-python/blob/master/Notebooks/Data/Advertising.csv). **TV**, **Radio**, and **Newspaper** are input features; **Sales** is the target. This is for learning, not causal measurement of ad performance.
