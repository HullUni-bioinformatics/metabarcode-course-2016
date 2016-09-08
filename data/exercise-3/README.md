## Exercise 3 - Cumbrian lakes eDNA ##

In this exercise we will use [metaBEAT](https://github.com/HullUni-bioinformatics/metaBEAT), a tool tailored towards reproducible and efficient analyses of metabarcoding data that we have developed in-house. It is still under active development and will likely be extended further in the future. The pipeline is available in a Docker [container](https://registry.hub.docker.com/u/chrishah/metabeat/) with all necessary dependencies. The Docker image is building on [ReproPhylo](https://registry.hub.docker.com/u/szitenberg/reprophylo/).

The data we will be analyzing are CytB sequences amplified from eDNA samples collected from Lake Windermere, plus 10 samples comprising so-called Mock communities. The experiment was designed to assess the potential of the eDNA approach to assess fish community compositions and has recently been published (Haefnling et al. 2016). A manuscript (Haenfling et al.) The metaBEAT tool is designed as a wrapper around a complete analysis from raw data, performing (optionally) de-multiplexing, quality filtering, clustering along the way, to OTU tables in biom format. It currently supports BLAST and phylogenetic placement (pplacer). The plan is to include further approaches in the future and to allow for efficient and standardized comparative assessments of all approaches.

We will use the metaBEAT pipeline to process the data, from raw Illumina reads, via quality trimming, read merging, and clustering, to a denovo OTU table. We provided a [notebook]() that will guide you through the process. Start a new notebook and try to replicate the steps outlined there.

Back to Google [doc](https://goo.gl/z1MTTf)
