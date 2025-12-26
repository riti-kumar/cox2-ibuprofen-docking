# COX-2–Ibuprofen Docking Study

## Overview
This repository presents a molecular docking study of **ibuprofen**, a non-steroidal anti-inflammatory drug (NSAID), with **Cyclooxygenase-2 (COX-2)**. The study was performed using the **CB-Dock2** web server for blind docking and **AutoDock Vina** as the scoring engine to identify potential binding pockets and evaluate ligand–protein interactions.

The objective of this project is to computationally analyze the binding affinity and preferred binding site of ibuprofen on COX-2, providing insights into its inhibitory mechanism.

---

## Tools and Databases
- **CB-Dock2** – blind docking and cavity detection
- **AutoDock Vina** – docking and scoring
- **AlphaFold Protein Structure Database** – COX-2 structure
- **ZINC Database** – ibuprofen ligand structure
- **PyMOL / CB-Dock2 Viewer** – visualization

---

## Methodology

1. The COX-2 protein structure was obtained from the AlphaFold Protein Structure Database.
2. The ibuprofen ligand structure was downloaded from the ZINC database.
3. Blind docking was performed using CB-Dock2, which automatically detects potential binding cavities.
4. Docking was carried out using AutoDock Vina to estimate binding affinities.
5. The best-ranked binding pose was visualized and analyzed based on docking score and pocket properties.

---

## Results

CB-Dock2 identified **five potential binding pockets** on the COX-2 protein. Among these, **CurPocket C5** exhibited the most favorable docking score.

| Pocket ID | Vina Score (kcal/mol) | Cavity Volume (Å³) |
|----------|----------------------|-------------------|
| C5       | **-6.4**             | 125               |
| C1       | -5.6                 | 2188              |
| C4       | -5.4
