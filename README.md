# Venlafaxine Mesocosm Amplicon Analysis
This repository contains amplicon sequencing analyses (16S and 18S) for the Venlafaxine mesocosm experiment at the Experimental Lakes Area (ELA), focusing on:

_**Sample types:** water, biofilm, and sediment (2021)_

## Analyses: data processing, diversity, community composition, and differential abundance testing

## Workflow
For each dataset (16S and 18S), scripts are organized modularly:

_1_create_phyloseq – Import, filter, and normalize data_

_2_alphadiversity – Calculate richness and diversity metrics_

_3_betadiversity – Ordination (NMDS/PCoA) and PERMANOVA_

_4_barplots – Visualize taxa composition across treatments_

_5_MaAsLin3 – Differential abundance testing_

All metadata and input data are in the data/ folder within each dataset directory, while outputs (plots, tables, RData) are saved in R_output/.


## Repository Structure

├── **16S/**

│   ├── data/                       # Metadata and input data for 16S

│   ├── R_output/                   # Outputs (plots, RData, tables) for 16S

│   ├── Venla16_1_create_phyloseq_MEsser.Rmd

│   ├── Venla16_2_alphadiversity_MEsser.Rmd

│   ├── Venla16_3_betadiversity_MEsser.Rmd

│   ├── Venla16_4_barplots_MEsser.Rmd

│   └── Venla16_5_MaAsLin3_MEsser.Rmd

│

├── **18S/**

│   ├── data/                       # Metadata and input data for 18S

│   ├── R_output/                   # Outputs (plots, RData, tables) for 18S

│   ├── Venla18_1_create_physeq_MEsser.Rmd

│   ├── Venla18_2_alphadiversity_MEsser.Rmd

│   ├── Venla18_3_betadiversity_MEsser.Rmd

│   ├── Venla18_4_barplots_MEsser.Rmd

│   └── Venla18_5_MaAsLin3_MEsser.Rmd

