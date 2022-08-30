# Cloud-Bind
Cloud-based Drug Binding Structure Prediction

## Hi there!

This is a repository where you can find a Jupyter notebook scripts for running [EquiBind](https://github.com/HannesStark/EquiBind) (geometric deep learning for drug binding structure prediction) and [GNINA](https://github.com/gnina/gnina) (molecular docking program with integrated support for scoring and optimizing ligands using convolutional neural networks) on Google Colab.

The main goal of this work is to demonstrate how to harness the power of cloud-computing in a cheap and yet feasible fashion.

1. **EquiBind** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Cloud-Bind/blob/main/EquiBind.ipynb)  - `Using EquiBind to perform direct-shot prediction of both the receptor binding location (blind docking) and the ligand’s bound pose and orientation.`
2. **GNINA** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Cloud-Bind/blob/main/GNINA.ipynb)  - `Using GNINA to perform molecular docking calculations with integrated support for scoring and optimizing ligands using convolutional neural networks. `
3. **EquiBind+MD** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Cloud-Bind/blob/main/EquiBind%2BMD.ipynb)  - `Using EquiBind to perform direct-shot prediction of both the receptor binding location (blind docking) and OpenMM to run molecular dynamics simulations`
4. **GNINA+MD** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Cloud-Bind/blob/main/GNINA%2BMD.ipynb)  - `Using GNINA to perform molecular docking calculations with integrated support for scoring and optimizing ligands using convolutional neural networks and OpenMM to run molecular dynamics simulations `

## Bugs
- If you encounter any bugs, please report the issue to https://github.com/pablo-arantes/Cloud-Bind/issues

## Acknowledgments
- We would like to thank the [EquiBind](https://github.com/HannesStark/EquiBind) and [GNINA](https://github.com/gnina/gnina) team for doing an excellent job open sourcing the software.
- We would like to thank the [Roitberg](https://roitberg.chem.ufl.edu/) team for developing the fantastic [TorchANI](https://github.com/aiqm/torchani).
- We would like to thank [@ruiz_moreno_aj](https://twitter.com/ruiz_moreno_aj) for his work on [Jupyter Dock](https://github.com/AngelRuizMoreno/Jupyter_Dock) 
- We would like to thank the ChemosimLab ([@ChemosimLab](https://twitter.com/ChemosimLab)) team for their incredible [ProLIF](https://prolif.readthedocs.io/en/latest/index.html#) (Protein-Ligand Interaction Fingerprints) tool.
- Also, credit to [David Koes](https://github.com/dkoes) for his awesome [py3Dmol](https://3dmol.csb.pitt.edu/) plugin.
- Finally, we would like to thank [Making it rain](https://github.com/pablo-arantes/making-it-rain) team, **Pablo R. Arantes** ([@pablitoarantes](https://twitter.com/pablitoarantes)), **Marcelo D. Polêto** ([@mdpoleto](https://twitter.com/mdpoleto)), **Conrado Pedebos** ([@ConradoPedebos](https://twitter.com/ConradoPedebos)) and **Rodrigo Ligabue-Braun** ([@ligabue_braun](https://twitter.com/ligabue_braun)), for their amazing work.
- A Cloud-Bind by **Pablo R. Arantes** ([@pablitoarantes](https://twitter.com/pablitoarantes))

## How should I reference this work?
- If you’re using **EquiBind**, please cite: <br />
  Stärk et al. "EquiBind: Geometric Deep Learning for Drug Binding Structure Prediction." <br />
  arXiv (2022) doi: [10.48550/arXiv.2202.05146](https://doi.org/10.48550/arXiv.2202.05146)
- If you’re using **GNINA**, please also cite: <br />
  McNutt et al. "GNINA 1.0: molecular docking with deep learning." <br />
  Journal of Cheminformatics (2021) doi: [10.1186/s13321-021-00522-2](https://doi.org/10.1186/s13321-021-00522-2)
- If you’re using **Molecular Dynamics Notebook**, please also cite: <br />
  Arantes et al. "Making it rain: cloud-based molecular simulations for everyone." <br />
  Journal of Chemical Information and Modeling (2021) doi: [10.1021/acs.jcim.1c00998](https://doi.org/10.1021/acs.jcim.1c00998)
