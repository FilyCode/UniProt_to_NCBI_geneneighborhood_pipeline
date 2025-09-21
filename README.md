# UniProt to NCBI Gene Neighborhood Pipeline

## Overview
This pipeline facilitates phylogenetic enzyme homology searches by identifying genes within the genomic neighborhood of target proteins. It accepts UniProt IDs as input and generates a `.csv` file providing a comprehensive overview of genes of interest. The pipeline leverages the UniProt and NCBI APIs for data retrieval and integration.

## Scripts

*   **`Gene-search-pipeline.ipynb`**: This Jupyter Notebook serves as the main interactive interface. It allows users to input UniProt IDs, execute API queries, and generate the gene overview file.
*   **`Gene-neighborhood-pipeline_with-matrix-calc...`**: This accompanying script provides additonal matrix calculations for downstream analysis and visualization.

## Output
The pipeline produces a `.csv` file containing a detailed overview of the identified genes within their respective genomic neighborhoods.
