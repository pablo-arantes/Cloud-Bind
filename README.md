# Cloud-Bind
Cloud-based Drug Binding Structure Prediction

![](https://github.com/pablo-arantes/Cloud-Bind/blob/main/Cloud-Bind.png)

## Hi there!

This is a repository where you can find a collection of Jupyter notebook scripts for running [GNINA](https://github.com/gnina/gnina) (molecular docking program with integrated support for scoring and optimizing ligands using convolutional neural networks),  [Uni-Dock](https://github.com/dptech-corp/Uni-Dock) (GPU-accelerated molecular docking program) and [OpenBPMD](https://github.com/Gervasiolab/OpenBPMD) (evaluating ligand pose stability using metadynamics) on Google Colab.

The main goal of this work is to demonstrate how to harness the power of cloud-computing in a cheap and yet feasible fashion.
**GNINA**
1. **GNINA** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Cloud-Bind/blob/main/GNINA.ipynb)  - `Using GNINA to perform molecular docking calculations with integrated support for scoring and optimizing ligands using convolutional neural networks. `
2. **GNINA+MD** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Cloud-Bind/blob/main/GNINA%2BMD.ipynb)  - `Using GNINA to perform molecular docking calculations and OpenMM to run molecular dynamics simulations.`
3. **GNINA+OpenBPMD** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Cloud-Bind/blob/main/GNINA%2BOpenBPMD.ipynb)  - `Using GNINA to perform molecular docking calculations and OpenBPMD to evaluate binding pose with metadynamics (BPMD).`
**Uni-Dock**
4. **Uni-Dock** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Cloud-Bind/blob/main/Uni_Dock.ipynb)  - `Using Uni-Dock to perform GPU-accelerated molecular docking calculations. It supports various scoring functions including vina and vinardo. `
5. **Uni-Dock+MD** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Cloud-Bind/blob/main/Uni_Dock%2BMD.ipynb)  - `Using Uni-Dock to perform GPU-accelerated molecular docking calculations and OpenMM to run molecular dynamics simulations.`
6. **Uni-Dock+OpenBPMD** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Cloud-Bind/blob/main/Uni_Dock%2BOpenBPMD.ipynb)  - `Using Uni-Dock to perform GPU-accelerated molecular docking calculations and OpenBPMD to evaluate binding pose with metadynamics (BPMD).`
**Virtual Screening**
**Uni-Dock+OpenBPMD** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Cloud-Bind/blob/main/Uni_Dock%2BOpenBPMD.ipynb)  - `Virtual Screening protocol, including molecular docking calculations with deep learning using the Gnina docking software, the Protein-Ligand Atomistic Conformational Ensemble Resolver and the AEV-PLIG binding affinity predictor.`

## Bugs
- If you encounter any bugs, please report the issue to https://github.com/pablo-arantes/Cloud-Bind/issues

## Acknowledgments
- We would like to thank the [GNINA](https://github.com/gnina/gnina) team for doing an excellent job open sourcing the software.
- We would like to thank the [Uni-Dock](https://github.com/dptech-corp/Uni-Dock) team for doing an excellent job open sourcing the software.
- We would like to thank the [OpenBPMD](https://github.com/Gervasiolab/OpenBPMD) team for their open source implementation of binding pose metadynamics (BPMD).
- We would like to thank the [Roitberg](https://roitberg.chem.ufl.edu/) team for developing the fantastic [TorchANI](https://github.com/aiqm/torchani).
- We would like to thank [@ruiz_moreno_aj](https://twitter.com/ruiz_moreno_aj) for his work on [Jupyter Dock](https://github.com/AngelRuizMoreno/Jupyter_Dock) 
- We would like to thank the ChemosimLab ([@ChemosimLab](https://twitter.com/ChemosimLab)) team for their incredible [ProLIF](https://prolif.readthedocs.io/en/latest/index.html#) (Protein-Ligand Interaction Fingerprints) tool.
- Also, credit to [David Koes](https://github.com/dkoes) for his awesome [py3Dmol](https://3dmol.csb.pitt.edu/) plugin.
- Finally, we would like to thank [Making it rain](https://github.com/pablo-arantes/making-it-rain) team, **Pablo R. Arantes** ([@pablitoarantes](https://twitter.com/pablitoarantes)), **Marcelo D. Polêto** ([@mdpoleto](https://twitter.com/mdpoleto)), **Conrado Pedebos** ([@ConradoPedebos](https://twitter.com/ConradoPedebos)) and **Rodrigo Ligabue-Braun** ([@ligabue_braun](https://twitter.com/ligabue_braun)), for their amazing work.
- A Cloud-Bind by **Pablo R. Arantes** ([@pablitoarantes](https://twitter.com/pablitoarantes)), **Conrado Pedebos** ([@ConradoPedebos](https://twitter.com/ConradoPedebos)) and **Rodrigo Ligabue-Braun** ([@ligabue_braun](https://twitter.com/ligabue_braun)).
- 
## How should I reference this work?
- If you’re using **GNINA**, please also cite: <br />
  McNutt et al. "GNINA 1.0: molecular docking with deep learning." <br />
  Journal of Cheminformatics (2021) doi: [10.1186/s13321-021-00522-2](https://doi.org/10.1186/s13321-021-00522-2)
- If you’re using **Uni-Dock**, please also cite: <br />
  Yu et al. "Uni-Dock: GPU-Accelerated Docking Enables Ultralarge Virtual Screening." <br />
  Journal of Chemical Theory and Computation (2023) doi: [10.1021/acs.jctc.2c01145](https://doi.org/10.1021/acs.jctc.2c01145)
- If you’re using **Molecular Dynamics Notebook**, please also cite: <br />
  Arantes et al. "Making it rain: cloud-based molecular simulations for everyone." <br />
  Journal of Chemical Information and Modeling (2021) doi: [10.1021/acs.jcim.1c00998](https://doi.org/10.1021/acs.jcim.1c00998)
- If you’re using **OpenBPMD**, please cite: <br />
  Clark et al. "Prediction of Protein–Ligand Binding Poses via a Combination of Induced Fit Docking and Metadynamics Simulations." <br />
  Journal of Chemical Theory and Computation (2016) doi: [10.1021/acs.jctc.6b00201](https://doi.org/10.1021/acs.jctc.6b00201)
  
  Lukauskis et al. "Open Binding Pose Metadynamics: An Effective Approach for the Ranking of Protein–Ligand Binding Poses." <br />
  Journal of Chemical Information and Modeling (2022) doi: [10.1021/acs.jcim.2c01142](https://doi.org/10.1021/acs.jcim.2c01142)
