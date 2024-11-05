
## Data Files

In the `data` folder, you will find the following files:

1. **`gene_annot.txt.gz`**: A completed list of genes located on autosomes, including specific information for each gene.
2. **`GD462.GeneQuantRPKM.50FN.samplename.resk10.txt.gz`**: A gene expression file containing data from samples in the [1000 Genomes Project](https://www.internationalgenome.org/).

You will need to unzip both of these files before conducting the analysis.

## Required Resources

Before starting the analysis, ensure you have the following resources:

1. **1000 Genomes Consortium Data**:
   - Download the publicly available data from [here](https://data.broadinstitute.org/alkesgroup/FUSION/LDREF.tar.bz2).
   - Keep the folder named `LDREF` in the repository directory.

2. **Software Requirements**:
   - **PLINK2**: Download from [here](https://www.cog-genomics.org/plink/2.0/) and place it in the repository directory.
   - **Python Packages**: Ensure you have the following Python packages installed:
     - `os`
     - `math`
     - `random`
     - `subprocess`
     - `numpy`
     - `pandas`
     - `pandas_plink`
     - `statsmodels`
     - `matplotlib`

## Getting Started

To begin your analysis, follow these steps:

1. Unzip the `gene_annot.txt.gz` and `GD462.GeneQuantRPKM.50FN.samplename.resk10.txt.gz` files.
2. Download and extract the 1000 Genomes consortium data into a folder named `LDREF`.
3. Ensure PLINK2 is downloaded and accessible in your project directory.
4. Install the required Python packages.

Once everything is set up, open the `analysis.ipynb` notebook to start your analysis.
