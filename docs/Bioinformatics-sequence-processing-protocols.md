Bioinformatics Sequence Processing Protocols
=====


Reference Database Generation & Curation
------------

- [MitoPilot](https://github.com/Smithsonian/MitoPilot)
<br>
An R package for scalable mitogenome assembly and annotation, uses Nexflow and includes (Shiny) web app for project management and curation of results. Currently supports fish and starfish datasets, but will be expanded to other taxa soon. Developed as a joint effort by the [NOAA National Systematics Lab](https://www.fisheries.noaa.gov/about/national-systematics-laboratory) and the [Smithsonian Ocean DNA Initiative](https://naturalhistory.si.edu/initiatives/oceans/ocean-science-center/ocean-dna)
<br><br>
- [rCRUX Reference Database Generating Tool](https://github.com/CalCOFI/rCRUX) <br>
This R package generates reference databases for eDNA metabarcoding from user-supplied primer sequences. The package employs iterative Basic Alignment Search Tool (BLAST) searches paired with quality control to produce a final reference library.
<br><br>
- [Mitohelper](https://github.com/aomlomics/mitohelper)
<br>
This Python-based tool is designed to assist with preparing eDNA reference databases for fishes. It can determine whether a reference sequence exists for a specific species/group and visualize the available sequenced regions of target genes.
<br><br>


Metabarcoding
----------------
- [Tourmaline metabarcoding pipeline](https://github.com/aomlomics/tourmaline) <br>
Detailed Snakemake workflow for standardized, repeatable processing and classifying of eDNA sequence data. Uses the popular [QIIME 2](https://qiime2.org/) software
<br><br>
- [REVAMP: Rapid Exploration and Visualization through an Automated Metabarcoding Pipeline](https://github.com/McAllister-NOAA/REVAMP) <br>
Bash workflow wrapper for many eDNA quality control and analysis tools. Produces a variety of figures including taxonomy bar charts, rarefaction curves, and ordination plots. 
<br><br>
- [Anacapa metabarcoding pipeline](https://github.com/limey-bean/Anacapa) <br>
eDNA toolkit to build reference databases, assign taxonomy, and explore biodiversity statistics. Works for a variety of markers, including 12S, 16S, 18S, ITS2, and CO1.

Population Genomics
--------------------
- [SEDNA Workflows](https://github.com/sedna-users/overview/blob/main/README.md) <br>
 List of scripts, pipelines, and tools for a variety of analyses including whole genome sequencing workflows, SNP discovery, microhaplotype genotyping, population assignment, historical demography. All written specifically for the NOAA NMFS SEDNA bioinformatics computing cluster.
<br><br>
- [strataG: An R package for manipulating, summarizing and analysing population genetic data](https://github.com/EricArcher/strataG) 
<br>
R package for exploring multi-locus genetic datasets, calculating population genetic summary statistics, and demographic and population structure analyses. 

Data Visualization
----------------
- [MBON eDNA data Visualization Tool](https://github.com/marinebon/edna-vis)<br>
R Shiny app to interactively map and visualize eDNA Operational Taxonomic Units (OTUs).
<br><br>
- [Great Lakes Atlas for Multi-omics Research (GLAMR)](https://greatlakesomics.org/)<br>
Tool to map environmental 'Omics datasets from the Laurentian Great Lakes, including metagenomic and amplicon sequence data.

