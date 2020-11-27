# Retinal Determination Network expression in non-retinal tissues - IRP code 2020
This is the Github repository for Mcg33's IRP 2020, coded in Python3 and stored in .ipynb format to be run in Jupyter Notebooks. This repository contains the code used to run the cell clustering and velocity analysis from the project. It also contains information relating to how to run the code. 
## Python 3 modules
The main module for clustering is Kallisto-Bustools. This is a module for Python3 allowing the user to perform basic QC and cell clustering for single-cell RNA-sequencing datasets saved in FASTQ format. RNA Velocity analysis is primarily run using the scVelo module for Python 3 (*Bergen V*, *et al.,*(2020)). scVelo is a scalable toolkit for RNA velocity analysis in single cells.    
## Prerequisite Python3 modules
### Clustering with Kallisto Bustools
* Kallisto-Bustools
* matplotlib
* scikit-learn
* numpy
* scipy
* leidenalg
* scanpy  
### Velocity analysis with scVelo
* Kallisto-Bustools
* scVelo  
### Velocity analysis with Google Collab  
Installing the relevant module required to run the Google Collab session is part of the set-up within the session.
* Kallisto-Bustools
* scanpy
* loompy
* scVelo
* anndata
* velocyto
* python-igraph
* louvain  
## Uploaded files
* Clustering analysis of human and mouse retinal datasets:
  * **Clustering_Human_Retina.ipynb**
  * **Clustering_Mouse_Retina.ipynb**
* Clustering analysis of the human embryonic glutamatergic neuron dataset:
  * **Clustering_Human_LaManno.ipynb**
* Clustering analysis of the mouse pancreatic dataset:
  * **Clustering_Mouse_Pancreas.ipynb**  
* Velocity analysis of the mouse pancreatic dataset:
  * **RNAvelo_Mouse_Velocity.ipynb**  
* Velocity analysis of the human embryonic glutamatergic neuron dataset (Error):
  * **Velocity_Human_scVelo_error.ipynb** - The code crashing with "Keyerror: X-Umap"
  * **https://colab.research.google.com/github/pachterlab/kallistobustools/blob/master/notebooks/kb_velocity.ipynb** - Code is based off this Google Collab session
