# Daniel Ogundero

Biotechnology engineering student (ESBS, University of Strasbourg; MSc Biology, Freiburg) moving into **computational biology**: modelling, molecular docking/dynamics, structural bioinformatics and AI/ML in biology.

**Looking for a 6-month end-of-studies internship starting February/March 2027** (degree expected August 2027).

📫 [daniel.ogundero@etu.unistra.fr] · [LinkedIn](www.linkedin.com/in/daniel-ogundero)

---

## Selected projects

### 🧬 [NylC–polyamide docking pipeline](https://github.com/darni3l/nylc-docking)
**Question:** how does a nylon-degrading enzyme (NylC, PDB 3AXG) bind a polyamide substrate, and does docking into the native tetramer change the outcome compared with the isolated monomer? Relevant to enzymatic plastic recycling.

**What I did:** built a reproducible Python pipeline around AutoDock Vina, MGLTools and PyMOL (receptor/ligand preparation, docking, result parsing, 5-seed replicates). Poses were ranked by score *and* by catalytic geometry (distance between Thr-267 OG1 and the ligand's carbonyl carbon).

**Findings:** Vina’s score alone did not identify the reaction-plausible pose, so geometry was checked in both conditions. The tetramer scored about 0.5 kcal/mol better than the monomer across replicates: reproducible, but below typical Vina scoring uncertainty, so not strong evidence of a real binding difference. This is tentatively attributed to atoms from other chains falling inside the search box (hypothesis, not yet tested with a control).

**Skills:** structure preparation, docking, pose analysis, scripting, honest reporting of limitations (rigid receptor, score ≠ affinity).
Built independently, with AI assistance for learning and troubleshooting, as disclosed in the repository.

### ⚛️ [BRD4 bromodomain: molecular dynamics of the W81A/F83A mutant](https://github.com/darni3l/brd4-md-simulation)
**Question:** how does removing two binding-pocket aromatic residues change the dynamics of BRD4 BD1 and the stability of a bound dual BET–HDAC inhibitor (LSH24)?

**What I did:** compared apo, holo and mutant systems (system building with CHARMM-GUI, CHARMM36m/CGenFF, NAMD, analysis in VMD and PyMOL). Coursework at ESBS, done with a classmate: we each ran the full set of MD simulations independently on our own machines, then co-wrote the report together.

**Findings:** a short single-run vacuum simulation (200 ps), so conclusions are limited: the ligand stayed in the pocket in both holo and mutant, and the mutant showed a late localised rearrangement that cannot be attributed to the mutation from one run. The repository states these limitations explicitly.

**Skills:** MD setup and minimisation, force-field parametrisation, trajectory analysis, critical interpretation.

---

## Tools I have used in these projects
Python · AutoDock Vina · MGLTools · PyMOL · NAMD · VMD · CHARMM-GUI · CHARMM36m / CGenFF · Git/GitHub 

## Languages
French and English (bilingual) · Spanish (B1) · German (A2)

## Interests
Structural bioinformatics · molecular modelling and dynamics · AI/ML applied to biology · high-throughput biological data analysis

<!--
**darni3l/darni3l** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
