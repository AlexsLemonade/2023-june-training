---
title: Resources for single-cell RNA-seq analysis
nav_title: Single-cell resources
---

This list provides some links to resources on single-cell RNA-seq analysis methods that may be useful to you as you develop your own single-cell RNA-seq analysis skills and practices.
Please note, this is not an exhaustive list.
It includes multiple types of resources for various topics in single-cell RNA-seq analysis, but does not represent the complete breadth of analysis topics.
Resources are listed by topic and in alphabetical order, not in order of recommendation.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [General Single-cell resources](#general-single-cell-resources)
- [Alignment and quantification of gene expression](#alignment-and-quantification-of-gene-expression)
- [Filtering and normalization](#filtering-and-normalization)
- [Dimensionality reduction and clustering](#dimensionality-reduction-and-clustering)
- [Cell type annotation](#cell-type-annotation)
- [CITE-seq](#cite-seq)
- [Integrating scRNA-seq samples](#integrating-scrna-seq-samples)
- [Differential expression analysis](#differential-expression-analysis)
- [Differential abundance](#differential-abundance)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## General Single-cell resources

- [An introduction to the SingleCellExperiment class - Bioconductor](https://www.bioconductor.org/packages/devel/bioc/vignettes/SingleCellExperiment/inst/doc/intro.html)
- [Analysis of single cell RNA-seq data - Hemburg Lab](https://www.singlecellcourse.org/)
- [Current best practices in single-cell RNA-seq analysis: a tutorial - Luecken and Theis (2019)](https://doi.org/10.15252/msb.20188746)
- [Orchestraing Single-cell Analysis with Bioconductor - Bioconductor](https://bioconductor.org/books/3.16/OSCA/)

## Alignment and quantification of gene expression

- [A like-for-like comparison of lightweight-mapping pipelines for single-cell RNA-seq data pre-processing - Zakeri _et al._ (2021)](https://doi.org/10.1101/2021.02.10.430656)
- [Alevin-fry unlocks rapid, accurate and memory-frugal quantification of single-cell RNA-seq data - He _et al._ (2022)](https://doi.org/10.1038/s41592-022-01408-3)
- [Cell Ranger Overview - 10X Genomics](https://support.10xgenomics.com/single-cell-gene-expression/software/pipelines/latest/what-is-cell-ranger)
- [Comparative analysis of common alignment tools for single-cell RNA sequencing - Bruning _et al._ (2022)](https://doi.org/10.1093/gigascience/giac001)

## Filtering and normalization

- [EmptyDrops: distinguishing cells from empty droplets in droplet-based single-cell RNA sequencing data - Lun _et al._ (2019)](https://doi.org/10.1186/s13059-019-1662-y)
- [miQC: An adaptive probabilistic framework for quality control of single-cell RNA-sequencing data - Hippen _et al._ (2021)](https://doi.org/10.1371/journal.pcbi.1009290)
- [OSCA Basics](http://bioconductor.org/books/3.16/OSCA.basic/)
- [Utilities for handling droplet-based single-cell RNA-seq data: Detecting empty droplets](https://bioconductor.org/packages/devel/bioc/vignettes/DropletUtils/inst/doc/DropletUtils.html#detecting-empty-droplets)

## Dimensionality reduction and clustering

- [OSCA chapter on clustering](http://bioconductor.org/books/3.16/OSCA.basic/clustering.html)
- [OSCA chapter on clustering metrics](http://bioconductor.org/books/3.16/OSCA.advanced/clustering-redux.html)
- [OSCA chapter on dimensionality reduction](http://bioconductor.org/books/3.16/OSCA.basic/dimensionality-reduction.html)
- [PCA - Principal Component Analysis](http://www.nlpca.org/pca_principal_component_analysis.html)
- [Principal Component Analysis - A Brief Introduction](https://medium.com/x8-the-ai-community/principal-component-analysis-a-brief-introduction-dc8cf3e03c71)

## Cell type annotation

- [AUCell: Identifying cells with active gene sets](https://bioconductor.org/packages/devel/bioc/vignettes/AUCell/inst/doc/AUCell.html)
- [Azimuth](https://azimuth.hubmapconsortium.org/)
- [Identifying cell types to interpret scRNA-seq data: how, why and more possibilities - Wang _et al._ (2020)](https://doi.org/10.1093/bfgp/elaa003)
- [OSCA chapter on cell type annotation](https://bioconductor.org/books/3.16/OSCA.basic/cell-type-annotation.html)
- [scType](http://sctype.app)
- [The SingleR Book - Bioconductor](https://bioconductor.org/books/3.16/SingleRBook/)
- [Web resources for cell type annotation - 10X Genomics](https://www.10xgenomics.com/resources/analysis-guides/web-resources-for-cell-type-annotation)

## CITE-seq

- [OSCA chapter on integrating with protein abundance](http://bioconductor.org/books/3.16/OSCA.advanced/integrating-with-protein-abundance.html)
- [Simultaneous epitope and transcriptome measurement in single cells - Stoeckius _et al._ (2017)](https://doi.org/10.1038/nmeth.4380)

## Integrating scRNA-seq samples

- [A description of the theory behind the `fastMNN` algorithm](https://marionilab.github.io/FurtherMNN2018/theory/description.html)
- [Batch effects in single-cell RNA-sequencing data are corrected by matching mutual nearest neighbors - Haghverdi _et al._ (2018)](https://doi.org/10.1038/nbt.4091)
- [Benchmarking atlas-level data integration in single-cell genomics - Luecken _et al._ (2021)](https://doi.org/10.1038/s41592-021-01336-8)
- [Fast, sensitive and accurate integration of single-cell data with Harmony - Korsunsky _et al._ (2019)](https://doi.org/10.1038/s41592-019-0619-0)
- [OSCA multi-sample](http://bioconductor.org/books/3.16/OSCA.multisample/)

## Differential expression analysis

- [Batch effects and the effective design of single-cell gene expression studies - Tung _et al._ (2017)](https://doi.org/10.1038/srep39921)
- [Differential gene expression analyses in scRNA-seq data between conditions with biological replicates - 10X Genomics](https://www.10xgenomics.com/resources/analysis-guides/differential-gene-expression-analysis-in-scrna-seq-data-between-conditions-with-biological-replicates)
- [Harvard-Chan Bioinformatics Core tutorial on differential expression analysis with DESeq2](https://hbctraining.github.io/scRNA-seq/lessons/pseudobulk_DESeq2_scrnaseq.html)
- [OSCA chapter on DE analyses between conditions](http://bioconductor.org/books/3.16/OSCA.multisample/multi-sample-comparisons.html)

## Differential abundance

- [Cell type composition analysis: comparison of statistical methods - Simmons (2022)](https://doi.org/10.1101/2022.02.04.479123)
- [OSCA chapter on changes in cluster abundance](http://bioconductor.org/books/3.16/OSCA.multisample/differential-abundance.html)
- [scCODA is a Bayesian model for compositional single-cell data analysis - Buttner _et al._ (2021)](https://doi.org/10.1038/s41467-021-27150-6)
- [scDC: single cell differential composition analysis - Cao _et al._ (2019)](https://doi.org/10.1186/s12859-019-3211-9)
