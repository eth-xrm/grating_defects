# Quantifying grating defects in X-ray Talbot-Lau interferometry through a comparative study of two fabrication techniques

This repository contains the simulation and analysis code for the manuscript 
*Quantifying grating defects in X-ray Talbot-Lau interferometry through a comparative study of two fabrication techniques*.

The simulation is built on the RAVE SIM package (https://doi.org/10.1364/OE.543500). Installations need to be followed based on the provided git submodule.

The Python environment is shared across the entire codebase. The requirements.txt file in the root directory therefore contains the requirements for all the subprojects.


```bash
git submodule update --init
conda create -n simEnv python=3.11.7
conda activate simEnv
pip install -r requirements.txt
```

Further installations to use the CUDA implementation follow the instructions provided in https://github.com/eth-xrm/rave-sim

All notebooks need to be adapted to incorporate the correct paths to the RAVE SIM code paths, prior to running.
