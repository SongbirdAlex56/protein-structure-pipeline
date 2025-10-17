# Protein Structure Pipeline

Predicting and visualizing neuroscience-related protein structures (e.g., VMAT2, nicotinic receptor) using ColabFold (AlphaFold2 + MMseqs2) and PyMOL. 

- **Started:** August 2025  
- **Last updated (pushed):** October 2025  

## Project Overview
This project demonstrates how deep learning tools can be used to fold amino acid sequences into 3D structures and explore them visually.  
By focusing on proteins tied to neurotransmission (such as **VMAT2**, which regulates dopamine/serotonin storage, and **nicotinic receptors**), the goal is to connect **computer science** methods with **neuroscience** insights.

##  Pipeline
1. **Input**: Protein sequence in FASTA format (from [UniProt](https://www.uniprot.org/)).  
2. **Prediction**: Run [ColabFold](https://github.com/sokrypton/ColabFold) to generate structural models (PDB files).  
3. **Visualization**: Open predicted structures in PyMOL/Chimera for analysis and figure generation.  
4. **Output**: 3D models, confidence scores, and visualizations.

##  Repository Structure
protein-structure-pipeline/
├── data/ # input protein sequences
│ └── VMAT2.fasta
├── results/ # ColabFold outputs
│ ├── ranked_0.pdb
│ ├── plddt.png
│ ├── coverage.png
│ └── pae.png
├── notebooks/ # Colab notebooks used for predictions
│ └── ColabFold_run.ipynb
├── figures/ # PyMOL/Chimera visualizations (to be added)
└── README.md

More to be added soon. 
