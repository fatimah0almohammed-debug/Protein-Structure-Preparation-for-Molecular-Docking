# Protein Structure Preparation for Molecular Docking

## Overview

This project demonstrates the preparation of an experimental protein structure for molecular docking using UCSF Chimera.

## Objective

To prepare the experimental structure of human Dihydrofolate Reductase (DHFR) by inspecting the structure, removing unwanted components, and using Dock Prep to generate a clean structure suitable for molecular docking.

## Protein Information

* **PDB ID:** 1U72
* **Protein:** Dihydrofolate reductase (DHFR)
* **Organism:** Homo sapiens
* **Chain:** A
* **Experimental Method:** X-ray diffraction
* **Resolution:** 1.90 Å

## Software Used

* RCSB Protein Data Bank
* UCSF Chimera
* PyMOL

## Workflow

1. Downloaded the experimental protein structure (PDB ID: 1U72) from the RCSB Protein Data Bank.
2. Opened the structure in UCSF Chimera.
3. Inspected the protein structure and its chains, water molecules, ligands, and heteroatoms.
4. Selected Chain A for preparation.
5. Removed water molecules.
6. Inspected the remaining ligands and heteroatoms.
7. No additional unwanted cofactors or heteroatoms were identified for removal.
8. Ran Dock Prep in UCSF Chimera to prepare the protein structure.
9. Added hydrogens using Dock Prep.
10. Saved the prepared structure and visualized the raw and prepared structures in PyMOL.

## Preparation Results

The experimental DHFR structure was successfully prepared for molecular docking. Water molecules were removed, and hydrogens were added during the Dock Prep process. The resulting prepared structure was saved for further computational analysis.

## Before and After Visualization

### Before Preparation

The raw experimental structure was visualized in PyMOL before protein preparation.

### After Preparation

The prepared protein structure was visualized in PyMOL after the Chimera preparation process.

## Files

* `1U72.cif` — Experimental protein structure.
* `Chimera edited.mol2` — Structure file generated during the Chimera preparation workflow.
* `prepared.pdb` — Prepared protein structure for molecular docking.
* `Before_PyMOL.png` — Raw structure visualization before preparation.
* `After_PyMOL.png` — Prepared structure visualization after preparation.
* `Protein_Preparation_Report.pdf` — Completed project report.

## Conclusion

Protein preparation is an important step before molecular docking because it ensures that the protein structure is appropriately processed for computational analysis. The prepared DHFR structure can subsequently be used as a receptor for molecular docking studies.
