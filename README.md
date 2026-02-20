# chem5412-spring2026
Course materials for CHEM 5412 Structural Bioinformatics II (Spring 2026)


## Week 1: Intro to Structural Bioinformatics II

<details>
   
<summary>Week 1 material</summary>

### Reading

[PDB-101: A Guide to Understanding PDB Data](https://pdb101.rcsb.org/learn/guide-to-understanding-pdb-data) 

### Classroom 

1. Overview of the Course [Syllabus](https://docs.google.com/document/d/1IGzo_B5qDoInHGlWOUk1xnXKJUxShs8kWADd1V1-gNw/edit?usp=sharing)
2. Lecture notes: [Intro to Structural Bioinformatics II](https://templeu.instructure.com/courses/168964/files/37629788?module_item_id=8694021)

3. Getting started with Google Colab: `notebooks/00_getting_started.ipynb` [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vvoelz/chem5412-spring2026/blob/main/notebooks/00_getting_started.ipynb)

4. PDB I/O  `notebooks/01_pdb_io.ipynb` [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vvoelz/chem5412-spring2026/blob/main/notebooks/01_pdb_io.ipynb)


### Resources 

* [BioPython Tutorial and Cookbook](https://biopython.org/docs/latest/Tutorial/index.html)
* [Retrieving Information from the PDB using the Web API](https://education.molssi.org/python-scripting-biochemistry/chapters/rcsb_api.html)


#### Software for visualizing PDB structures

* [UCSF ChimeraX](https://www.rbvi.ucsf.edu/chimerax/) - latest release version 1.11 recommended 
* [Online Mol* 3D Viewer](https://www.rcsb.org/3d-view) at [RCSB](https://www.rcsb.org)
* [PyMOL](https://www.pymol.org/)
* [VMD](https://www.ks.uiuc.edu/Research/vmd/) Visual Molecular Dynamics - v1.9.4 recommended. This application excels at visualizing MD trajectories. 


</details>

## Week 2

No class due to MLK Holiday


## Week 3: Protein folding and the structure prediction problem

<details>   
<summary>Week 3 material</summary>
   
### Reading

### Classroom 

1. Lecture notes: [Protein Folding and Structure Prediction (Part I)](https://templeu.instructure.com/courses/168964/files/37858171?module_item_id=8744615)
   
2. Recording of [Zoom lecture](https://temple.zoom.us/rec/share/fWr0Lqh4Nk2bBppzEcTAw-zQHu4dEi_m8C3UQgm3EklZI_YlndJz5WhTYdUzcbyn.A8KTyxRLvrSYdH4e)

### Resources and Links

The CASP (Critical Assessment of Structure Prediction) Challenges: [Protein Structure Prediction Center](https://predictioncenter.org/)

David Baker (University of Washington/HHMI) Youtube lectures (from 2011):
* [Part 1: Introduction to Protein Design](https://www.youtube.com/watch?v=0LetJMbu7uY)
* [Part 2: Design of New Protein Functions](https://www.youtube.com/watch?v=ZrAwWx7meTk)

David Baker, Nobel Prize in Chemistry 2024 [Nobel Lecture](https://www.youtube.com/watch?v=KbDvQgsOI-E)

</details>


## Week 4: AI-based tools for structure prediction: the AlphaFold era

<details>   
<summary>Week 4 material</summary>
   
### Reading

Jumper, John, Richard Evans, Alexander Pritzel, et al. “Highly Accurate Protein Structure Prediction with AlphaFold.” Nature 596, no. 7873 (2021): 583–89. https://doi.org/10.1038/s41586-021-03819-2.

Abramson, Josh, Jonas Adler, Jack Dunger, et al. “Accurate Structure Prediction of Biomolecular Interactions with AlphaFold 3.” Nature 630, no. 8016 (2024): 493–500. https://doi.org/10.1038/s41586-024-07487-w.

Lin, Zeming, Halil Akin, Roshan Rao, et al. “Evolutionary-Scale Prediction of Atomic-Level Protein Structure with a Language Model.” Science 379, no. 6637 (2023): 1123–30. https://doi.org/10.1126/science.ade2574.



### Classroom 

1. Lecture notes: TBA

### Assignment 1:  Protein Structure Prediction 

1. Assignment 1 Instructions [Google Doc](https://docs.google.com/document/d/1Xq1oCiqk3GRiDdmGxceRBJaIwuFMb8veVqoJCjoaId0/edit?usp=sharing)
2. List of [Assigned Targets](https://github.com/vvoelz/chem5412-spring2026/tree/main/data/assignment01)
3. Colab notebook: Example for Assignment 1: `notebooks/02_structure_prediction.ipynb` [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vvoelz/chem5412-spring2026/blob/main/notebooks/02_structure_prediction.ipynb)
   
### Resources and Links

CASP

* [CASP16](https://predictioncenter.org/casp16/index.cgi)
* [CASP16 Targets](https://predictioncenter.org/casp16/targetlist.cgi)
* CASP16 [Results for Protein Domains](https://predictioncenter.org/casp16/results.cgi?tr_type=regular)
* CASP 16 Special Issue in PROTEINS: https://onlinelibrary.wiley.com/toc/10970134/2026/94/1

ColabFold

* Mirdita, M., Schütze, K., Moriwaki, Y. et al. ColabFold: making protein folding accessible to all. Nat Methods 19, 679–682 (2022). [https://doi.org/10.1038/s41592-022-01488-1](https://doi.org/10.1038/s41592-022-01488-1)

* [ColabFold GitHub](https://github.com/sokrypton/ColabFold?tab=readme-ov-file)


</details>

## Week 5: Introduction to Virtual Screening

<details>   
<summary>Week 5 material</summary>
   

### Classroom 

1. Lecture notes: [Introduction to Virtual Screening](https://templeu.instructure.com/courses/168964/modules/items/8762714)


   
### References

</details>

## Week 6: Introduction to Virtual Screening - Part II

  
<summary>Week 6 material</summary>
   

### Classroom 

1. Lecture notes: [Structure-Based Virtual Screening](https://templeu.instructure.com/courses/168964/modules/items/8772017)

### Assignment 2:  Virtual Screening with Autodock Vina

1. Assignment 2 Instructions [Google Doc](https://docs.google.com/document/d/1T4cuU7S2ydSFtaIAL3gEgC8PqmeGrJ-N_2eY08bjL3A/edit?usp=sharing)
2. Colab notebook: Example for Assignment 2: `notebooks/03_virtual_screening.ipynb` [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vvoelz/chem5412-spring2026/blob/main/notebooks/03_virtual_screening.ipynb)
   
### References







