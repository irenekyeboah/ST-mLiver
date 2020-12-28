# ST Liver 

This repository contains data to produce data presented in "Title", these include data, scripts ..

## Structure

* `data` - contains processed data to be used in the analysis
	* `gene lists`- 
	* `h5ad-cca`- 
	* `meta`- 
	* `stereoscope`- 
* scripts - contains processing scripts and notebooks
	* `R-markdown-methods.Rmd` - contains a R markdown script to perform canonical correlation analyis, clustering and DGEA, tissue visualization, correlation analysis, visualization of single cell integration using single cell data of the [Mouse Cell Atlas](https://www.cell.com/cell/fulltext/S0092-8674%2818%2930116-8) and comparative analyses with published data from [Halpern et al](https://www.nature.com/articles/nature21065)
	* `MultiCCA.R` - contains code for the modified canonical correlation analysis function used in `R-markdown-methods.Rmd`
* res - holds results generated from the analysis
* rsc - are resources of interest

## Additional Information
* the `.h5ad` files are generated by using the script `.prepare-data`
* the counts data in the `.h5ad` files are normalized data, performed by `sctransform` in `R`
* larger files (>10Mb) are managed by the LFS system
