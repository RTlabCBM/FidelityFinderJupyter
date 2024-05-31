

Jupyter Notebooks with scripts used in the pipeline [FidelityFinder](https://github.com/RTlabCBM/FidelityFinder). All scripts are adapted to be run on Google Colab using the following links:

- [lengths_distribution_plotting](https://colab.research.google.com/github/RTlabCBM/FidelityFinderJupyter/blob/main/JupyterNotebooks/lengths_distribution_plotting.ipynb): creates plots with the lengths of the merged sequences obtained.
- [consensus_construction](https://colab.research.google.com/github/RTlabCBM/FidelityFinderJupyter/blob/main/JupyterNotebooks/consensus_construction.ipynb): finds barcodes and builds consensus sequences
- [vcf_analyzer](https://colab.research.google.com/github/RTlabCBM/FidelityFinderJupyter/blob/main/JupyterNotebooks/vcf_analyzer.ipynb): finds variants in VCF files. Creates an excel file with different data (table with variants, total number of variants, mutation rate...) and graphs showing the distribution of variants in the reference sequence, the distribution of indels and a heatmap with the types of SNPs (if any).
- [offsprings_finder](https://colab.research.google.com/github/RTlabCBM/FidelityFinderJupyter/blob/main/JupyterNotebooks/offsprings_finder.ipynb): finds possible offspring barcodes (barcodes generated due to errors in PCR reactions/sequencing reaction).

Additionally, there are three extra Google Colab notebooks to further process the results of the pipeline and to simulate the pipeline:
- [barcode_analyzer](https://colab.research.google.com/github/RTlabCBM/FidelityFinderJupyter/blob/main/JupyterNotebooks/barcode_analyzer.ipynb): creates a plot with a profile of the nucleotides present in barcodes
- [hotspots_finder](https://colab.research.google.com/github/RTlabCBM/FidelityFinderJupyter/blob/main/JupyterNotebooks/hotspots_finder.ipynb): it can process mutations tables of several samples to analyze and plot total variants, indels and SNPs in common
