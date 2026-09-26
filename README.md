# Pandas Practice

My journey learning Pandas — from first principles to hands-on exercises,
with a cheat sheet I built along the way.

## Cheat Sheet

![Pandas Cheat Sheet](assets/pandas-cheatsheet.png)

## Structure

```
notebooks/   lessons and exercises, numbered in learning order
docs/        exercise questions, review notes, and lessons learned
data/        raw dataset(s) used by the notebooks
assets/      cheat sheet and other visual references
```

## Setup

```bash
pip install pandas numpy jupyter
```

Open a notebook from `notebooks/` and run it from that folder — data paths
are relative (`../data/...`).

## Notebooks

| Notebook | What it covers |
|---|---|
| [`00_lessons_1_to_18.ipynb`](notebooks/00_lessons_1_to_18.ipynb) | Foundational lessons: Series, DataFrames, reading/writing files, inspection, selection, grouping, strings, dates |
| [`01_pandas_exercise.ipynb`](notebooks/01_pandas_exercise.ipynb) | DataFrame inspection, filtering, missing values, grouping, pivot tables |
| [`02_pandas_exercise.ipynb`](notebooks/02_pandas_exercise.ipynb) | Series vs DataFrame selection, string cleaning, duplicates, dtype conversion, dates |

## Docs

- [`docs/questions.md`](docs/questions.md) — full question list for exercise 1
- [`docs/feedback.md`](docs/feedback.md) — review notes for exercise 1
- [`docs/lessons-learned.md`](docs/lessons-learned.md) — mistakes and fixes from exercise 2
