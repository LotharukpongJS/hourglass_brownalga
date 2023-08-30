# Transcriptomic hourglass in brown algae
Exploring the transcriptomic hourglass in three brown algal species (_Fucus distichus_, _Fucus serratus_, & _Ectocarpus_ species 7).

## Documentation
I have rendered all the analysis (in Rmd) as HTML files. I include all the necessary R scripts to generate the figures and interpretation of the brown algal developmental transcriptome datasets.

### 1 – Preprocessing the data (each step includes visualisation too) 
* [1.0 Save counts (also de-noised data)](https://lotharukpongjs.github.io/hourglass_brownalga/1_0_savecounts.html)
* [1.1 Visualise the distribution of RNA-seq counts/abundance](https://lotharukpongjs.github.io/hourglass_brownalga/1_1_visabundance.html)
* [1.2 Save the PES (input dataset for myTAI; TAI analysis)](https://lotharukpongjs.github.io/hourglass_brownalga/1_2_savePES.html)
* [1.2.1 Save the DES (input dataset for myTAI; TDI analysis)](https://lotharukpongjs.github.io/hourglass_brownalga/1_2_1_saveDES.html)
* [1.3 Transform the PES data (for rlog, log2, sqrt, rank transforms etc)](https://lotharukpongjs.github.io/hourglass_brownalga/1_3_transformations.html)
* [1.3.1 Transform the DES data (for rlog, log2, sqrt, rank transforms etc)](https://lotharukpongjs.github.io/hourglass_brownalga/1_3_1_transformation_DES.html)
* [1.4 Save the DESeq2 dataset (including LRT).](https://lotharukpongjs.github.io/hourglass_brownalga/1_4_dds_save.html)
* [1.5 Visualise the distribution of gene ages.](https://lotharukpongjs.github.io/hourglass_brownalga/1_5_visage.html)
* [1.6 Import and save orthogroup counts/abundance for comparative transcriptomics.](https://lotharukpongjs.github.io/hourglass_brownalga/1_6_OG_as_genes_import.html)

### 2 – TAI analysis
* [2.0 TAI profiles across development](https://lotharukpongjs.github.io/hourglass_brownalga/2_0_TAI_profiles.html)
* [2.0.1 Stability of standard deviation in the TAI analysis](https://lotharukpongjs.github.io/hourglass_brownalga/2_0_1_sd_stability.html)
* [2.0.2 TAI profiles for low input data](https://lotharukpongjs.github.io/hourglass_brownalga/2_0_2_low_input.html)
* [2.0.4 TAI profiles for only developmental genes (DEGs)](https://lotharukpongjs.github.io/hourglass_brownalga/2_0_4_TAI_devgenes.html)
* [2.0.5 TAI profiles for de-noised data](https://lotharukpongjs.github.io/hourglass_brownalga/2_0_5_TAI_denoised.html)
* [2.1 TAI between Fucus matSP tissues](https://lotharukpongjs.github.io/hourglass_brownalga/2_1_TAI_tissues.html)
* [2.3 TAI enrichment](https://lotharukpongjs.github.io/hourglass_brownalga/2_3_TAI_enrichment.html)

### 3 – TDI analysis 
* [3.0 TDI profiles across development](https://lotharukpongjs.github.io/hourglass_brownalga/3_0_TDI_profiles.html)
* [3.0.2 TDI profiles for low input data](https://lotharukpongjs.github.io/hourglass_brownalga/3_0_2_low_input_TDI.html)
* [3.0.4 TDI profiles for only developmental genes (DEGs)](https://lotharukpongjs.github.io/hourglass_brownalga/3_0_4_TDI_devgenes.html)
* [3.0.5 TDI profiles for de-noised data](https://lotharukpongjs.github.io/hourglass_brownalga/3_0_5_TDI_denoised.html)
* [3.1 TDI between Fucus matSP tissues](https://lotharukpongjs.github.io/hourglass_brownalga/3_1_TDI_tissues.html)
* [3.3 TDI enrichment](https://lotharukpongjs.github.io/hourglass_brownalga/3_3_TDI_enrichment.html)

### 4 – Orthogroup (OG) analysis
* [4.0 OG visualisation (comparative transcriptomics)](https://lotharukpongjs.github.io/hourglass_brownalga/4_0_OG_visualisation.html)
* [4.0.1 OG visualisation (comparative transcriptomics) with sqrt transform](https://lotharukpongjs.github.io/hourglass_brownalga/4_0_1_OG_visualisation_sqrt.html)
* [4.1 OG differential expression analysis](https://lotharukpongjs.github.io/hourglass_brownalga/4_1_OG_DEG.html)
* [4.2 OG analysis for “recapitulation patterns”](https://lotharukpongjs.github.io/hourglass_brownalga/4_2_OG_recapitulation.html)

### 5 – Gene ontology (GO) analysis 
* [5.0 GO enrichment analysis](https://lotharukpongjs.github.io/hourglass_brownalga/5_0_GO_enrichment.html)
* [5.0.1 GO enrichment analysis with denoised data](https://lotharukpongjs.github.io/hourglass_brownalga/5_0_1_GO_enrichment_denoised.html)
* [5.1 PS GO enrichment analysis](https://lotharukpongjs.github.io/hourglass_brownalga/5_1_PS_DEG.html)
