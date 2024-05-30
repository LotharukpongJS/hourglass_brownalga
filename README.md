# Transcriptomic hourglass in brown algae
Exploring the transcriptomic hourglass in three brown algal species (_Fucus distichus_, _Fucus serratus_, & _Ectocarpus_ species 7). BioProject number (PRJNA1090323).

## Documentation
I have rendered all the analysis (in Rmd) as HTML files. I have included all the necessary R scripts to generate the figures and interpretation of the brown algal developmental transcriptome datasets. Both `2_evolutionary_transcriptomics.Rmd` and `3_further_evolutionary_transcriptomics.Rmd` scripts can be run from the data available in the github repository (https://github.com/LotharukpongJS/hourglass_brownalga), which was generated using step 1 "Obtaining RNA-seq data and gene age data".

### 1 – Obtaining RNA-seq data and gene age data (available [here](https://lotharukpongjs.github.io/hourglass_brownalga/1_preprocessing.html))
* RNA-seq quantification
* Gene age inference
* Processing RNA-seq and gene age data 
* Create input for myTAI
* Visualise gene age distribution
* Orthogroup abundance

### 2 – Evolutionary transcriptomics analyses (available [here](https://lotharukpongjs.github.io/hourglass_brownalga/2_evolutionary_transcriptomics.html))
* Evolutionary transcriptome in _Fucus_ embryogenesis
* Evolutionary transcriptome in _Ectocarpus_
* Evolutionary transcriptome across _Fucus_ tissues
* Mean expression of different PS

### 3 – Further evolutionary transcriptomics analyses (available [here](https://lotharukpongjs.github.io/hourglass_brownalga/3_further_evolutionary_transcriptomics.html))
* Evolutionary transcriptome in Fucus embryogenesis using RNA-seq that has been ‘denoised’ using noisyR
* Stats for male-female difference in Ectocarpus
* Tau profiles
* TDI across _Ectocarpus_ life cycle stages
* Visualisation of orthogroups
* pTAI analysis
* GO analysis of top contributor gene (from `pTAI`)

### 4 – Further evolutionary transcriptomics analyses (addressing reviewers) (available [here](https://lotharukpongjs.github.io/hourglass_brownalga/4_address_reviewer_comments.html)). 
NOTE: the version of myTAI is newer due to an addition of the PairwiseTest(). However, the lower-level functions such as `cpp_TAI` remain the same, thus, results from other functions should not differ.

* Difference in TAI between matSP stages.

At the end of each of these scripts, I list the software and versions used. R code here was run on MacBook Pro (Apple M1 Chip, 16 GB Memory, macOS Ventura v13.4.1). Some of the preprocessing step (e.g., RNA-seq quantification, gene age inference, interproscan) were run on a high performance compute cluster. Otherwise, the rest of the script should take less than 30 minutes to run on a "normal" desktop computer.
