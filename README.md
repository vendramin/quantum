 Mathematical Aspects of Quantum Computing (Summer 2026)

These are lecture notes for a graduate-level course on some mathematical aspects of quantum computing, held at the University of Marburg during the summer term of 2026.

# What (not) to expect

Here, you get the most recent version of the notes. This may include some sketched and incomplete section and parts that are under development. Proceed with caution. 

# Compilation Instructions

To compile these notes, please follow the guidelines below:

### 1. Style Requirements
You must use the `style.sty` file located in the `style-file/` directory. 
This stylesheet assumes a full **TeX Live** installation is available on your machine.

### 2. Externalisation 
If you wish to compile the notes using the **externalise** option, you need to:

* **Enable Shell Escape:** Ensure `write18` (shell escape) is enabled for `pdflatex`.
* **Create Figures Directory:** Manually create a folder named `figures/` in the root directory for the compiled graphics.

> **Note:** The first compilation run will take significantly longer than usual because all figures must be generated and externalised. Subsequent runs will be much faster though.
