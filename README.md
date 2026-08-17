# Data Availability: Beyond the Quasiparticle Approximation: Lattice Heat Capacity of Strongly Anharmonic Solids

This repository contains the computational data and analysis scripts for the manuscript **"Beyond the Quasiparticle Approximation: Lattice Heat Capacity of Strongly Anharmonic Solids"**.

---

## 📁 Repository Structure

The repository is organized by material into two main directories:
* `agcl/`: Contains data and analysis for Silver Chloride (AgCl).
* `pbte/`: Contains data and analysis for Lead Telluride (PbTe).

Both directories share the identical internal structure and file formats as described below.

```text
.
├── agcl/                          
└── pbte/                          
    ├── heat_capacity.ipynb        # Jupyter notebook for heat capacity analysis
    ├── POSCAR                     # Crystal structure input file
    ├── norm_mode_resolved_*/      # Mode-resolved lattice heat capacity folders
    └── T*/                        # Directory containing temperature-dependent input files
        ├── BTE.omega                  # Raw frequency data (ShengBTE format)
    	└── BTE.sefeng*ph_spectrum     # Raw phonon self-energy spectrum data
