---
layout: page
title: Software
group: navigation
permalink: "software.html"
---
{% include JB/setup %}

### Bioconductor R packages

We implement our methods as the R packages deployed on [Bioconductor](http://www.bioconductor.org).

- [**scHiCcompare**](https://github.com/dozmorovlab/scHiCcompare) - differential interaction detection in single-cell Hi-C data. Includes imputation, normalization, and differential interaction detection between two groups of scHiC matrices. 
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ [GitHub](https://github.com/dozmorovlab/scHiCcompare), [Preprint](https://doi.org/10.1101/2024.11.06.622369) ]

- [**preciseTAD**](https://bioconductor.org/packages/preciseTAD) - Prediction of boundaries of topologically associating domains (TADs) and chromatin loops from epigenomic data at base-level precision. [preciseTADhub](https://bioconductor.org/packages/preciseTADhub/) - Pre-trained random forest models obtained using preciseTAD. [preciseTAD predicted boundaries for 60 cell lines](https://drive.google.com/drive/folders/15Rc6PhrrBjThwE-5dSyNX-ILELaUu6uG?usp=sharing) - BED files, hg38
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ [Bioconductor](https://bioconductor.org/packages/preciseTAD/), [GitHub](https://github.com/dozmorovlab/preciseTAD), [Paper](https://doi.org/10.1093/bioinformatics/btab743) ]

- [**excluderanges**](https://bioconductor.org/packages/excluderanges) - Genomic ranges of deny (aka problematic, exclusion, blacklisted) regions that should be avoided when working with genomic data. For human, mouse, and selected other organisms.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ [Bioconductor](https://bioconductor.org/packages/excluderanges/), [GitHub](https://github.com/mdozmorov/excluderanges), [Preprint](https://doi.org/10.1101/2022.11.21.517407) ]

- [**CTCF**](https://bioconductor.org/packages/CTCF) - Genomic coordinates of FIMO-predicted CTCF binding sites with motif MA0139.1 (Jaspar).
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ [Bioconductor](https://bioconductor.org/packages/CTCF/), [GitHub](https://github.com/mdozmorov/CTCF), [Paper](https://doi.org/10.1093/bioadv/vbac097) ]

- [**TADcompare**](https://bioconductor.org/packages/TADCompare/) - Differential and time course analysis of Topologically Associated Domains
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ [Bioconductor](https://bioconductor.org/packages/TADCompare/), [GitHub](https://github.com/dozmorovlab/TADCompare), [Paper](https://doi.org/10.3389/fgene.2020.00158) ]

- [**SpectralTAD**](https://bioconductor.org/packages/SpectralTAD/) - Calling Topologically Associated Domains (TADs) using spectral clustering
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ [Bioconductor](https://bioconductor.org/packages/SpectralTAD/),  [GitHub](https://github.com/dozmorovlab/SpectralTAD), [Preprint](https://www.biorxiv.org/content/10.1101/549170v3), [Paper](https://doi.org/10.1186/s12859-020-03652-w) ]

- [**multiHiCcompare**](https://bioconductor.org/packages/multiHiCcompare/) - Joint normalization of multiple Hi-C datasets and comparative analysis of complex Hi-C experiments
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ [Bioconductor](https://bioconductor.org/packages/multiHiCcompare/), [GitHub](https://github.com/dozmorovlab/multHiCcompare), [Paper](https://doi.org/10.1093/bioinformatics/btz048) ]

- [**HiCcompare**](https://bioconductor.org/packages/HiCcompare/) - Joint normalization and differential analysis of pairs of chromatin interaction matrices obtained from Hi-C sequencing
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ [Bioconductor](https://bioconductor.org/packages/HiCcompare/), [GitHub](https://github.com/dozmorovlab/HiCcompare), [Preprint](https://www.biorxiv.org/content/10.1101/147850v2), [Paper](https://doi.org/10.1186/s12859-018-2288-x) ]

- [**HMP2data**](https://bioconductor.org/packages/HMP2Data/) - An R package for data access from the integrative Human Microbiome data portal
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ [Bioconductor](https://bioconductor.org/packages/HMP2Data/), [GitHub](https://github.com/dozmorovlab/HMP2Data) ]

# Non Bioconductor

- **GenomeRunner** - A web server and a standalone tool for enrichment analysis of genomic regions in epigenomic annotations
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ [GitHub](https://github.com/mdozmorov/genomerunner_web), [SourceForge](https://sourceforge.net/p/genomerunner), [Paper1](https://doi.org/10.1093/bioinformatics/btw169), [Paper2](https://doi.org/10.1093/bioinformatics/btr666) ]

- [lrcde](https://github.com/mdozmorov/lrcde.dev) - An R package for cell type-specific deconvolution and differential gene expression analysis
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ [GitHub](https://github.com/mdozmorov/lrcde.dev), [Paper](https://doi.org/10.1186/s12859-016-1226-z) ]

# Contributor

- [**nullranges**](https://bioconductor.org/packages/nullranges) - Generation of null ranges via bootstrapping or covariate matching.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ [website](https://nullranges.github.io/nullranges/) ]

# GitHub stats

<img src="https://raw.githubusercontent.com/mdozmorov/GitHub_metrics/master/github-metrics.svg" height=200 >
