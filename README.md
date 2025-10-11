[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/y12QcJaO)
# HW 2: From Notebooks to Research Packages

_This repository is public so that Binder can find it. All code and data is based on the original [LIGO Center for Open Science Tutorial Repository](https://github.com/losc-tutorial/LOSC_Event_tutorial). This repository is a class exercise that restructures the original LIGO code for improved reproducibility, as a homework assignment for the [Fall 2025 installment of UC Berkeley's Stat 159/259 course, _Reproducible and Collaborative Data Science](https://ucb-stat-159-f25.github.io/site/). Authorship of the original analysis code rests with the LIGO collaboration._


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/UCB-stat-159-f25/hw-2-saachigoyal26/HEAD?labpath=LOSC_Event_tutorial.ipynb)


This repository restructures the LIGO Gravitational Wave Detection Tutorial into a fully reproducible research package.  
It contains the necessary data, utilities, and environment specifications to replicate the analysis that detected gravitational waves from the event GW150914.

### 🔍 Overview
- Converts the original LIGO tutorial into a reproducible Python package called `ligotools`.  
- Defines an isolated Conda environment (`ligo`) for dependency management.  
- Enables one-click execution via Binder for open, reproducible workflows.  
- Demonstrates best practices in version control, modular code design, and environment reproducibility.

### 📁 Repository Structure
hw-2-saachigoyal26/
├── BBH_events_v3.json
├── GW150914_4_template.hdf5
├── H-H1_LOSC_4_V2-1126259446-32.hdf5
├── L-L1_LOSC_4_V2-1126259446-32.hdf5
├── LOSC_Event_tutorial.ipynb
├── ligotools/
│ ├── init.py
│ └── readligo.py
├── environment.yml
├── README.md
└── hw02-description.ipynb

bash
Copy code

