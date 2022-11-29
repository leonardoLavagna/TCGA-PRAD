# TCGA-PRAD
<img width="996" alt="Schermata 2022-11-29 alle 16 01 22" src="https://user-images.githubusercontent.com/91341004/204564258-466abba8-bc3b-43c0-b693-1ccd0d8f223d.png">

We will study from the perspective of Precision Medicine the 	Prostate Adenocarcinoma Data from the well known GDC data Portal: https://portal.gdc.cancer.gov/projects/TCGA-PRAD. The main goal of this project is to find hub genes related to the tumor condition. In particular we carried out a multi step analysis:
- extrapolation and preprocessing the relevant data;
- construction of Differentially Expressed Genes (DEGs);
- construction of Coexpression Networks (exploiting hard-thresholding and comparing it with soft-thresholding), and identification of candidate hub genes by considering different centrality measures;
- analysis (with different similarity measures) of Differential Coexpressed Network based on DEGs;
- extrapolation of communities (with different methods and via clustering techniques) in Patient Similarity Networks.

### What's in here?
- The notebook with alll the code we used to carry out the project `DEPM-1_proj_group-14.ipynb`
- The reprt with our findings `report.pdf`.
- Prvious versions of the notebook of the project called with different names, eg. `main.ipynb`, `DEPM_1.ipynb`, etc...

### Dataset
All the relevant data was extracted from the Genomic Data Commons Data Portal using custom R code to carry out the necessary queries. See https://portal.gdc.cancer.gov/projects/TCGA-PRAD.

### Disclamair
This project was part of a course of Digital Epidemiology and Precision Medicin at Sapienza University of Rome held by Prof. M. Petti. 
