# Data and scripts for reproducing the analyses in the SPMP project

This repository contains data and scripts used for our Singapore Platinum Metagenomes Project (SPMP) study.

## Directory structure

- [envs](envs): Conda environment used for this project
- [scripts](scripts): folder containing code used for this project (jupyter and Rmarkdown)
- [tables](tables): Input data used

## Software versions

Python - jupyter and R version 4.1.0 with tidyverse version 1.3.1 

## Unusual library

Most of the figure has been generated using [seahorse](https://github.com/jsgounot/Seahorse), a custom plotting library based on seaborn.

## Raw data availability

 - Raw sequencing data has been uploaded to [European Nucleotide Archive](https://www.ebi.ac.uk/ena/data/view/PRJEB49168)
 - Assemblies and annotations will be available at Figshare

## Citation

A preprint of our manuscript is available on [biorxiv](https://doi.org/10.1101/2022.05.05.490740).

## Contact

Please direct any questions or feedback to [Jean-Sebastien Gounot](mailto:Jean-Sebastien@gis.a-star.edu.sg) and [Niranjan Nagarajan](mailto:nagarajann@gis.a-star.edu.sg).

## Figures to script relationship

| Figure title     | Script file                         |
| ---------------- | ----------------------------------- |
| Figure 1.A       | `assembly_stats.ipynb`              |
| Figure 1.B left  | `kraken_self_single_analysis.ipynb` |
| Figure 1.B right | `kraken_self_single_analysis.ipynb` |
| Figure 1.C       | `kraken_self_single_analysis.ipynb` |
| Figure 1.D       | `assembly_stats.ipynb`              |
| Figure 1.E       | `assembly_stats.ipynb`              |
| Figure 1.F       | `gtdb_improvement.ipynb`            |
| Figure 1.G       | `gtdb_improvement.ipynb`            |
| Figure 2.A       | `rarefaction_inext_run.ipynb`       |
| Figure 2.B       | `assembly_stats.ipynb`              |
| Figure 2.C       | `strains_clustering.ipynb`          |
| Figure 2.D       | `BGC_class_barplot.Rmd`             |
| Figure 2.E       | Schematic representation            |
| Figure 2.F       |                                     |
| S. Figure 1      | `reads_statistics.ipynb`            |
| S. Figure 2.A    | `reads_statistics.ipynb`            |
| S. Figure 2.B    | `reads_statistics.ipynb`            |
| S. Figure 3      | `kraken_self_single_analysis.ipynb` |
| S. Figure 4      | `kraken_self_single_analysis.ipynb` |
| S. Figure 5.A    | `assembly_stats.ipynb`              |
| S. Figure 5.B    | `assembly_stats.ipynb`              |
| S. Figure 6.A    | `assembly_stats.ipynb`              |
| S. Figure 6.B    | `assembly_stats.ipynb`              |
| S. Figure 7      | `bracken_self_combine.ipynb`        |
| S. Figure 8.A    | `kraken_cre.ipynb`                  |
| S. Figure 8.B    | `strains_mapping.ipynb`             |
| S. Figure 9      | Schematic representation            |
| S. Figure 10.A   | `assembly_stats.ipynb`              |
| S. Figure 10.B   | `assembly_stats.ipynb`              |
| S. Figure 11.A   | `bracken_self_combine.ipynb`        |
| S. Figure 11.B   | `novel612.ipynb`                    |
| S. Figure 12.A   | `strains_clustering.ipynb`          |
| S. Figure 12.B   | `strains_clustering.ipynb`          |
| S. Figure 13     |                                     |
| S. Figure 14     |                                     |

