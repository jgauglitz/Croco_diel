## Temporal proteome shifts in the marine diazotroph Crocosphaera watsonii WH 8501

For more information: [official code website](https://github.com/jgauglitz/Croco_diel)

Marine diazotrophic cyanobacteria provide a key source of new nitrogen into the oceans and are important contributors to primary production. We obtained LC/MS-MS proteomics data from independent diel culturing experiments from the unicellular diazotroph, Crocosphaera watsonii WH8501. High resolution sampling revealed choreographed and distinctly timed protein abundances regulated by the light/dark cycle, with expected patterns of photosynthesis and nitrogen fixation identified in a data-driven manner, as well as additional insights into respiratory protective mechanisms, circadian clock function, and a distinct order in which proteins in the nif operon are detected, with FeS cluster assembly preceding peak abundance measurements of the nitrogenase iron protein.

Using the data and code in this repo, you will be able to reproduce the analyses and figures published in Gauglitz et al., *publication pending*.

If you use the code or data in your own work, please cite the following publication: 

* Gauglitz et al., *publication pending*


## Analyses

Study wide clustering
* time_clustering.ipynb

GO enrichment analysis
* find_enrichment.py
* go-basic.obo

Day vs Night significance test for the two datasets published in the current article, and for the original data from [Saito et al., 2011](https://pubmed.ncbi.nlm.nih.gov/21248230/). 
* signif_proteins.ipynb
* signif_proteins_2015.ipynb
* signif_proteins_2011.ipynb

## Figures

Culture measurements
* cell_growth.ipynb
* N2fix.ipynb

Plotting protein abundance
*  protein_timecourse.ipynb

## Contact

For more information you can visit the [official code website](https://github.com/jgauglitz/Croco_diel) or send an email to [julia.gauglitz@uantwerpen.be](julia.gauglitz@uantwerpen.be).
