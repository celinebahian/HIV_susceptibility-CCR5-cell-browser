# UCSC Cell Browser Activity

**Name:** Bahian, Celine R. Previously 

**Assigned Gene:** CCR5 

**Associated Disease:** HIV-susceptibility 

**Date:** September 23, 2026

# PART B. Organ/Tissue Choice and Dataset Information

| Item | Information |
|---|---|
| **Dataset** | COVID-19 PBMC |
| **Organ/Tissue** | Peripheral blood mononuclear cells (PBMCs) |
| **Cell Types** | T cells, B cells, monocytes, dendritic cells, and other immune cells |
| **Gene** | CCR5 |
| **Reason for Selection** | PBMCs contain immune cells where CCR5 is relevant. CCR5 is a chemokine receptor involved in immune-cell signaling and is also associated with HIV infection. |
| **Dataset URL** | https://cells.ucsc.edu/?ds=covid19-pbmc |

<img width="1106" height="601" alt="image" src="https://github.com/user-attachments/assets/35708e4a-de73-4d22-ae30-95a303082af5" />

**Figure 1.** UCSC Cell Browser COVID-19 PBMC dataset showing major immune-cell populations in peripheral blood.

# PART C. Understanding the Cell Map

| Item | Observation |
|---|---|
| **Visualization** | UMAP |
| **What does one dot represent?** | One individual cell measured in the single-cell dataset. |
| **What do the clusters represent?** | Groups of cells with similar gene-expression profiles, representing different immune cell types. |
| **Cell-type/cluster labels** | CD4_T, CD8_T, B_cell, CD14_mono, CD16_mono, Treg, MAIT, NK_CD56hi, NK_CD56lo |

# Part D. Cell Types and Clusters

| Part | Answer |
|---|---|
| **a. Assigned gene symbol** | CCR5 |
| **b. Dataset used** | COVID-19 PBMC |
| **c. Is expression widespread, restricted, or low/undetected** | Low/undetected overall and relatively restricted |
| **d. Which cluster(s) appear to contain cells with stronger expression?** | Lymph_prolif, CD8_T, CD4_T Treg, CD14_mono, CD16_mono |
| **e. Which cluster(s) appear to contain little or no detectable expression?** | B_cell, Plasmablast, RBC, Platelets, HSPC, pDC |

<img width="918" height="588" alt="image" src="https://github.com/user-attachments/assets/f44a41b9-f48c-4731-8627-349ac16bf3c0" />

**Figure 2.** Cell-type annotation map of the COVID-19 PBMC dataset showing the major annotated cell clusters, including CD8_T, CD4_T Treg, CD14_mono, CD16_mono, B_cell, Plasmablast, and other cell populations.

# PART E.  Expression Plot

| Requirement | Observation |
|---|---|
| **Assigned gene** | CCR5 |
| **Cell types/clusters where CCR5 is detectable** | CD8_T, CD4_T Treg, CD14_mono, and CD16_mono |
| **Two examples of detectable expression** | CD8_T and CD14_mono |
| **Cluster with lower/little detectable expression** | B_cell |
| **Overall observation** | CCR5 expression is relatively low and appears in scattered cells, with more detectable expression in selected T-cell and monocyte clusters. |

<img width="1362" height="637" alt="image" src="https://github.com/user-attachments/assets/ef23ad00-a5dc-4438-aa16-2f3367756c0f" />

**Figure 3.** CCR5 gene-expression map of the COVID-19 PBMC dataset showing CCR5 expression across annotated cell clusters. Stronger expression is observed in selected T-cell and monocyte populations, while other clusters show little or no detectable expression.

# PART F. Marker Genes

| Question | Answer |
|---|---|
| **a. Which cells/cluster did you select?** | CD14_mono |
| **b. Does your selected group show higher, lower, or similar expression compared with the comparison cells?** | Higher/more detectable CCR5 expression compared with several other cell groups. |
| **c. What does the expression plot add that was not obvious from the UMAP/t-SNE map?** | The dot plot directly compares CCR5 expression across cell types. Color represents average expression, while dot size represents the fraction of cells with detectable (non-zero) expression. This provides quantitative context that is less obvious from the UMAP/t-SNE map alone. |

<img width="427" height="605" alt="image" src="https://github.com/user-attachments/assets/5dad7ca8-dfac-42a7-b2a4-2b2047fe22cd" />

**Figure 4.** Dot plot showing CCR5 expression across cell types in the COVID-19 PBMC dataset. Dot color represents average CCR5 expression, while dot size represents the fraction of cells with detectable (non-zero) CCR5 expression.

# PART G. Disease Gene vs. Marker Gene

| Item | Answer |
|---|---|
| **a. Cluster/cell type examined** | CD14_mono |
| **b. Marker gene 1** | LYZ |
| **c. Marker gene 2** | S100A9 |
| **d. Marker gene 3** | S100A8 |
| **e. Does the assigned gene behave like a cell-type marker?** | No. CCR5 is detectable in CD14_mono, but it is not listed among the marker genes shown for this cluster. Therefore, CCR5 does not appear to uniquely characterize the CD14_mono cell type in this dataset. |

<img width="1235" height="534" alt="image" src="https://github.com/user-attachments/assets/84e76efc-4922-47b9-9c1b-f08778a609bf" />

**Figure 5.** Cluster marker genes for CD14_mono in the COVID-19 PBMC dataset. LYZ, S100A9, and S100A8 are among the highest-ranked marker genes shown for the CD14_mono cluster

# PART H. Connection to Genome Browser and ClinVar

| Item | Answer |
|---|---|
| **a. Assigned disease gene** | CCR5 |
| **b. Marker gene** | LYZ |
| **c. Which gene shows a more cell-type-restricted expression pattern?** | LYZ |
| **d. Which gene appears more broadly expressed?** | CCR5 |
| **e. What does this comparison teach you about the difference between a disease-associated gene and a cell-type marker gene?** | A cell-type marker gene such as LYZ shows a more characteristic expression pattern in specific cell populations, especially monocyte-related cells. A disease-associated gene such as CCR5 can be biologically relevant without being specific to one cell type. Therefore, disease-associated genes and cell-type marker genes can have different expression patterns and purposes. |

<img width="445" height="620" alt="image" src="https://github.com/user-attachments/assets/1a3d3684-09b9-4f5f-9443-9922f3208692" />

**Figure 6.** LYZ expression across annotated cell populations in the COVID-19 PBMC dataset. LYZ shows stronger expression in monocyte-related populations, particularly CD14_mono, CD16_mono, cDC, and Mono_prolif, providing a comparison with the more limited CCR5 expression pattern.

# PART I. Connect the Cell Browser Result to Your Previous Genome Activity

1. On which chromosome is your assigned gene located? Use your previous UCSC Genome Browser activity.
   
Chromosome 3
   
2. What disease-associated variant did you examine previously?

CCR5-Δ32 (CCR5 Delta 32) — a 32-base-pair deletion in the CCR5 gene.
   
3. In the current Cell Browser dataset, which cell type(s) express the gene?

CCR5 is detectable mainly in T-cell and monocyte-related cell types, including CD14_mono and and some. The expression is relatively low and appears in only some cells within some populations.
   
4. Does the observed cell expression make biological sense based on what you already know about the gene's function or associated disease? Explain in 3-5 sentences.

Yes. CCR5 is involved in the immune system. It makes sense that it is found in some T cells and monocytes. This matches its role in immune responses.
   
5. Can this single Cell Browser dataset prove that the gene causes the disease? Explain why or why not.

No. The dataset only shows where CCR5 is expressed. It cannot prove that CCR5 causes the disease and more research and experiments are needed.

# PART J. Short Reflection

1. What did the UCSC Cell Browser show you that the UCSC Genome Browser could not?

The Cell Browser showed me which cells have CCR5 and how much they express it. The Genome Browser mainly shows the gene’s location and DNA information.

2. Why can the same gene have different expression levels among different cell types?

Different cells have different jobs in the body. Because of this, some genes are more active in certain cells than others.

3. Why should you be careful when interpreting a gene that shows zero or very low expression in single-cell data?

A low or zero result does not always mean the gene is not there. Sometimes the gene is just not detected in that cell because of limits in the data.

4. Why is it useful to combine information about genomic location, genetic variants, and cell-specific gene expression?

It helps us understand a gene from different points of view. We can see where the gene is, what changes it may have, and which cells use it.

5. What was the most interesting observation you made about your assigned gene?

I found it interesting that CCR5 was mostly seen in some T cells and monocytes. Its expression was not very high, but it could still be detected in some cells.

# References and Links

UCSC Cell Browser – COVID-19 PBMC dataset
https://cells.ucsc.edu/?ds=covid19-pbmc

UCSC Genome Browser
https://genome.ucsc.edu/

ClinVar – NCBI (only if you actually used ClinVar in your previous activity)
https://www.ncbi.nlm.nih.gov/clinvar/
