## Exercise 4 - Reference database curation ##

This exercise will focus on the assessment and phylogenetic curation of custom reference databases for metabarcoding applications.

We will be running [SATIVA](http://nar.oxfordjournals.org/content/44/11/5022.long) a tool for 'Phylogeny-aware identification and correction of taxonomically mislabeled sequences'.
 
To run `SATIVA` on the example dataset that we have prepared, please follow the instructions in [this](https://github.com/HullUni-bioinformatics/metabarcode-course-2016/blob/master/data/exercise-4/supplementary_material/run_SATIVA/Install_and_run_SATIVA.ipynb) notebook.
All necessary input files for the test run are present in the directory `input_data`. Full documentation on how these input data were generated are present in the directory `supplementary_data`. See [here](https://github.com/HullUni-bioinformatics/metabarcode-course-2016/blob/master/data/exercise-4/supplementary_material/build_tree/build_reduced_tree_for_ref_db_discussion.ipynb) for how we generated the example dataset, produced the alignment (input for SATIVA) and inferred a phylogenetic tree that we use for [visualization](https://github.com/HullUni-bioinformatics/metabarcode-course-2016/blob/master/data/exercise-4/supplementary_material/build_tree/CytB_mafftLinsi_clipped_raxml_SATIVA_annotated.png) of `SATIVA` results. See [here](https://github.com/HullUni-bioinformatics/metabarcode-course-2016/blob/master/data/exercise-4/supplementary_material/run_SATIVA/create_SATIVA_tax_file_from_gb.ipynb) for how we produced the SATIVA taxonomy [file](https://github.com/HullUni-bioinformatics/metabarcode-course-2016/blob/master/data/exercise-4/supplementary_material/run_SATIVA/tax_for_SATIVA.tax) from a Genbank formatted set of sequences.

Find some discussion on the results in the course [manual](https://docs.google.com/document/d/1h9d0JrTsDLzsOV5klMkD47807dWTmcXN3uxoYp0ei64/edit#heading=h.47vs6jk5xu41).
