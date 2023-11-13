# ![](vignettes/images/banner.png)

## Overview

Understanding the interplay between different types of cells and their immediate environment is critical for understanding the mechanisms of cells themselves and their function in the context of human diseases. Recent advances in high dimensional in situ cytometry technologies have fundamentally revolutionized our ability to observe these complex cellular relationships providing an unprecedented characterisation of cellular heterogeneity in a tissue environment.

## Description

In this tutorial we will introduce an analytical framework for analysing data from high dimensional spatial omics technologies such as, CODEX, CycIF, IMC and High Definition Spatial Transcriptomics. This framework makes use of functionality from our Bioconductor packages simpleSeg, scHot, FuseSOM, spicyR, listClust, statial, scFeatures and ClassifyR. By the end of this tutorial attendees will be able to implement and assess some of the key steps of a spatial analysis pipeline including cell segmentation, feature normalisation, cell type identification, microenvironment and cell-state characterisation, spatial hypothesis testing and patient classification. Understanding these key steps will provide attendees with the core skills needed to interrogate the comprehensive spatial information generated by these exciting new technologies.

### Pre-requisites

It is expected that students will have:

-   basic knowledge of R syntax,
-   familiarity with SingleCellExperiment and/or SpatialExperiment objects, and
-   this workshop will not provide an in-depth description of cell-resolution spatial omics technologies.

### Time outline

The expected timing of the workshop:

| Activity                               | Time   |
|----------------------------------------|--------|
| Data visualisation & cell segmentation | 1h 30m |
| Cell type clustering & classification  | 1h 30m |
| Spatial analysis & feature generation  | 2h     |
| Patient Classification                 | 1h 30m |

### Learning objectives

-   Understand and visualise spatial omics datasets.
-   Identify key biological questions that can be addressed with these technologies and spatial analysis.
-   Understand the key analytical steps involved in spatial omics analysis, and perform these steps using R.
-   Evaluate the performance of data normalisation and cell segmentation.\
-   Understand and generate individual feature representations from spatial omics data.
-   Develop appreciation on how to assess performance of classification models.
-   Perform disease outcome prediction using the feature representation and robust classification framework.
