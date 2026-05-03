# SVsig
a tool for structural variation mutational signature

SVSig is an end-to-end pipeline for mutational signature analysis of structural variants (SVs) from whole-genome sequencing data. It integrates breakpoint sequence features, copy number variation (CNV) metrics, and a minimum-volume non-negative matrix factorization (mvNMF) model to extract stable and biologically interpretable SV signatures.

SVSig is specifically designed for cancer genomes (e.g., esophageal carcinoma) and outputs signature spectra, exposure matrices, and COSMIC matching results with publication-ready visualizations.

Requirements
Python 3.7 or higher

Linux / Ubuntu (tested on 20.04)

Run the full pipeline

SVSig runall -i /path/to/sv_vcf/ -b /path/to/bam/ -c /path/to/cnv/ -o results/
