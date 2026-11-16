<div align="center">
  <a href="https://suleimancomputationalstructuralbiology.github.io/">
    <img src="https://raw.githubusercontent.com/SuleimanComputationalStructuralBiology/SuleimanComputationalStructuralBiology.github.io/main/assets/logo.svg" alt="Suleiman Computational Structural Biology Logo" width="780"/>
  </a>
  <br/><br/>
  
  <p align="center">
    <strong>Computational Structural Biology Laboratory · Institute of Molecular Biology (IMB)</strong>
  </p>

  <p align="center">
    <a href="https://suleimancomputationalstructuralbiology.github.io/"><img src="https://img.shields.io/badge/Public_Portal-Live_Site-0284c7?style=flat-square" alt="Live Site"/></a>
    <a href="https://github.com/SuleimanComputationalStructuralBiology"><img src="https://img.shields.io/badge/Organization-GitHub-334155?style=flat-square" alt="Organization"/></a>
    <a href="mailto:suleyman.hacizade1@gmail.com"><img src="https://img.shields.io/badge/Contact-suleyman.hacizade1%40gmail.com-059669?style=flat-square" alt="Contact"/></a>
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/Modeling-AlphaFold2_|_ColabFold-0369a1?style=flat-square" alt="AlphaFold2"/>
    <img src="https://img.shields.io/badge/Complexes-AF2--Multimer-4338ca?style=flat-square" alt="AF2-Multimer"/>
    <img src="https://img.shields.io/badge/Screening-AutoDock_Vina-b45309?style=flat-square" alt="AutoDock Vina"/>
    <img src="https://img.shields.io/badge/Visualization-3Dmol.js-0f766e?style=flat-square" alt="3Dmol.js"/>
    <img src="https://img.shields.io/badge/Knowledge_Base-48_Curated_Notes-6d28d9?style=flat-square" alt="Knowledge Base"/>
  </p>
</div>

---

## Overview

The **Suleiman Computational Structural Biology** laboratory operates within the Institute of Molecular Biology (IMB), focusing on macromolecular modeling, kinase mechanics, and automated virtual screening.

Research workflows integrate transcriptomics, deep-learning structural prediction, vector-algebraic geometric metrics, and ligand docking:

$$\text{Transcriptomics / WGCNA Hubs} \longrightarrow \text{Macromolecular Modeling (AlphaFold2)} \longrightarrow \text{Biophysical & Geometric Analytics} \longrightarrow \text{Allosteric Virtual Screening}$$

---

## Repository Structure and Data Access Policy

The organization is divided into a private core repository for ongoing computation and a public presentation portal:

```
SuleimanComputationalStructuralBiology
│
├── SuleimanComputationalStructuralBiology (Private Core Repository)
│   ├── Raw multiple sequence alignments (MSAs) and sequence profiles
│   ├── Unrelaxed and relaxed coordinate models
│   ├── Full PAE error matrices and per-residue pLDDT profiles
│   ├── Receptor and ligand preparation routines for AutoDock Vina
│   ├── Computational structural biology curriculum and tutorial assets
│   └── 48-note research knowledge base and manuscript drafts
│
└── SuleimanComputationalStructuralBiology.github.io (Public Presentation Portal)
    ├── Public URL: https://suleimancomputationalstructuralbiology.github.io/
    ├── Interactive 3D molecular structure viewer
    ├── Per-residue confidence plots and error heatmap viewers
    ├── Publication figure gallery
    ├── Structural biology knowledge base
    └── Master-level curriculum outlines
```

### Private Data and Access Inquiries

Raw datasets, multiple sequence alignments, full scoring tensors, simulation trajectories, and internal pipeline scripts remain private. Academic reviewers and researchers interested in evaluating or collaborating on these datasets may request repository access by contacting:

**Contact:** [suleyman.hacizade1@gmail.com](mailto:suleyman.hacizade1@gmail.com?subject=Access%20Request%20-%20SuleimanComputationalStructuralBiology%20Private%20Data)

---

## Research Projects

### 1. [AKT1 Kinase Structural Modeling in Triple-Negative Breast Cancer](https://suleimancomputationalstructuralbiology.github.io/research/akt1/)
* **Target:** Human RAC-alpha serine/threonine-protein kinase (UniProt: `P31749`).
* **Context:** Identified as a central regulatory hub kinase in triple-negative breast cancer (TNBC) via weighted gene co-expression network analysis (WGCNA).
* **Methods:** AlphaFold2 (ColabFold v1.6.1, MMseqs2), vector-algebraic backbone dihedral calculations (Ramachandran analysis), pairwise Cα contact topology, and Predicted Aligned Error (PAE) profiling.
* **Findings:** Well-defined catalytic kinase core (pLDDT >= 90) bordered by intrinsically disordered regulatory linkers (pLDDT < 50); 573 long-range tertiary Cα contacts identified.

### 2. [STN7 and STN8 Chloroplast Kinase Complex and Virtual Screening](https://suleimancomputationalstructuralbiology.github.io/research/stn7-stn8/)
* **Target:** *Arabidopsis thaliana* chloroplast thylakoid kinases STN7 (`Q9S713`) and STN8 (`Q9LZV4`).
* **Context:** Key regulators of photosynthetic acclimation, LHCII state transitions, and Photosystem II (PSII) core D1 protein turnover.
* **Methods:** AlphaFold2-multimer complex modeling, singular value decomposition (SVD) structural superposition, conserved catalytic motif mapping (DFG, HRD, alphaC-helix), and AutoDock Vina virtual screening.
* **Screened Compounds:** ATP, ADP, Staurosporine, K252a, SB216763, and Quercetin.
* **Findings:** Canonical active-site conformation, heterodimer interface mediated by the STN7 C-terminal extension, and sub-nanomolar binding affinities for selected kinase scaffolds.

---

## Public Web Portal

The companion web portal is accessible at **[suleimancomputationalstructuralbiology.github.io](https://suleimancomputationalstructuralbiology.github.io/)**:

* **3D Molecular Explorer:** Interactive WebGL inspection of AKT1 and STN7-STN8 coordinates with representation controls and confidence color mapping.
* **Linked Structural Charts:** Dynamic per-residue pLDDT line tracks and Predicted Aligned Error heatmaps with residue-level crosshair coordinates.
* **Scientific Knowledge Base:** 48 cross-linked articles cataloging target entities, biophysical concepts, literature sources, and comparative syntheses.
* **Curriculum Syllabus:** 9 graduate-level modules outlining methods from molecular dynamics to structural prediction and de novo protein design.

---

## Laboratory Leadership and Affiliation

* **Lead Researcher:** Suleiman Hajizadeh
* **Affiliation:** Institute of Molecular Biology (IMB), Azerbaijan
* **Focus:** Structural Bioinformatics, Macromolecular Modeling, Kinase Biophysics, Systems Biology
* **Email:** [suleyman.hacizade1@gmail.com](mailto:suleyman.hacizade1@gmail.com)
* **GitHub:** [@SuleimanHajizadeh](https://github.com/SuleimanHajizadeh)

---

<div align="center">
  <sub>Suleiman Computational Structural Biology Laboratory · Institute of Molecular Biology (IMB)</sub>
</div>
