# Planar Truss Structure Analysis MATLAB Application

The MATLAB GUI allows the analysis of planar truss structures using Finite Element Method such that:
- The deflection values throughout the structure in both x and y directions
- The stress value for each element
- Reaction forces at the supports can found.
  
---

The GUI is named as TrussStructure_exported.p; and the other files are needed for running the GUI. 
The manual is named as Truss_Structure_Analysis_Manual.pdf in which the basic instructions related to GUI are given. 

---

The explanatory videos links for the concept&GUI as follows:
- [Theory](https://www.youtube.com/watch?v=nNnijrYtKAs)
- [GUI Explanation](https://www.youtube.com/watch?v=6010K-_Qfvg)

---
A sample screenshot from the GUI is as follows:<img width="1440" alt="1" src="https://user-images.githubusercontent.com/77242876/135863665-9a9fdc73-bb1a-4f1d-8a13-56fd83bbb95d.png">

---

- The purpose of this project is to design a mini-FE package with a GUI in MATLAB to analyze truss structures under various loadings and boundary conditions.
- The location of the nodes as well as their connectivity to generate elements can be entered by the user. Besides, Neumann and Dirichlet type of boundary conditions can be assigned to the nodes.
- The interface consists of three parts of pre-process, processor and post-processor. In the project, quantities of interest such as stress or displacements (in either directions) can be analyzed.
