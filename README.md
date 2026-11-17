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

## Setup

```bash
git clone https://github.com/Xx-Pumpkin-xX/ml2-labwork.git
cd ml2-labwork
python -m venv .venv
# Windows: .venv\Scripts\activate    |    Linux/macOS: source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

## Conventions

- Notebooks are numbered (`01_...`, `02_...`) and must run top to bottom (Restart & Run All) before committing.
- Raw data is never edited in place; cleaned data is written to `data/processed/`.
- Figures used in the report are saved as PNG to the lab's `figures/` folder.
- Random seeds are fixed (`random_state=42`) so results are reproducible.
- Reports, course slides and lab statements are not part of this repository.
