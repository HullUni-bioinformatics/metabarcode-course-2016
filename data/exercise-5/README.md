## Exercise 5 - Taxonomic assignment and comparison of approaches ##

In the course of the exercise in this directory we will attempt to assign taxonomic identity to the set of denovo OTUs obtained from the 57 Lake Windermere eDNA samples that we have produced in [exercise-3](https://github.com/HullUni-bioinformatics/metabarcode-course-2016/tree/master/data/exercise-3).

We will be using a custom phylogenetically curated reference database (details can be found [here](https://github.com/HullUni-bioinformatics/metabarcode-course-2016/tree/master/data/exercise-5/supplementary_data/reference_db). 

Taxonomic assignment will be performed using three different approaches:
 - BLAST based LCA
 - [pplacer](http://matsen.fhcrc.org/pplacer/) (Phylogenetic placement)
 - [Kraken](http://ccb.jhu.edu/software/kraken/MANUAL.html) (k-mer based sequence classification)

We will again be using our custom pipeline metaBEAT to make our lives easier and to facilitate reproducibility. 

Most of the input data you will need for the analysis you have already produced in exercise 3. The rest you can find in the folder `input_data`. The directory `supplementary_data` describes the detailed processing steps and all intermediate files to obtain the input data.

