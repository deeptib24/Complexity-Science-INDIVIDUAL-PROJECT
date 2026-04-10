# Cascading Workload Dynamics in Student Networks

This project models cascading workload dynamics in a network of interacting students using concepts from complexity science and self-organized criticality (SOC).

## Files Included

* `project_code.ipynb` – Python simulation and data analysis (avalanche distribution, plots, power-law fitting)
* `netlogo_simulation.nlogo` – Agent-based visualization of cascade dynamics
* `task_cascade.gif` – Sample visualization of cascading behavior
* `project_report.pdf` – Detailed report explaining model, methodology, and results

## Overview

The model represents students as nodes in a network with limited workload capacity. When a node exceeds its threshold, excess workload is redistributed to neighbors, potentially triggering cascades (avalanches).

## Key Features

* Network-based simulation (Erdős–Rényi graph)
* Threshold-driven cascade dynamics
* Avalanche size analysis
* Power-law fitting (τ ≈ 1.84) indicating SOC behavior
* Python + NetLogo visualization

## How to Run

1. Open `project_code.ipynb` in Jupyter Notebook and run all cells
2. Open `netlogo_simulation.nlogo` in NetLogo and click **Setup → Go**

## Outcome

The system exhibits heavy-tailed avalanche distributions and intermittent dynamics, suggesting self-organized criticality in workload propagation.

---

