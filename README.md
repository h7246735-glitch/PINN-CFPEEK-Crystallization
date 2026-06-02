# PINN-CFPEEK-Crystallization
Data for "A universal differential equation framework for decoupling non-equilibrium crystallization kinetics in CF/PEEK composite manufacturing"
========================================================================
README: Data and Code for Research Article
========================================================================

TITLE: A universal differential equation framework for decoupling non-equilibrium crystallization kinetics in CF/PEEK composite manufacturing

JOURNAL: Computational Materials Science
MANUSCRIPT NO.: COMMAT-D-26-02130

------------------------------------------------------------------------
1. SOFTWARE & ENVIRONMENT
------------------------------------------------------------------------
- Software: Jupyter Notebook / JupyterLab
- Programming Language: Python 3.8+
- Main Framework: PyTorch (torch)
- Required Libraries: torch, pandas, numpy, matplotlib, os

------------------------------------------------------------------------
2. FILE DESCRIPTION
------------------------------------------------------------------------
This package contains the source codes and datasets used in this study:

Code Files:
- DNN-PINN-PEEK.ipynb: PINN-based training for pure PEEK.
- DNN-PINN-CFPEEK.ipynb: PINN-based training for CF/PEEK composites.

Data Files (CSV):
- nonisoDatepeek.csv: Experimental dataset for pure PEEK.
- nonisoDatepeekcf2.csv: Experimental dataset for CF/PEEK composites.

Instructions:
- ReadMe_Instructions.txt: This instruction file.

------------------------------------------------------------------------
3. HOW TO RUN THE CODE
------------------------------------------------------------------------
1. Ensure Python and PyTorch are installed in your environment.
2. Keep both .ipynb files and .csv files in the SAME directory.
3. Open the Jupyter Notebooks.
4. Run the cells sequentially. The code will automatically load the 
   corresponding CSV data file from the current directory to perform 
   the PINN training and generate the results.
========================================================================
