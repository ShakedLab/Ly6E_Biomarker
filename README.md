# Ly6E_Biomarker
Raw and processed data (scRNA-seq, RNA-velocity, CYTOF) for Benguigui &amp; Cooper et al. (2024, Cancer Cell).

Paper: https://www.cell.com/cancer-cell/fulltext/S1535-6108(23)00433-6

Highlight Article: https://www.nature.com/articles/s41577-024-00993-y (Nature Reviews Immunology)

## Samples:

**Non_Responder** - 4T1 (Murine Breast Carcinoma, BALB/c), Parental
 
**Responder** - 4T1 (Murine Breast Carcinoma, BALB/c), Mutagenised 

## Data structure, within each sample folder:

**CellRanger** - full CellRanger (v4.0.0) output, including:
1. Raw (/raw_feature_bc_matrix), unfiltered count matrices
2. Filtered (/filtered_feature_bc_matrix) count matrices
3. A full alignment summary (web_summary.html)

**CYTOF** - Processed .fcs files (all dead-cells, debris removed, CD45+ cells gated)

**VeloCyto** - Processed .loom file (for the calculation of RNA-velocity)

## Seurat Objects:
**Neutrophils** - Filtered & Clustered (as visualized in Fig 3.): https://web.tresorit.com/l/9UzVT#pf2ALbHPqrcLuqi7gm-75A
