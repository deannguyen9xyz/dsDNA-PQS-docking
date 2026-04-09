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
3. Run the script: **main.ipynb**

---

## <img width="40" height="40" alt="image" src="https://github.com/user-attachments/assets/2aabcc50-bd8f-4bec-93c8-15d6c4b4a581" /> Repository structure

- `dna/` – dsDNA structures (PDB files)
- `pdbqt/` – prepared receptor files
- `template/` – ligand files (PQS)
- `output/` – docking results

---

## <img width="40" height="40" alt="image" src="https://github.com/user-attachments/assets/53c4db4f-9e12-40ee-aad7-44ab96ecddc9" /> Limitations

- DNA structures were treated as rigid during docking
- Results represent relative binding affinity, not absolute values
- Binding poses should be interpreted qualitatively

--- 

## 📊 Result and Discussion

<img width="437" height="410" alt="image" src="https://github.com/user-attachments/assets/4960f242-7edf-4796-a8d4-ce4e5f978fe4" />

Figure. The bõ 40x40x40 Angstrom is quite big, enough to contain ¬13 bases pare

- Top candidate sequences were selected based on average binding energy and reproducibility (mean ± SD), this require 3-5 times repetition.
- The target PQS with the whole carbon chain stuck inside the dsDNA structure, which may happen when the dsDNA opens. However, the results are just comparable between them, not meaning of absolute values.

--- 

## 🧑‍💻 Author

Developed by: Vu Bao Chau Nguyen, Ph.D.

Keywords: DNA-based sensor, molecular docking.

---
