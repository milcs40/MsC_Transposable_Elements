# The Dark Side of the Genome: R Notebooks for Transposable Element Analysis

This repository contains the R Markdown (Rmd) notebooks developed during my master thesis: **"The dark side of the genome: Development of a computational pipeline to identify transposable elements with a functional role in genome regulation."** The work focuses on identifying and analyzing transposable elements (TEs) with potential regulatory roles in naive and primed human embryonic stem cells (hESCs).

## Contents

1. **`H9hESCs_DEA.Rmd`**  
   Differential expression analysis for genes and TE subfamilies.

2. **`H9hESCs_DEA_individualTEs.Rmd`**  
   Differential expression analysis for genes and individual TE loci.

3. **`H9hESCs_individualTEs_subfamilyAnalysis.Rmd`**  
   Analysis of TE subfamilies associated with primed or naive states. Includes approaches such as:
   - Subfamily differential expression analysis.
   - Subfamilies with high percentages of up/downregulated elements.
   - GSEA-like enrichment analysis of TE subfamilies.

4. **`H9hESCs_DEA_settingThreshold.Rmd`**  
   Using permutation tests to determine statistical thresholds for differential expression.

5. **`regioneR.Rmd`**  
   Analysis using regioneR and permutation tests to detect associations between TE subfamilies and differentially expressed genes in naive and primed hESCs.

6. **`MeasuringDistances.Rmd`**  
   Measuring distances between selected TE subfamilies and the start sites of up/downregulated genes in naive and primed hESCs. Includes statistical and effect size comparisons with random gene sets.

---

Feel free to explore and adapt these notebooks for your own research! If you find them helpful, consider citing this repository or reaching out with feedback.

