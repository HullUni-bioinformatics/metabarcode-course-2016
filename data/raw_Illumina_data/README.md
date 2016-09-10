## Downloading Illumina data from SRA

In the course of our excercises we will be analysing previously published, real life Illumina data from:

Hänfling B, Lawson Handley L, Read DS, Hahn C, Li J, Nichols P, Blackman RC, Oliver A, Winfield IJ. (2016). Environmental DNA metabarcoding of lake fish communities reflects long-term data from established survey methods. _Molecular Ecology_ 25(13):3101-19. DOI: 10.1111/mec.13660. (open on [ResearchGate](https://www.researchgate.net/publication/301550636_Environmental_DNA_metabarcoding_of_lake_fish_communities_reflects_long-term_data_from_established_survey_methods))

In this directory you'll find a Jupyter [notebook](https://github.com/HullUni-bioinformatics/metabarcode-course-2016/blob/master/data/raw_Illumina_data/Download_Illumina_data_from_SRA.ipynb) taking you through the download of the raw Illumina reads from a subset of the samples analysed in the above study. 

The notebook will first download and install the program required for the download. Then it will parse [this](https://github.com/HullUni-bioinformatics/metabarcode-course-2016/blob/master/data/raw_Illumina_data/sample_metadata/Sample_accessions_LW.tsv) file and will download the reads (MiSeq, paired end) for 58 samples from SRA. 
You can find extensive metadata for all samples [here](https://github.com/HullUni-bioinformatics/metabarcode-course-2016/blob/master/data/raw_Illumina_data/sample_metadata/Sample_metadata.csv).
