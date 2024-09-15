# Graph Theoretical Properties of the Brain’s Structural Network

This repository contains a project focused on analyzing the graph-theoretical properties of the human brain's structural networks. Using graph theory, this project explores the organization and changes in the brain's structural connectivity across different age groups, providing insights into cognitive functions and potential implications for neurological conditions.

**Note:** 
1) Some outputs in the Jupyter notebook may not display correctly due to rendering limitations. For the best viewing experience, consider running the notebook locally using Jupyter Notebook or Jupyter Lab.
2) Some outputs in the PDF may not display correctly due to rendering limitations on GitHub. For the best viewing experience, please access the PDF through this [link to Google Drive](https://drive.google.com/file/d/1v1A628gjY4lg0XAI0gEc_RLblxOwjbOJ/view?usp=sharing).

## Introduction

Understanding the structural connectivity of the brain is crucial for gaining insights into its organization, development, and potential deterioration due to aging or disease. This project uses graph theory to model brain networks, where nodes represent brain regions, and edges denote connections between them. By applying various graph metrics, such as degree distribution, clustering coefficients, and centrality measures, this study investigates the efficiency and resilience of brain networks.

## Data

The dataset includes structural connectivity matrices for 88 individuals, aged 18 to 48, derived from diffusion-weighted imaging (DWI). Each matrix represents the connectivity between 90 cortical regions, as defined by the Automatic Anatomical Labeling (AAL) atlas. The data processing pipeline includes artifact correction, registration to standard brain space, and probabilistic tractography to construct the connectivity matrices.

## Methodology

The analysis involves several steps:

1. **Single Network Analysis**: Analyzing the structural connectivity of a single individual to establish a baseline understanding of a brain network's structure.
   
2. **Age Group Analysis**: Comparing the brain networks of three individuals from different age groups (18-25, 25-35, 35-45) to identify potential age-related changes in connectivity patterns.

3. **Graph-Theoretical Metrics**: Computing and analyzing centrality measures (degree, closeness, betweenness) and examining network properties like small-worldness and scale-freeness to understand the brain's efficiency and robustness.

## Results

The study reveals that brain networks exhibit distinct topological features, including small-world and scale-free properties, which are essential for efficient information processing and resilience against failures. Age-related changes are evident in the network structure, with older age groups showing more specialized and robust connectivity patterns.



