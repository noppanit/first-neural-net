# First Neural Net — Advertising Sales Lab

Learn machine learning **from zero**, one small pull request at a time. No previous ML experience needed.

## Learning roadmap
1. **Lesson 1:** Load and understand a CSV dataset — rows, columns, features, targets, averages, missing values.
2. **Lesson 2:** Explore graphs and learn what linear regression predicts.
3. **Lesson 3:** Build a tiny neural network with PyTorch and compare it to linear regression.

## Getting started
Install [uv](https://docs.astral.sh/uv/getting-started/installation/), then run:

```bash
git clone https://github.com/noppanit/first-neural-net.git
cd first-neural-net
uv sync
```

`uv sync` installs the project's pinned Python version, creates `.venv`, and installs the exact dependency versions in `uv.lock`. To use JupyterLab outside VS Code, run:

```bash
uv run jupyter lab
```

Start in `notebooks/01_meet_the_data.ipynb`, run cells with **Shift+Enter**, and answer the exercises.

### Run in VS Code
1. Open the repository folder (not just the `.ipynb` file) in VS Code.
2. Install the recommended **Python** and **Jupyter** extensions when prompted.
3. Run `uv sync` in VS Code's terminal.
4. Open a notebook, click **Select Kernel** in the top-right, and choose `.venv/bin/python` (`.venv\\Scripts\\python.exe` on Windows).
5. Use **Run All** from the notebook toolbar.

If `.venv` is not listed, run **Python: Select Interpreter** from the Command Palette and select it. Then reload the VS Code window and select the notebook kernel again.

## Dataset
The included `data/Advertising.csv` is the classic 200-row Advertising sample from [ISLR-python](https://github.com/JWarmenhoven/ISLR-python/blob/master/Notebooks/Data/Advertising.csv). **TV**, **Radio**, and **Newspaper** are input features; **Sales** is the target. This is for learning, not causal measurement of ad performance.
