# ML-Bacteria-Classification
Machine Learning Models for Bacteria Classification using 16S rRNA Short-Reads

![alt text](https://www.healthtech.dtu.dk/-/media/institutter/sundhedsteknologi/health-tech-newdesign/research/research-sections/bioinformatics/bioinformatics_graphic.jpg?rw=960&rh=0&hash=D4A1917E9829DB9BE4064403BD341192)

***

### About the Project

Taxonomy is one of the most relevant scientific disciplines in biology. Initially, the characterization and classification of species relied exclusively on phenotypic traits. Today, bacterial systematics and taxonomy have evolved to incorporate molecular information. The advent of modern sequencing methods has optimized and scaled the analysis of complete genomes, with shotgun sequencing and amplicon sequencing standing out.

This project addresses taxonomic work using short sequences obtained through amplicon sequencing of the small subunit ribosomal RNA (16S rRNA). The metagenomic data analysis involves feature extraction through the representation of subsequence frequencies, known as k-mers. Additionally, high-dimensional data visualization techniques are applied, alongside Machine Learning (ML) models, to explore underlying patterns in the data, identify differences in nucleotide composition between sequences, and effectively classify species at various hierarchical levels.

### Data Description

The metagenomic data used in this study come from the work published by Fiannaca *et al.* (2018). These are simulated data from an amplicon sequencing process, based on the 16S ribosomal RNA (rRNA) gene corresponding to the small ribosomal subunit. For the simulation, only the hypervariable V3-V4 regions (approximately 469 bp) were selected, as these less conserved regions have been widely reported as discriminative for species identification and classification.

The dataset includes 28,000 short sequences, which were processed to remove the primers. The data is available at the following [URL](http://tblab.pa.icar.cnr.it/public/BMC-CIBB_suppl/datasets/
)

### Key Insights

This project highlights the power of Machine Learning models in analyzing metagenomic data, demonstrating that k-mer frequency vectorization effectively captures patterns for accurate bacterial classification. By integrating Bioinformatics and Machine Learning, it underscores the critical role of interdisciplinary approaches in extracting deeper biological insights from complex datasets. These methods enable scalable and precise analyses in microbial taxonomy, ecosystem studies, and medical research. By profiling bacterial communities and their dynamics, they enhance our understanding of ecological interactions, support environmental monitoring, and drive advances in medical diagnostics and treatment development. This emphasizes the potential of computational tools in addressing complex biological and biomedical challenges.

_December 2024_

***

_Note: This notebook is intended to showcase my work and computational thinking in order to build my portfolio and record my progress as increase my knowledge and improve my programming skills. This code is not intended for redistribution, and the original author of this notebook is not responsible for any academic penalties or other damages incurred from plagiarized code._
