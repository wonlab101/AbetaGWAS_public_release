# AbetaGWAS_public_release

> This repository includes code and plots. Exploratory analysis and intermediate processing files are too large for this repository.

> The summary statistic are available from Zendo at [link]. 

## Description

> A cross-ancestry GWAS meta-analysis of β-amyloid deposition in East Asian and European populations identified a novel SORL1 locus and highlighted its differential expression in microglia associated with β-amyloid positivity.


<p align="center">
  <img src="/figures/manhattan_plot.pdf" width="100" />
</p>

## scripts
> sciprts for Korean single-cell RNA sequencing dataset.  

* `processing_SMC_brain.ipynb`: was used to merge all dataset and perform the Quality Control(QC) using SCANPY
* `report_SMC_brain.ipynb`: was used to plot the figure for paper using SCANPY
* `DEG_SMC_Brain.Rmd`: was used to conduct the differential expression gene analysis using the MAST


## Authors

Contributors names and contact info

- Hong-Hee Won (wonhh@skku.edu)

- Sang-Hyuk Jung (Sanghyuk.Jung@pennmedicine.upenn.edu)

- Beomjin Jang (beomjin.jang@skku.edu)


## Acknowledgments

Inspiration, code snippets, etc.
* [hail](https://github.com/hail-is/hail)
* [METAL](https://genome.sph.umich.edu/wiki/METAL_Documentation)
* [COLOC](https://github.com/chr1swallace/coloc)
* [SCANPY](https://scanpy.readthedocs.io/en/stable/installation.html)
* [MAST](https://rglab.github.io/MAST/)
