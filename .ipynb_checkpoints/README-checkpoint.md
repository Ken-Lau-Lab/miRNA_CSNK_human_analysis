# miRNA_CSNK_human_analysis
## This github contains code for the figures exploring oncogenic KRAS suppression on global miRNA function in human patient samples

## Data Availability: 
- discovery dataset without raw data can be found on HTAN portal:
- Annotated ASC, SSC and GOB h5ads can be found in this dropbox folder:
- Annotated disc_header.h5ad (only gene scores and other data, no count matrix) can also be found in the dropbox folder 

## Notebooks:
- score_genes.ipynb: this shows the steps to generate the gene scores or other related labels for the entire discovery set. The results should be in disc_header.h5ad, or can be generated from the HTAN Discovery raw dataset 
- visualize_disc.ipynb: this contains the code to generate the umaps of the discovery dataset in the paper 
- subsets.ipynb: this shows the steps to extract the subsets from the annotated discovery set, steps to zoom-in the umaps and the resulting umap visualizations in the paper 
- correlation.ipynb: this contains the steps to make the scatter plots for each subsets between their CSNK gene expression and miRNA target gene scores. Linear regression and correlation analysis steps are included 

