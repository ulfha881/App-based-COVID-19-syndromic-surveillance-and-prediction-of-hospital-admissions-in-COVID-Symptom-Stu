# App-based-COVID-19-syndromic-surveillance-and-prediction-of-hospital-admissions-The-COVID-Symptom-S
Codes and example data set for Covid Symptom Study Sweden

This folder contains all codes used for the paper "App-based COVID-19 syndromic surveillance and prediction of hospital admissions: The COVID Symptom Study Sweden". The codes can be run in order in Linux from the file "0_Run.sh". The original datasets can unfortunately not be attached due to the size and confidentiality issues, but mock datasets are included which can be used when running the code, but does not represent real individuals. The code can be run using these mock datasets. The Swedish mock datasets are located in "/proj/sens2020559/COVID-19/OriginalData" and the UK mock datasets in "/proj/sens2020559/COVID-19/OriginalData" and "/proj/sens2020559/georgioray/Split_weeks". Datasets needed to reproduce the figures and supplementary figures are located in "/proj/sens2020559/COVID-19/Figures"

All codes needed for running the analyses are located in "/proj/sens2020559/COVID-19/Codes". The bash file "0_Run.sh" runs every other code in order from beginning to end to produce all output, including sensitivity analyses. The 'sed' lines are for changing global options in the code (which is why some codes are run several times). The GitHub folder structure reproduces the folder structure used when running the code. The output will be in the "MyData" and "Results" folders and sub-folders.

The codes have been run on CentOS Linux 7 (Core).  The softwares used are R 3.6.1 and Stata/MP 15.1. Note that a number of R libraries have to be imported, for example data.table, haven, lubridate. The libraries required are stated in the header of each individual code. 

The full code with the full dataset is preferably run on a node of 256 GB, and requires one or two days. The mock datasets should have an expected running time of a couple of hours.
