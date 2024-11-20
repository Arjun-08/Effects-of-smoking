# Effects of Smoking on Gene Expression

## Overview
This project explores the effects of smoking on gene expression, focusing on identifying genes that respond differently in men and women. The study utilizes a **2-way ANOVA framework** to analyze the interaction between **Smoking Status** and **Gender**. The results are visualized through a histogram of p-values.

---

## Problem Statement
The objective of this analysis is to:
- Determine genes exhibiting significant interaction effects between **Smoking Status** and **Gender**.
- Visualize the distribution of p-values to highlight genes with potential differential responses.

---

## Dataset Description
The dataset comprises:
- **~40,000 rows** of normalized gene expression data.
- **Metadata fields**:
  - `GeneSymbol`: The unique identifier for genes.
  - `EntrezGeneID`: Gene-specific identifiers for cross-referencing.
  - `GO`: Gene Ontology terms describing biological processes.
- **Samples**: Representing combinations of gender (`Male`/`Female`) and smoking status (`Smoker`/`Non-smoker`).

---

## Analysis Approach

### Data Overview
The dataset was processed to classify samples based on gender and smoking status. Each row represents a single probe (gene), and the study focuses on identifying interaction effects between smoking and gender.

### Statistical Analysis
Using a 2-way ANOVA framework, the analysis examined gene expression levels across four groups:
1. Male Smokers
2. Female Smokers
3. Male Non-smokers
4. Female Non-smokers

The p-values derived from the interaction term indicate whether a gene's response to smoking differs significantly by gender.

### Visualization
A histogram was plotted to depict the distribution of p-values. Genes with \( p < 0.05 \) suggest potential interaction effects worthy of further investigation.


## Results

### Key Findings
- The majority of genes show no significant interaction effects between smoking and gender.
- A subset of genes exhibits significant \( p \)-values (\( p < 0.05 \)), suggesting differential responses to smoking in men vs. women.

### Visualization
![plot1](https://github.com/user-attachments/assets/3ece0983-7eee-4c0c-8118-4724fa399be1)

The histogram highlights the distribution of p-values, with a focus on genes with significant interaction effects.

## Conclusion
This analysis serves as a preliminary step in identifying genes that may respond differently to smoking based on gender. Further research, including multiple testing correction and biological validation, is required to confirm these findings.

## Contact
If you have any questions or suggestions, please feel free to reach out to me at nvarjunmani07@gmail.com.
