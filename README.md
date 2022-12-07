# TCGA-PRAD
<img width="996" alt="Schermata 2022-11-29 alle 16 01 22" src="https://user-images.githubusercontent.com/91341004/204564258-466abba8-bc3b-43c0-b693-1ccd0d8f223d.png">

We will study from the perspective of Precision Medicine the 	Prostate Adenocarcinoma Data from the well known GDC data Portal: https://portal.gdc.cancer.gov/projects/TCGA-PRAD. The main goal of this project is to find hub genes related to the tumor condition. In particular we carried out a multi step analysis:
- extrapolation and preprocessing the relevant data;
- construction of Differentially Expressed Genes (DEGs);
- construction of Coexpression Networks (exploiting hard-thresholding and comparing it with soft-thresholding), and identification of candidate hub genes by considering different centrality measures;
- analysis (with different similarity measures) of Differential Coexpressed Network based on DEGs;
- extrapolation of communities (with different methods and via clustering techniques) in Patient Similarity Networks.

### What's in here?
There are two branches. In the `main` branch there are:
- The notebook with alll the code we used to carry out the project `DEPM-1_proj_group-14.ipynb`
- The reprt with our findings `DEPM-1_proj_group-14.pdf`.

In the `previous versions` branch there are previous versions of the notebook `DEPM-1_proj_group-14.ipynb`.

**Remark .** The notebook `DEPM-1_proj_group-14.ipynb` contains R code. We used Google Colab to work on it since it offered GPUs, redy to use R Libraries and Packages, and remote access to the code. So, to run the notebbok, either use Google Colab with an R kernel (e.g. by clicking the `Open In Colab` button), or use a locally available R distribution paying attention to the set up steps. It is also possible to run locally the notebook, using a distribution like Anaconda, lounching the `ipynb` file with Jupiter Notebook equipped with an R kernel (provided that the necessary libraries needed to execute the code are available), but we haven't tested this procedure. 

### Dataset
All the relevant data was extracted from the Genomic Data Commons Data Portal using custom R code to carry out the necessary queries. See https://portal.gdc.cancer.gov/projects/TCGA-PRAD.

### Disclamair
This project was part of a course of Digital Epidemiology and Precision Medicin at Sapienza University of Rome held by Prof. M. Petti. 
