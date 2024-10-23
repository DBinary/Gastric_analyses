# ScRNA-seq and Spatial Transcriptomics Analyses

This repository includes all the scripts needed for the scRNA-seq and spatial transcriptomics analyses mentioned in the following manuscript:

**Lei Hu, et al. (2024). "The Immunosuppressive Landscape of the Gastric Mucosa under Helicobacter pylori Infection." (In submission)**

## Table of Contents

- [Introduction](#introduction)
  - [Data Availability](#data-availability)
  - [Other Information](#other-information)
- [Main Figure](#Main_scripts)
  - [Quality Control (QC) and Clustering.](./Main_Figure/Gastric_Origin_Data_Preprocess.ipynb)
  - [(Figure1)-A Single Cell and Spatial Transcriptomic Landscape of the Gastric Mucosal Microenvironment.](./Main_Figure/Gastric_Figure1.ipynb)
  - [(Figure2)-Infiltration Characteristics of NK/T cells in Gastric Mucosal with H. pylori Infection](./Main_Figure/Gastric_Figure2.ipynb)
  - [(Figure3)-Heterogeneity and Dynamics of Exhausted T Cells.](./Main_Figure/Gastric_Figure3.ipynb)
  - [(Figure4_part1)-Profiling the Epithelial Cells Infected with H. pylori at Single-Cell Level.](./Main_Figure/Gastric_Figure4_1.ipynb)
  - [(Figure4_part2)-Profiling the Epithelial Cells Infected with H. pylori at Single-Cell Level.](./Main_Figure/Gastric_Figure4_2.ipynb)
  - [Spatial Transcriptomics Analysis](./Main_Figure/Spatial_Transcriptomics_Analysis.ipynb)

- [Supplementary Figure](#Supplementary_scripts)
  - [Figure1_related](./Supplementary_Figure/Figure1_related)
    - [(sFigure1)-Characterization of the Gastric Mucosal Microenvironment by ScRNA-seq.](./Supplementary_Figure/Figure1_related/Gastric_sFigure1.ipynb)  
    - [(sFigure2)-The Heterogeneity of Cell Types and Patients at Singlecell Resolution.](./Supplementary_Figure/Figure1_related/Gastric_sFigure2.ipynb)
  - [Figure2_related](./Supplementary_Figure/Figure2_related)
    - [(sFigure3)-Characterization of Signature Genes of Sub Cell Types of CD8+ and CD4+ T Cells.](./Supplementary_Figure/Figure2_related/Gastric_sFigure3.ipynb)
    - [(sFigure4)-Data Integration of NK/T Cells.](./Supplementary_Figure/Figure2_related/Gastric_sFigure4.ipynb)
    - [(sFigure5)-Analysis of CD8+ and CD4+ T Cell Subset Distributions.](./Supplementary_Figure/Figure2_related/Gastric_sFigure5.ipynb)
    - [(sFigure6)-Infiltration Characteristics of B Cells and Plasma Cells in Gastric Mucosal with H. pylori Infection.](./Supplementary_Figure/Figure2_related/Gastric_sFigure6.ipynb)
    - [(sFigure7)-Infiltration Characteristics of Meyloid Cells in Gastric Mucosal with H. pylori Infection.](./Supplementary_Figure/Figure2_related/Gastric_sFigure7.ipynb)
  - [Figure3_related](./Supplementary_Figure/Figure3_related)
    - [(sFigure8)-The Developmental Trajectories of CD4+ and CD8+ T Cells.](./Supplementary_Figure/Figure3_related/Gastric_sFigure8.ipynb)
    - [(sFigure9)-The Developmental Trajectories of CD8+ CXCL13+ Tex Cells.](./Supplementary_Figure/Figure3_related/Gastric_sFigure9.ipynb)
    - [(sFigure10)-The Developmental Trajectories of CD8+ MAIT Cells.](./Supplementary_Figure/Figure3_related/Gastric_sFigure10.ipynb)
    - [(sFigure11)-The Developmental Trajectories of Exhausted CD4+ T Cells.](./Supplementary_Figure/Figure3_related/Gastric_sFigure11.ipynb)
    - [(sFigure12)-Pathway Activitiy Characteristic of Exhausted T Cells.](./Supplementary_Figure/Figure3_related/Gastric_sFigure12.ipynb)
    - [(sFigure13)-Analysis of Correlations Among T Cell Subtype Frequencies.](./Supplementary_Figure/Figure3_related/Gastric_sFigure13.ipynb)
    - [(sFigure14)-Infiltration Characteristics of CD8+ MAIT Cells in Gastric Mucosal with H. pylori Infection.](./Supplementary_Figure/Figure3_related/Gastric_sFigure14.ipynb)
    - [(sFigure15)-Driver Regulators of Cell Fate Analysis of Exhausted T Cells.](./Supplementary_Figure/Figure3_related/Gastric_sFigure15.ipynb)
  - [Figure4_related](./Supplementary_Figure/Figure4_related)
    - [(sFigure16)-The Marker Genes Distribution Across Sub Cell Types of Epithelial Cells at Single Cell Resolution.](./Supplementary_Figure/Figure4_related/Gastric_sFigure16.ipynb)
    - [(sFigure17)-Characteristics of Intestinal Metaplasia Process in Gastric Mucosal with H. pylori Infection.](./Supplementary_Figure/Figure4_related/Gastric_sFigure17.ipynb)
    - [(sFigure18)-GeneTrajectory Deconvolves the Intestinal Metaplasia Processes in H. pylori Infection.](./Supplementary_Figure/Figure4_related/Gastric_sFigure18.ipynb)
    - [(sFigure19)-Functional Analysis for Subtypes of Enterocytes in H. pylori Infection.](./Supplementary_Figure/Figure4_related/Gastric_sFigure19.ipynb)
    - [(sFigure20_part1)-Using CellphoneDB to Predict Cell-Cell Interactions Based on Ligand-Receptor Interactions.](./Supplementary_Figure/Figure4_related/Gastric_sFigure20_1.ipynb)
    - [(sFigure20_part2)-Using CellphoneDB to Predict Cell-Cell Interactions Based on Ligand-Receptor Interactions.](./Supplementary_Figure/Figure4_related/Gastric_sFigure20_2.ipynb)

## Introduction

This repository includes all the scripts needed for the scRNA-seq and spatial transcriptomics analyses mentioned in our manuscript. 

The `Main Figure` category includes scripts that are directly related to the main figures in the manuscript, while the `Supplementary Figure` category includes scripts that are related to the supplementary figures in the manuscript.


### Data Availability

The processed scRNA-seq data required to reproduce the analysis and figures have been deposited on Zenodo database (https://zenodo.org/records/13968284). All the data generated and materials used in this manuscript are available upon request.

**For data security reasons, the data on Zenodo will only be made public after the article has been accepted.**


### Other Information
You will need to install packages that are listed in the header of scripts prior to running them.

Please reach me at hulei@westlake.edu.cn if there are questions about the analysis.