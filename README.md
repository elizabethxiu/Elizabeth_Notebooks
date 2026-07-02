# 🧬 Welcome to the Zamarin Lab Scimap Pipeline!

## 🔬 What is this pipeline?
A Jupyter notebook-based pipeline for analyzing multiplexed CyCIF tissue imaging data. It takes MCMICRO quantification output through cell phenotyping, drawing ROIs, calculating immune densities, and spatial analysis —- creating different figures at each stage.

## 📒 What is hosted here?

`01_SCIMAP_sample_processing.ipynb` | Gate markers, phenotype cells, draw ROIs 

`02_SCIMAP_immune_density.ipynb` | Compute immune cell densities per ROI

`03_SCIMAP_immune_plots.ipynb` | Generate density boxplots across genotypes

`04_SCIMAP_within_sample_visuals.ipynb` | Single-sample spatial analysis figures

`05_SCIMAP_across_sample_visuals.ipynb` | Multi-sample spatial analysis figures 

## ✍️ Notes
- All file paths are set in the configuration cell at the top of each notebook
- Step 1 requires two manual steps -- marker gating (minerva gater) and ROI drawing (napari)
