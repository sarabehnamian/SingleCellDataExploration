# Single Cell RNA-seq Analysis
 
## Description

This repository contains a Jupyter Notebook that performs an exploratory analysis of a single-cell RNA sequencing dataset. The analysis includes preprocessing, visualization, clustering, and differential expression analysis, primarily using the `scanpy` Python library.
 
## Dataset

The analysis is performed on a dataset containing gene expression data for 117,573 cells from the study titled "Cryopreservation of human cancers conserves tumour heterogeneity for single-cell multi-omics analysis".

**Important Note:** The dataset required for the analysis is not included in the repository due to its large size. Please download it directly from the [Single Cell Portal](https://singlecell.broadinstitute.org/single_cell/study/SCP1415/cryopreservation-of-human-cancers-conserves-tumour-heterogeneity-for-single-cell-multi-omics-analysis#study-download).

## Content

- `single_cell_analysis.ipynb`: Jupyter Notebook that contains all the code for the analysis.

## Libraries Used

- `scanpy`: Used for preprocessing, analysis, and visualization of single-cell RNA-seq data.
- `pandas`: Used for data manipulation and analysis.

## Usage

1. Clone the repository: `git clone https://github.com/sarabehnamian/SingleCellDataExploration.git`
2. Navigate into the project directory: `cd SingleCellDataExploration`
3. Download the dataset from the [Single Cell Portal](https://singlecell.broadinstitute.org/single_cell/study/SCP1415/cryopreservation-of-human-cancers-conserves-tumour-heterogeneity-for-single-cell-multi-omics-analysis#study-download) and place it in a `data` directory within the project folder.
4. Launch Jupyter Notebook: `jupyter notebook`
5. Open `single_cell_analysis.ipynb` and run the cells to perform the analysis.

## Author

[Sara Behnamian](https://github.com/sarabehnamian)
