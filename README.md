# How to Get Started

‼️‼️‼️ <br>
The original script, `analysis.ipynb`, performs eQTL analysis across all chromosomes (1–22), which can take **over 4 hours** to complete. To make it more convenient for reproducibility check, a shortened version, `analysis_fast.ipynb`, is also provided. 

This shortened script performs the same set of analyses but focuses on a single chromosome (chr15), taking approximately **32 minutes** to complete.


### Step 1: Clone the Repository
Clone the repository using the command below:

```sh
git clone https://github.com/ybbu/DSC180A-Genetic-risk-prediction.git
```

### Step 2: Install PLINK2
Before starting the analysis, make sure you have PLINK2 installed and executable.

- Download PLINK2 from [here](https://www.cog-genomics.org/plink/2.0/) (choose the version that fits your OS).
- Unzip the downloaded package.
- Move the pacakge into the cloned repository directory.

### Step 3: Set Up the Python Environment
All the Python packages are listed in the `environment.yml` file. Once you have PLINK2 installed, follow these steps to set up the environment:

1. Create the conda environment:

   ```sh
   conda env create -f environment.yml
   ```

2. Activate the environment:

   ```sh
   conda activate dsc180a
   ```

3. Install the IPython kernel for Jupyter Notebook:

   ```sh
   python -m ipykernel install --user --name dsc180a --display-name "dsc180a"
   ```

### Step 4: Start Your Analysis
Now you can open the Jupyter Notebook file `analysis.ipynb` to start your analysis!

Make sure to select the **dsc180a** kernel from the Python Environments to ensure all dependencies are correctly loaded.
