# ☁️ Cloud-Bind
**Cloud-Based Drug Binding Structure Prediction**

![](https://github.com/pablo-arantes/Cloud-Bind/blob/main/Cloud-Bind.png)

---

## 🔬 Overview

**Cloud-Bind** is a cloud-powered platform for running molecular docking, virtual screening, and ligand pose evaluation directly in **Google Colab**, no local installation or high-performance computing required.

This repository contains a collection of Jupyter Notebooks integrating:
- [**GNINA**](https://github.com/gnina/gnina): Molecular docking with deep learning scoring using convolutional neural networks (CNNs).  
- [**Uni-Dock**](https://github.com/dptech-corp/Uni-Dock): GPU-accelerated molecular docking for ultralarge virtual screening.  
- [**OpenBPMD**](https://github.com/Gervasiolab/OpenBPMD): Binding pose metadynamics for ligand stability evaluation.  

The main goal of **Cloud-Bind** is to demonstrate how **cloud computing can democratize access** to advanced drug discovery tools, providing a **low-cost and fully reproducible pipeline** for structure-based modeling and binding pose assessment.

---

## 🚀 Available Workflows

### **GNINA**
1. **GNINA** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Cloud-Bind/blob/main/GNINA.ipynb)  
   Perform molecular docking with integrated CNN-based scoring and optimization.  

2. **GNINA + MD** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Cloud-Bind/blob/main/GNINA%2BMD.ipynb)  
   Combine GNINA docking with **OpenMM** molecular dynamics simulations for pose relaxation and stability.  

3. **GNINA + OpenBPMD** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Cloud-Bind/blob/main/GNINA%2BOpenBPMD.ipynb)  
   Use GNINA docking and **OpenBPMD** metadynamics to evaluate ligand pose stability (BPMD).  

---

### **Uni-Dock**
4. **Uni-Dock** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Cloud-Bind/blob/main/Uni_Dock.ipynb)  
   Perform GPU-accelerated molecular docking with multiple scoring functions (vina, vinardo, etc.).  

5. **Uni-Dock + MD** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Cloud-Bind/blob/main/Uni_Dock%2BMD.ipynb)  
   Combine Uni-Dock docking with **OpenMM** molecular dynamics simulations for post-docking relaxation.  

6. **Uni-Dock + OpenBPMD** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Cloud-Bind/blob/main/Uni_Dock%2BOpenBPMD.ipynb)  
   Integrate Uni-Dock docking with **OpenBPMD** to assess binding pose stability using metadynamics.  

---

### **Virtual Screening**
7. **Virtual Screening** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Cloud-Bind/blob/main/Virtual_Screening.ipynb)  
   Execute an end-to-end virtual screening protocol that includes:
   - Deep learning docking with **GNINA**
   - Conformational ensemble generation via **PLACER**
   - Binding affinity prediction with **AEV-PLIG**

---

## 🐞 Reporting Issues
If you encounter any bugs or have suggestions, please open an issue at:  
👉 [https://github.com/pablo-arantes/Cloud-Bind/issues](https://github.com/pablo-arantes/Cloud-Bind/issues)

---

## 🙏 Acknowledgments

We gratefully acknowledge the developers of the tools integrated in **Cloud-Bind**:

- [**GNINA**](https://github.com/gnina/gnina) — Deep learning–based molecular docking  
- [**Uni-Dock**](https://github.com/dptech-corp/Uni-Dock) — GPU-accelerated docking for ultralarge virtual screening  
- [**OpenBPMD**](https://github.com/Gervasiolab/OpenBPMD) — Binding pose metadynamics  
- [**ProLIF**](https://prolif.readthedocs.io/en/latest/index.html#) — Protein–Ligand Interaction Fingerprints  
- [**py3Dmol**](https://3dmol.csb.pitt.edu/) — Interactive 3D molecular visualization  

Special thanks to:  
**Pablo R. Arantes**, **Conrado Pedebos**, and **Rodrigo Ligabue-Braun**, developers of *Cloud-Bind*  
and to the *Making it Rain* team for pioneering open, cloud-based molecular simulation workflows.

---

## 📖 Citation Guidelines

If you use **Cloud-Bind** or any of its integrated notebooks, please cite the respective software and references:

- **Cloud-Bind**  
  Pedebos et al., *ChemRxiv,* **2025**, DOI: [10.26434/chemrxiv-2025-jr04j](https://doi.org/10.26434/chemrxiv-2025-jr04j)

- **GNINA**  
  McNutt et al., *J. Cheminform.* **2021**, DOI: [10.1186/s13321-021-00522-2](https://doi.org/10.1186/s13321-021-00522-2)

- **Uni-Dock**  
  Yu et al., *J. Chem. Theory Comput.* **2023**, DOI: [10.1021/acs.jctc.2c01145](https://doi.org/10.1021/acs.jctc.2c01145)

- **Molecular Dynamics Notebooks**  
  Arantes et al., *J. Chem. Inf. Model.* **2021**, DOI: [10.1021/acs.jcim.1c00998](https://doi.org/10.1021/acs.jcim.1c00998)

- **OpenBPMD**  
  Lukauskis et al., *J. Chem. Inf. Model.* **2022**, DOI: [10.1021/acs.jcim.2c01142](https://doi.org/10.1021/acs.jcim.2c01142)

---

💡 *Cloud-Bind: Bringing advanced molecular docking and pose evaluation to everyone, powered by the cloud.*
