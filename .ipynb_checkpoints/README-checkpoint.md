# miRNA_CSNK_human_analysis
## This github contains code for the figures exploring oncogenic KRAS suppression on global miRNA function in human patient samples

## Data Availability: 
- discovery dataset with raw data can be found in this dropbox file: https://www.dropbox.com/s/7f1w2zw0pu7sk1v/VUMC_HTAN_DIS_EPI_V2.h5ad?dl=0
- Annotated ASC, SSC and GOB and disc_header h5ads can be found in this dropbox folder: https://www.dropbox.com/sh/hy9hy9a4mchgi82/AACZkZlLLCzo8P1r-9bUdsqTa?dl=0 

## Notebooks:
- <font color = 'green'>score_genes.ipynb</font>: this notebook shows the steps to generate gene scores or other related labels for the entire discovery set. The results should be in disc_header.h5ad's .obs field, or can be generated from the HTAN Discovery raw dataset 
- <font color = 'green'>visualize_disc.ipynb</font>: this notebook contains the code to generate the umaps of the discovery dataset in the paper 
- <font color = 'green'>subsets.ipynb</font>: this notebook shows the steps to extract subsets from the annotated discovery set, steps to zoom-in the umaps and the resulting umap visualizations in the paper 
- <font color = 'green'>correlation.ipynb</font>: this notebook contains the steps to make the scatter plots for each subsets between their CSNK gene expression and miRNA target gene scores. Linear regression and correlation analysis steps are included 
- <font color = 'green'>boxplots.ipynb</font>: this notebook contains the steps to generate the box plots of subsets's all-miRNA target scores on selected miRNA families with statistical tests and annotations
