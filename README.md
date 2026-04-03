# dsDNA-PQS-docking
Molecular docking workflow for screening dsDNA sequences as binding elements for PQS.

---

## 🎯 Project Overview

This repository contains Jupyter Notebook scripts and data used to screen dsDNA sequences for binding affinity toward PQS. 
The workflow includes sequence preparation, docking using AutoDock Vina, and analysis of binding energies 
across multiple runs to identify stable and high-affinity candidates.

This work aims to find out the top DNA candidates for the development of dsDNA-based electrochemical sensors.

--- 

## ▶️ How to Run

1. Install dependencies:

       pip install numpy meeko pandas mdanalysis jupyter prolif RDkit gemmi

2. Make sure all the dsDNA PDB files in folder "dna", and template.PDB file in folder "template".
3. Run the script: **python battery_ekf_soc.py**

---

## <img width="40" height="40" alt="image" src="https://github.com/user-attachments/assets/2aabcc50-bd8f-4bec-93c8-15d6c4b4a581" /> Repository structure

- `dna/` – dsDNA structures (PDB files)
- `pdbqt/` – prepared receptor files
- `template/` – ligand files (PQS)
- `output/` – docking results

---

## 📊 Result and Discussion



--- 

## 🧑‍💻 Author

Developed by: Vu Bao Chau Nguyen, Ph.D.

Keywords: Lithium ion battery, Kalman filter, State of charge.

---
