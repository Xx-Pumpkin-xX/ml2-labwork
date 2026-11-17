# ML2 Labwork — Machine Learning and Data Mining II

Source code for the labwork of the course **Machine Learning and Data Mining II** (USTH).

| Lab | Topic | Folder | Status |
|---|---|---|---|
| 1 | Data preparation & Principal Component Analysis (PCA) | [`lab1/`](lab1/) | In progress |
| 2 | TBA | [`lab2/`](lab2/) | Not started |
| 3 | TBA | [`lab3/`](lab3/) | Not started |

## Repository structure

```
ml2-labwork/
├── lab1/
├── lab2/
├── lab3/
├── requirements.txt
└── README.md
```

Each lab folder will get its own `README.md` with the tasks, datasets and key results.

## Conventions

- Raw data is never edited in place; cleaned data is written to `data/processed/`.
- Random seeds are fixed (`random_state=42`) so results are reproducible.
- Reports, course slides and lab statements are not part of this repository.
