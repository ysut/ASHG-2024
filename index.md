# Supplementary Information of Poster Presentation in ASHG 2024  
# Description
This page provides detailed points along with additional supplementary information.

## 1. Summary
Splicing variants significantly contribute to Mendelian disorders, yet prediction accuracy remains a challenge. We developed a framework to screen for pathogenic splicing SNVs, assigning a Priority Score (0–9) based on simplified 2023 ClinGen recommendations. Validation with data from the Human Gene Mutation Database and gnomAD demonstrated superior accuracy over SpliceAI alone. Applied to 1,330 unresolved exome cases, the framework identified pathogenic variants in _COL2A1_, _PDHA1_, _MECP2_, and _JAKMIP1_, and suggested candidates in _UBN1_, _NFE2L1_, and _ZNF516_. This workflow advances splicing variant detection in exome sequencing.

## 2. Additional Results information 
## The list of eLoF genes
A Microsft Excel format file is available.
[Here](https://github.com/ysut/ASHG-2024/blob/develop/_includes/eLoF_genes_list.txt).  

![venn](https://github.com/ysut/ASHG-2024/blob/develop/_includes/elof_venn.png?raw=true)
  
## Analysis note as Google colab
The code used for reanalyzing WES can be replicated in Google Colab.
The sample of 2000 randomly selected variants (2 sets) has also been uploaded.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ysut/2024_CellGenomics/blob/develop/main.ipynb)
  
## Supplementary Figures
Several figures are drawn using Plotly, allowing for interactive operations.

### Supplementary Figure 1. Priority Score Distribution in Validation variants set
{% include Figure3A.html %}

### Supplementary Figure 2. Performance Meterics Comparison 
{% include Figure3B.html %}

### Supplementary Figure 3. Results of revisited WES data
{% include FigureS3.html %}

### Supplementary Figure 4. Final interpretations of variants in known disease-associated gene
{% include FigureS4.html %}
