# Task 3: Visualization and Interpretation

## Project
**SWYNEX Bioinformatics Project**

## Dataset
**GSE10072 – Lung Adenocarcinoma vs Non-Tumor Lung Tissue**

The dataset contains gene expression data from lung adenocarcinoma and non-tumor lung tissue samples. It was obtained from the Gene Expression Omnibus (GEO) database.

## Objective

To visualize gene expression data using appropriate statistical plots and interpret the observed patterns, distributions, and variations across samples.

## Visualizations Performed

The following visualizations were performed using Python:

1. **Expression Value Distribution – Histogram**  
   Examines the overall distribution and frequency of gene expression values.

2. **Overall Expression Distribution – Boxplot**  
   Summarizes the distribution, median, spread, and potential outliers of expression values.

3. **Sample-wise Expression Distribution**  
   Compares the expression value distributions across individual samples to observe variation and consistency.

4. **Expression Density Distribution**  
   Examines the overall concentration and shape of expression values.

5. **Sample-wise Mean Expression**  
   Visualizes the average gene expression value for each sample and compares variation in sample-level averages.

6. **Tumor vs Non-Tumor Mean Expression Comparison**  
   Compares average expression values between tumor and non-tumor tissue groups.

## Key Observations

- Gene expression values were primarily concentrated within the central range of the distribution.
- The overall expression distribution showed a concentration of values around the central expression range.
- Sample-wise distributions showed broadly similar expression patterns across samples.
- Sample-wise mean expression values showed relatively small variation.
- Tumor and non-tumor tissue groups showed differences in average expression patterns that can be explored further.

## Limitations

These visualizations are exploratory and descriptive in nature.

They do not independently establish:

- Statistically significant differential gene expression.
- Biological causation.
- Specific molecular pathways associated with the observed patterns.
- Whether observed differences are caused by tumor status or other biological or technical factors.

Further statistical analysis, including differential expression analysis and multiple-testing correction, would be required to investigate these findings.

## Tools and Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib

## Notebook

The analysis and visualizations are available in:

`SWYNEX_Task3_Visualization_and_Interpretation.ipynb`

## Project Repository

[SWYNEX Bioinformatics Project – GitHub](https://github.com/naheedmomin/SWYNEX-Bioinformatics-Project)

---

**Task 3: Visualization and Interpretation – SWYNEX Bioinformatics Project**
