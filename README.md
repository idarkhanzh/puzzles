<div align="center">

# ♞ Jane Street Puzzles — My Solutions

**My write-ups and code for the monthly [Jane Street puzzles](https://www.janestreet.com/puzzles/).**

<img src="https://img.shields.io/badge/language-Python-3776AB?logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/format-Jupyter%20Notebooks-F37626?logo=jupyter&logoColor=white" alt="Jupyter">
<img src="https://img.shields.io/badge/status-solving%20monthly-1D9E75" alt="Status">

</div>

---

## What is this?

Every month Jane Street posts a puzzle — usually some mix of logic, number theory, geometry, and search. I solve them, and this repo is where the solutions live.

Each puzzle gets its own Jupyter notebook that walks through the full solve: the setup, the reasoning that cuts the problem down to size, the code that finishes the job, and an independent verification of the final answer. The goal is that you can read a notebook top to bottom and follow exactly how the answer falls out — or just run it yourself and watch it happen.

## Solutions

| Puzzle | Month | Answer | Notebook |
|--------|-------|:------:|----------|
| 'Pent-Up' Frustration 3 / Knight Moves 7 | July 2026 | `33609` | [`knight_moves_7.ipynb`](./2026-07-knight-moves-7/knight_moves_7.ipynb) |

*(more coming as the months roll in)*

## Running the notebooks

Everything is plain Python — the only dependency beyond the standard library is `matplotlib` for the board plots.

```bash
pip install matplotlib jupyter
jupyter notebook
```

Open any notebook and run all cells. Each one is self-contained and re-derives its answer from scratch, assertions included.

## A note on timing

Solutions here are only published **after** Jane Street releases the official answer for that month. If the current puzzle isn't in the table yet — no spoilers, go solve it. 🙂

---

<div align="center">
<sub>Not affiliated with Jane Street. Puzzles © Jane Street Group, LLC — go try them at <a href="https://www.janestreet.com/puzzles/">janestreet.com/puzzles</a>.</sub>
</div>
