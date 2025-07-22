# PDZ_homologs
Welcome to the GitHub repository for the following publication: [*The evolution of allostery in a protein family* (Marti-Aranda and Lehner 2025)](https://www.biorxiv.org/content/10.1101/2025.06.20.660748v1).

Here you'll find source code for computational analyses and to reproduce the figures in the paper.

# Required Data
The read counts (DiMSum output), fitness scores, MoCHI weights, and required miscellaneous files should be downloaded from [here](https://zenodo.org/records/15978782) and copied to your "base_dir" folder for running the analysis.

# System requirements
The code is ran on RMarkdown

Code was tested with Mac OSX and with R version 4.5.0 and with the following main dependencies:
tidyr_1.3.1
Biostrings_2.77.1
ggplot2_3.5.2    
stringr_1.5.1
seqinr_4.2-36       
dplyr_1.1.4
rstatix_0.7.2
bio3d_2.4-5
data.table_1.17.4

See the HTML files ran for each script for detailed session information in each case.

# installation guide
**Required data**:Download the RMarkdown files together with the required data from [here](https://zenodo.org/records/15978782). 
**Setup Folder Structure**: Place all RMarkdown scripts and additional scripts in the same folder. Extract the contents of the downloaded .zip file into this folder. It also includes all the required data folders and original results.
**Adjust Paths**: In each script, update the base_dir variable (found in the initializing section) to point to your working analysis folder.
The downloaded data includes the necessary folders and files to run all scripts. Refer to the provided .html files to see the expected outputs from the analysis.
