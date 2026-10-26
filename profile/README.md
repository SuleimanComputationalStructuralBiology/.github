<div align="center">
  <a href="https://suleimancomputationalstructuralbiology.github.io/">
    <img src="https://raw.githubusercontent.com/SuleimanComputationalStructuralBiology/SuleimanComputationalStructuralBiology.github.io/main/assets/logo.svg" alt="Suleiman Computational Structural Biology Logo" width="780"/>
  </a>
  <br/><br/>
  
  <p align="center">
    <strong>Advanced Research Platform for Deep Learning Structure Prediction, Kinase Mechanics & Automated Virtual Screening</strong>
  </p>

  <p align="center">
    <a href="https://suleimancomputationalstructuralbiology.github.io/"><img src="https://img.shields.io/badge/Live_Portal-suleimancomputationalstructuralbiology.github.io-00f2fe?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Live Site"/></a>
    <a href="https://github.com/SuleimanComputationalStructuralBiology"><img src="https://img.shields.io/badge/Organization-SuleimanComputationalStructuralBiology-7209b7?style=for-the-badge&logo=github&logoColor=white" alt="Organization"/></a>
    <a href="mailto:suleyman.hacizade1@gmail.com"><img src="https://img.shields.io/badge/Contact-IMB_Azerbaijan-10b981?style=for-the-badge&logo=gmail&logoColor=white" alt="Contact"/></a>
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/AlphaFold2-ColabFold_v1.6-0284c7?style=flat-square&logo=deepmind&logoColor=white" alt="AlphaFold2"/>
    <img src="https://img.shields.io/badge/AF2--Multimer-Heterodimer_Complexes-6366f1?style=flat-square" alt="AF2-Multimer"/>
    <img src="https://img.shields.io/badge/Virtual_Screening-AutoDock_Vina_v1.2.5-b45309?style=flat-square" alt="AutoDock Vina"/>
    <img src="https://img.shields.io/badge/Interactive_3D-3Dmol.js-06d6a0?style=flat-square" alt="3Dmol.js"/>
    <img src="https://img.shields.io/badge/Knowledge_Base-41_Interlinked_Notes-8b5cf6?style=flat-square" alt="Knowledge Base"/>
    <img src="https://img.shields.io/badge/Curriculum-9_Master_Modules-ec4899?style=flat-square" alt="Curriculum"/>
  </p>
</div>

---

## 🔬 Welcome to the Laboratory

The **Suleiman Computational Structural Biology** organization serves as a centralized computational research laboratory bridging systems biology and structural biophysics. 

Our core methodology traces a rigorous multi-scale path:
$$\text{Transcriptomics / WGCNA Hubs} \longrightarrow \text{Deep-Learning 3D Modeling (AlphaFold2)} \longrightarrow \text{Biophysical & Geometric Analytics} \longrightarrow \text{Allosteric Virtual Screening}$$

---

## 🏛️ Organization Architecture

To maintain the highest scientific rigor and protect sensitive work, our organization is structured into two dedicated repositories:

```
SuleimanComputationalStructuralBiology
│
├── 🔒 SuleimanComputationalStructuralBiology (Private Core Backend)
│   ├── Raw multi-sequence alignments (MSAs) & MMseqs2 profiles
│   ├── Unrelaxed & relaxed AlphaFold2 structure models
│   ├── Complete PAE distance matrices & per-residue pLDDT profiles
│   ├── AutoDock Vina receptor/ligand PDBQT preparation pipelines
│   ├── Master's computational structural biology curriculum & tutorial data
│   └── 41-note persistent LLM research wiki & manuscript drafts
│
└── 🌐 SuleimanComputationalStructuralBiology.github.io (Public Interactive Portal)
    ├── 🌟 Live URL: https://suleimancomputationalstructuralbiology.github.io/
    ├── Interactive 3Dmol.js molecular structure explorer
    ├── Real-time pLDDT line charts & PAE heatmap matrix viewer
    ├── Publication-grade figure gallery with multi-criteria filters
    ├── Searchable Markdown + KaTeX structural biology knowledge base
    └── Complete 9-module structural bioinformatics curriculum
```

---

## 🧪 Key Research Projects

### 1. [AKT1 Kinase Structural Modeling (TNBC Hub)](https://suleimancomputationalstructuralbiology.github.io/#research)
* **Target:** Human RAC-alpha serine/threonine-protein kinase (UniProt: `P31749`)
* **Context:** Identified as the central master regulator hub kinase in triple-negative breast cancer (TNBC) through weighted gene co-expression network analysis (WGCNA).
* **Methods:** AlphaFold2 (ColabFold v1.6.1, MMseqs2), custom vector-algebraic structural metrics, Ramachandran dihedral analysis ($\phi/\psi$), and pairwise $C_\alpha$ contact topology ($\le 8\text{ \AA}$).
* **Key Findings:** Highly confident catalytic kinase core ($\text{pLDDT} \ge 90$) flanked by intrinsically disordered regulatory linkers ($\text{pLDDT} < 50$); 573 long-range tertiary $C_\alpha$ contacts.

### 2. [STN7 / STN8 Chloroplast Kinase Complex & Docking](https://suleimancomputationalstructuralbiology.github.io/#research)
* **Target:** *Arabidopsis thaliana* thylakoid kinases STN7 (`Q9SHR7`) & STN8 (`Q9M0E6`)
* **Context:** Key photosynthetic regulators responsible for LHCII state transitions and Photosystem II (PSII) core D1 turnover.
* **Methods:** AF2-multimer complex prediction, SVD-based structural alignment, conserved kinase motif mapping (DFG, HRD, $\alpha$C-helix, P-loop), and high-throughput AutoDock Vina screening.
* **Screened Ligands:** Staurosporine, K252a, Quercetin, SB216763, ATP, and ADP.
* **Key Findings:** Identified canonical DFG-in active loop geometry, an extensive heterodimer interface driven by the STN7 C-terminal extension, and sub-nanomolar affinity scaffolds.

---

## 🌐 Public Interactive Platform Highlights

Visit our live web platform at **[suleimancomputationalstructuralbiology.github.io](https://suleimancomputationalstructuralbiology.github.io/)** to explore:

* 🧬 **3D Molecular Explorer:** Rotate, spin, zoom, and recolor AKT1 and STN7–STN8 models (Cartoon, Surface, Sphere, Stick) with AlphaFold pLDDT confidence color-mapping.
* 📊 **Linked Structural Charts:** Click any residue on the pLDDT confidence plot or PAE matrix to instantly focus and highlight that residue in the 3D viewer.
* 📚 **41-Note Scientific Wiki:** Search and read interconnected notes spanning entities (AKT1, STN7, STN8, LHCII, PTEN, mTORC2), concepts (Cryo-EM, MSMs, Docking, LDDT), and syntheses.
* 🎓 **Structural Bioinformatics Curriculum:** 9 master modules covering VMD scripting, MD simulations (GROMACS), enhanced sampling (Metadynamics/PLUMED), QM/MM (CP2K), and de novo protein design (RFdiffusion/ProteinMPNN).

---

## 👨‍🔬 Leadership & Affiliation

* **Lead Researcher:** Suleiman Hajizadeh
* **Affiliation:** Institute of Molecular Biology (IMB), Azerbaijan
* **Specialization:** Structural Bioinformatics, Deep-Learning Protein Modeling, Kinase Biophysics, Network Biology
* **Email:** [suleyman.hacizade1@gmail.com](mailto:suleyman.hacizade1@gmail.com)
* **Personal GitHub:** [@SuleimanHajizadeh](https://github.com/SuleimanHajizadeh)

---

<div align="center">
  <sub>© 2026 Suleiman Hajizadeh · Suleiman Computational Structural Biology Laboratory</sub>
</div>
