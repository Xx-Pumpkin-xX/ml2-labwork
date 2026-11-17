# Lab 1 — Data Preparation & PCA

| Notebook | Dataset | Label |
|---|---|---|
| [`01_credit_card.ipynb`](notebooks/01_credit_card.ipynb) | Default of Credit Card Clients — 30,000 clients, 23 features | `default` (binary) |
| [`02_student_performance.ipynb`](notebooks/02_student_performance.ipynb) | Student Performance — math course, 395 students, 33 columns | `G3` / `pass` |

Each notebook follows the lab statement:
**Part 1** (1.1–1.9) feature types → quality → cleaning → integration → transformation → label → statistics → correlation
**Part 2** (2.1–2.6) PCA → explained variance → high vs low PCs → varying k → 2D plot → loadings & comparison

## Run

1. Download the data into `data/raw/` (see [`data/README.md`](data/README.md)).
2. Open a notebook from `notebooks/` and run all cells.
3. Figures are saved to `figures/credit/` and `figures/student/`.
