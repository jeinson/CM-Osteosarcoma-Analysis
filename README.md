# Computational Methods Spring 2018

This repository contains scripts used to analyze an osteosarcoma dataset, based on patients master regulator signatures. The script is presented in the form of a jupyter notebook, which is run with an R kernel enabled. 

The required packages are listed in the first cell notebook. All other files needed are in the SourceCode_files directory

## SourceCode_files

1. `TARGET_OS_Discovery_ClinicalData.csv` This file contains all of the patient metadata, like relapse status, metastatic disease status, and survival post treatment.
2. `TOS_TPM.txt` Read counts measured in transcripts per million, which was downloaded directly from the TARGET Osteosarcoma study. This is the input for viper. 
3. `ens2entrez.rda` This has information for mapping genes labels from ensembl ids to entrez ids. This is necessary for downstream MR processing. 
3. `viper_dset.csv` A precomputed table of master regulator signatures for each patient. The process used to generate this file is described in detail in the report. 