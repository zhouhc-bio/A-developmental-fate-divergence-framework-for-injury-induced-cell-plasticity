# A developmental fate-divergence framework for injury-induced cell plasticity

This repository contains code, source data and reproducibility documentation for the manuscript:

**A developmental fate-divergence framework for injury-induced cell plasticity**

## Overview

This study evaluates a developmental fate-divergence framework for injury-induced cell plasticity. The central premise is that plasticity is permissive rather than instructive: injury-associated plasticity can increase accessibility to multiple cell-state outcomes, but regenerative, senescence-associated and tumor-like trajectories diverge according to positional-program activity, fate-stabilization logic and tissue-level organization.

The repository supports analyses related to:

- shared high-plasticity state space
- stemness-associated accessibility
- Wnt/MYC-associated plasticity
- positional-program activity
- fate-stabilization and lineage-restriction logic
- senescence-associated repair failure / SAT-like states
- axolotl regeneration as a negative boundary test
- tumor-like plasticity as a distinct operational high-plasticity branch

## Repository structure

plasticity-fate-divergence/
  README.md
  LICENSE
  CITATION.cff
  .gitignore
  requirements.txt
  environment.yml

  scripts/
  src/
  source_data/
  supplementary/
  docs/
  figures/

## Public datasets

This study reanalyses publicly available datasets. Raw public datasets are not redistributed in this repository and should be obtained from the original database records.

Dataset accessions used in the manuscript include:

- GSE153596
- GSE130381
- GSE295225
- GSE315993
- GSE195655

A dataset-use table is provided in:

docs/Public_Data_Accessions.xlsx

## Source data

Main quantitative source data are provided in:

source_data/Source_Data_Main_Figures.xlsx

Conceptual panels are marked as having no quantitative source data. Missing or unrecoverable items are documented rather than reconstructed.

## Reproducibility

Figure-to-data and figure-to-code mappings are provided in:

docs/Reproducibility_Manifest.xlsx
docs/Code_Manifest.xlsx

Each main figure or result is mapped to the corresponding dataset, script, source-data sheet and reproducibility status where available.

## Code

Core analysis scripts are located in:

scripts/

Shared utility functions are located in:

src/

The repository is intended to provide a transparent, reviewable record of the code and source-data workflow supporting the manuscript. Some large public single-cell datasets and processed intermediate objects are not redistributed because of file size or database-access constraints.

## Environment

A Python environment can be created with:

conda env create -f environment.yml
conda activate plasticity-fate-divergence

Alternatively, dependencies can be installed with:

pip install -r requirements.txt

Package versions should be checked against the analysis environment used for final figure and source-data generation.

## Limitations

Some legacy processed objects or intermediate files may not be redistributed in this public repository. Items that were not recoverable from available project files are listed in:

supplementary/Unrecoverable_Items_Audit.xlsx

Unrecoverable values were not reconstructed or invented.

## Citation

If you use this repository, please cite the associated manuscript and the archived repository DOI when available.

Repository DOI: pending Zenodo release

## Contact

Correspondence should be addressed to:

Hancheng Zhou  
samvniiy@icloud.com
An institutional education email address will be added to this repository after September 2026.
