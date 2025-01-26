# The Dark Side of the Genome: R Notebooks for Transposable Element Analysis

This repository contains the R Markdown (Rmd) notebooks developed during my master thesis: **"The dark side of the genome: Development of a computational pipeline to identify transposable elements with a functional role in genome regulation."** The work focuses on identifying and analyzing transposable elements (TEs) with potential regulatory roles in naive and primed human embryonic stem cells (hESCs).

## Contents

The R Markdown notebooks are located in the [`notebooks/`](notebooks/) folder:

1. **`H9hESCs_DEA.Rmd`**  
   Differential expression analysis for genes and TE subfamilies.

2. **`H9hESCs_DEA_individualTEs.Rmd`**  
   Differential expression analysis for genes and individual TE loci.

3. **`H9hESCs_individualTEs_subfamilyAnalysis.Rmd`**  
   Analysis of TE subfamilies associated with primed or naive states. Includes approaches such as:
   - Subfamily differential expression analysis.
   - Subfamilies with high percentages of up/downregulated elements.
   - GSEA-like enrichment analysis of TE families.

4. **`H9hESCs_DEA_settingThreshold.Rmd`**  
   Using permutation tests to determine statistical thresholds for differential expression.

5. **`regioneR.Rmd`**  
   Analysis using regioneR and permutation tests to detect associations between TEs and differentially expressed genes in naive and primed hESCs.

6. **`MeasuringDistances.Rmd`**  
   Measuring distances between selected TE subfamilies and the start sites of up/downregulated genes in naive and primed hESCs. Includes statistical and effect size comparisons with random gene sets.

---

## Notes
- This work was conducted in the laboratory of **[Nuno Morais](https://imm.medicina.ulisboa.pt/group/distrans/)** at the Instituto de Medicina Molecular João Lobo Antunes, University of Lisbon.  
- Some of the code in this repository is not fully polished or optimized, as it was developed in the context of a master thesis. Feel free to adapt or improve it for your own research.

---

Feel free to explore and adapt these notebooks for your research. If you have any feedback or questions, feel free to reach out!
