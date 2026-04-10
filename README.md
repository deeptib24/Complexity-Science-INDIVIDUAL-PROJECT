# Cascading Workload Dynamics in Student Networks

This project explores cascading workload dynamics in student interaction networks using concepts from complexity science and self-organized criticality (SOC).

## 📁 Repository Structure

* `project_code.ipynb` – Python simulation, avalanche analysis, and power-law fitting
* `netlogo_simulation.nlogo` – Agent-based NetLogo model for cascade visualization
* `project_latex.tex` – LaTeX source of the report
* `project_report.pdf` – Final compiled report
* `task_cascade.gif` – Simulation preview of cascading behavior

## 🔍 Overview

The model represents students as nodes in a network with limited workload capacity. When a node exceeds its threshold, excess workload is redistributed to neighbors, potentially triggering cascading failures (avalanches).

## ⚙️ Features

* Random network (Erdős–Rényi model)
* Threshold-based cascade dynamics
* Avalanche size distribution analysis
* Power-law fitting with exponent $\tau \approx 1.84$
* Python and NetLogo-based visualization

## ▶️ How to Run

### Python Simulation

1. Open `project_code.ipynb` in Jupyter Notebook
2. Run all cells to generate results and plots

### NetLogo Simulation

1. Install NetLogo: https://ccl.northwestern.edu/netlogo/
2. Open `netlogo_simulation.nlogo`
3. Click **Setup** → **Go**

## 📊 Outcome

The system exhibits heavy-tailed avalanche distributions and intermittent dynamics, indicating power-law-like behavior and self-organized criticality.

---
