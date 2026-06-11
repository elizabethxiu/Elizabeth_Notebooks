# 🧬 Welcome to the Zamarin Lab Scimap Pipeline!

## 🔬 What is this pipeline?
A Jupyter notebook-based pipeline for analyzing multiplexed CyCIF tissue imaging data. It takes MCMICRO quantification output through cell phenotyping, drawing ROIs, calculating immune densities, and spatial analysis —- creating different figures at each stage.

## 📒 What is hosted here?

`Elizabeth_step1_NoPC_scimap_processing.ipynb` | Gate markers, phenotype cells, draw ROIs 

`more visualization.ipynb` | Spatial analysis figures

`Elizabeth_step2_nopc_immunedensity.ipynb` | Compute immune cell densities per ROI 

`Elizabeth_step3_nopc_immune_plots.ipynb` | Generate density boxplots across genotypes 

## ✍️ Notes
- All file paths are set in the configuration cell at the top of each notebook
- Step 1 requires two manual steps -- marker gating (minerva gater) and ROI drawing (napari)
