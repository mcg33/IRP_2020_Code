# Expression of the Retinal Determination Network in multiple cell types - IRP code 2020
This is the Github repository for Mcg33's IRP 2020, coded in Python3 and stored in .ipynb format to be run in Jupyter Notebooks. This repository contains the code used to run the cell clustering and velocity analysis from the project. It also contains information relating to how to run the code. 
## Python 3 modules
The primary module used for clustering is Kallisto-Bustools. This is a module for Python3 that allows the user to perform basic QC and cell clustering for single-cell RNA-sequencing datasets saved in FASTQ format (Melsted *et al.,* 2019).   
## Prerequisite Python3 modules
### Clustering with Kallisto Bustools
* Kallisto-Bustools
* matplotlib
* scikit-learn
* numpy
* scipy
* leidenalg
* scanpy  
### Kallisto-Bustools notebook on Google Collab 
Below is a link to the Google collab notebook using Kallisto-Bustools for clustering that all code is based off:
* [mouse_lung.ipynb](https://colab.research.google.com/github/pachterlab/BBB/blob/master/notebooks/lung_atlas/mouse_lung_dropseq_SRR8426358_python.ipynb)
## Uploaded files
* Clustering analysis of human and mouse retinal datasets:
  * [Clustering_Human_Retina.ipynb](https://github.com/mcg33/IRP_2020_Code/blob/main/Clustering_Human_Retina.ipynb)
  * [Clustering_Mouse_Retina.ipynb](https://github.com/mcg33/IRP_2020_Code/blob/main/Clustering_Mouse_Retina.ipynb)
* Clustering analysis of the human embryonic glutamatergic neuron dataset:
  * [Clustering_Human_LaManno.ipynb](https://github.com/mcg33/IRP_2020_Code/blob/main/Clustering_Human_LaManno.ipynb)
* Clustering analysis of the mouse pancreatic dataset:
  * [Clustering_Mouse_Pancreas.ipynb](https://github.com/mcg33/IRP_2020_Code/blob/main/Clustering_Mouse_Pancreas.ipynb)  
* The paper analysing the results:
  * [Expression of the Retinal Determination Network in multiple cell types (.pdf)](https://github.com/mcg33/IRP_2020_Code/blob/main/Final%20write-up.pdf)
