# Assignment-1-9013742-CSCN8020

# CSCN8020 — Assignment 1 (Reinforcement Learning Programming)

This repo/notebook set contains solutions for **Problems 1–4** of the CSCN8020 assignment:
- **P1:** MDP design for a pick-and-place robot (states, actions, rewards).
- **P2:** Two value-iteration sweeps on a **2×2** grid (markdown solution).
- **P3:** Value Iteration (standard & in-place) on a **5×5** grid; print **V\*** and **π\***.
- **P4:** Off-Policy Monte Carlo with **importance sampling** on the same 5×5 grid; estimate **Q**, **V**, and greedy **π**.

---

## 📦 Contents

- `CSCN8020_Assignment1_P1_P2.ipynb` — Notebook for **Problem 1 (MDP design)** and **Problem 2** (explanation + demo).
- `p3_value_iteration.py` — **Problem 3**: 5×5 gridworld Value Iteration (standard + in-place) with pretty printers.
- `p4_offpolicy_mc_is.py` — **Problem 4**: Off-policy MC control with Weighted Importance Sampling.
- `requirements.txt` — Minimal runtime requirements (Jupyter only; code uses stdlib).

> If you prefer notebooks for P3/P4, copy the code into new notebooks or run the `.py` files directly.

---

## 🚀 Quick Start

```bash
# 1) (Optional) Create & activate a virtual environment
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate

# 2) Install the minimal requirements (Jupyter)
pip install -r requirements.txt

# 3) Open the provided notebook for P1 & P2
jupyter notebook CSCN8020_Assignment1_P1_P2.ipynb

# 4) Run Problem 3 (CLI)
python p3_value_iteration.py

# 5) Run Problem 4 (CLI)
python p4_offpolicy_mc_is.py
