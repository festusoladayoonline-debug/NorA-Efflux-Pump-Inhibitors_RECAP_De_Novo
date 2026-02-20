# NorA Efflux Pump Inhibitor De Novo Design
Fragment-based de novo design for NorA efflux pump inhibitors. Combats antimicrobial resistance.


## Overview
This repository implements a **fragment-based de novo drug design workflow** targeting the **NorA efflux pump** (CHEMBL5114), a critical multidrug resistance protein in *Staphylococcus aureus*. NorA belongs to the Major Facilitator Superfamily (MFS) and is a primary driver of resistance against fluoroquinolones and other antimicrobials.

## Scientific Rationale
Efflux pump inhibitors (EPIs) represent a promising strategy to combat antimicrobial resistance (AMR) by restoring the intracellular concentration of antibiotics. This workflow adopts a **Fragment-Based Lead Discovery (FBLD)** philosophy to design novel NorA inhibitors.

## Features
- ✅ **Bioactivity Data Retrieval**: Fetches IC50 data from ChEMBL for NorA (CHEMBL5114)
- ✅ **Pharmacophore Analysis**: Identifies structural features of known NorA inhibitors
- ✅ **Fragment-Based Design**: Deconstructs known ligands into high-quality fragments
- ✅ **Combinatorial Reconstruction**: Rebuilds novel molecules using structural constraints
- ✅ **Multi-Objective Scoring**: Ranks candidates based on MW, LogP, TPSA, and toxicity filters
- ✅ **ADMET Filtering**: Applies PAINS and Brenk alerts for safety profiling

## Requirements
- Python 3.8+
- 8GB RAM minimum (16GB recommended)

## Installation
pip install -r requirements.txt
