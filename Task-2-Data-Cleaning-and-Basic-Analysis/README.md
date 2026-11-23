# Task 2 – Data Cleaning and Basic Analysis

## Project Overview
This task focuses on data inspection, quality assessment, descriptive statistical analysis, and preliminary biological comparison using Python.

The dataset used is GSE10072, obtained from the NCBI Gene Expression Omnibus (GEO) database. It contains microarray expression data associated with lung adenocarcinoma and non-tumor lung tissue samples.

## Dataset Information
- **GEO Accession:** GSE10072
- **Study:** Gene Expression Signature of Cigarette Smoking and Its Role in Lung Adenocarcinoma Development and Survival
- **Data Type:** Microarray Gene Expression Data
- **Total Probes:** 22,283
- **Total Samples:** 107
- **Tumor Samples:** 58
- **Non-Tumor Samples:** 49

## Tools and Libraries
- Python
- Jupyter Notebook
- Anaconda
- Pandas
- NumPy
- Matplotlib
- gzip
- csv

## Methodology

### 1. Dataset Loading
Loaded the GEO Series Matrix file using Python and Pandas.

### 2. Dataset Inspection
Examined dataset dimensions, sample IDs, probe IDs, data types, expression values, and missing values.

### 3. Data Quality Assessment
Performed checks for:
- Missing values
- Duplicate probe IDs
- Duplicate sample IDs
- Infinite values
- Numerical data consistency

### 4. Descriptive Statistical Analysis
Calculated overall and sample-wise descriptive statistics, including mean, median, standard deviation, minimum, and maximum.

### 5. Preliminary Tumor vs Non-Tumor Comparison
Classified samples into tumor and non-tumor groups, separated their expression matrices, and calculated group-wise mean expression values for individual probes.

## Key Results
- Dataset dimensions: 22,283 × 107
- Missing values: 0
- Duplicate probe IDs: 0
- Duplicate sample IDs: 0
- Infinite values: 0
- Tumor samples: 58
- Non-tumor samples: 49
- Overall mean expression value: 7.527759

## Conclusion
The dataset passed the basic structural and numerical quality checks performed in this task. Descriptive statistical analysis and preliminary group-wise comparisons provided an overview of the microarray expression data.

Further statistical testing and multiple-testing correction would be required to identify statistically significant expression differences.

## Dataset Source
NCBI Gene Expression Omnibus: [GSE10072](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE10072)

## Project Notebook
The Jupyter Notebook containing the Python code, calculations, and analysis results is included in this folder.

## How to Run the Notebook

Download the GSE10072 series matrix file from the NCBI GEO database.

Place the downloaded file, GSE10072_series_matrix.txt.gz, inside the data folder at the repository root.

Open SWYNEX_Task2_Submission.ipynb using Jupyter Notebook.

Run the notebook cells sequentially.

Note: The notebook uses a relative file path to access the dataset.
