# Epigenome Analysis Tutorial
This website contains material for an epigenome analysis tutorial that covers ATAC-seq analysis and integration with TF motifs and gene expression


# Motivation
One of the main molecular mechanisms controlling the temporal and spatial expression of genes is transcriptional regulation. In this process, transcription factors (TFs) bind to the promoter and enhancers in the vicinity of a gene to recruit (or block) the transcriptional machinery and start gene expression. Inference of gene regulatory networks, i.e. factors controlling the expression of a particular gene, is a key challenge when studying development and disease progression. The availability of different experimental assays (Histone ChIP-seq, Dnase1-seq, ATAC-seq, NOME-seq etc.) that allow to map in-vivo chromatin dynamics and gene expression (RNA-seq), has triggered the development of novel computational modelling approaches for accurate prediction of TF binding and activity by integrating these diverse epigenomic datasets. However, in practice, researchers are faced with the problems that come with handling diverse assays, understanding the tools involved and building specific workflows that are tailored to the data they have.

# Goals & Audience

This tutorial is targeted to an audience of bioinformaticians with previous experience in gene expression and next generation sequencing analysis. This intermediary level tutorial will provide you knowledge on the use of state-of-art tools for inference of gene regulatory networks from chromatin and expression data. First, we will review tools to conduct the following analyses: 1) predict regulatory regions from ATAC-seq data, using footprint methods (HINT - Li et al., 2019) and show how to determine cell-specific TF binding in these regions and 2) study how to associate regulatory regions to genes and how to integrate gene expression data (e.g. Schmidt et al. 2016, Durek et al. 2016). 
After introductory presentations we will guide participants through hands on practicals on real data for both parts. 

# Documentation

We have created a ReadTheDocs documentation for the participants to setup the required software for the tutorial and for publishing the final working examples, accessible [here](https://epigenomeanalysistutorial-2020.readthedocs.io/en/latest/index.html).

# Schedule

[ECCB2020](https://github.com/SchulzLab/EpigenomeAnalysisTutorial-2020/blob/master/Schedule_ECCB2020.md)

[GCB2020](https://github.com/SchulzLab/EpigenomeAnalysisTutorial-2020/blob/master/Schedule_GCB2020.md)
