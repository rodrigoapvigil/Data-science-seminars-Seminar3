# Seminar 3: The Scientific Paper of the Future
**Author:** Rodrigo Peña Vigil
**Institution:** Universidad Politécnica de Madrid (UPM)

This repository contains the practical assignments for Seminar 3, focusing on best practices for sharing software, data, and provenance in research.

## 1. Software Metadata (Assignment 1)
I have included a `codemeta.json` file that follows the community standard to describe software authors, dependencies, and licensing.
- **License:** Apache License 2.0 (Selected for its permissive nature as recommended in the seminar).

## 2. Provenance Documentation (Assignment 2)
The repository includes a provenance diagram (`diagrama_prov.png`) based on the "Student Financial Support" survey scenario.
- **Standard:** W3C PROV-O.
- **Summary:** The diagram tracks the research lifecycle from Laura's initial design, through data collection by Jack, Jill, Peter, and Paula, to Zack's final analysis and the publication of the paper. It includes entities, activities, and agents, highlighting relations like `wasDerivedFrom`, `used`, and `wasAssociatedWith`.

## 3. Preservation and Citation
To ensure this work is citable and permanently preserved, this repository has been integrated with Zenodo to generate a Digital Object Identifier (DOI).

**How to cite:**
Peña Vigil, Rodrigo. (2026). Data-science-seminars-Seminar3 (v1.0.1). GitHub. DOI: [PASTE_YOUR_ZENODO_DOI_HERE]

## 4. Repository Structure
- `codemeta.json`: Software metadata file.
- `diagrama_prov.png`: W3C PROV provenance diagram.
- `analysis.py`: Sample script representing the software component.
- `data/`: Sample dataset folder.
