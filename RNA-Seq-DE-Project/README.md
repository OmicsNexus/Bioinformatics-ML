# RNA-Seq Differential Expression Project

This project performs differential gene expression analysis using DESeq2 on RNA-Seq data from GEO dataset **GSE60424**.

## Tools
- DESeq2 (R)
- STAR (alignment)
- featureCounts (quantification)
- FastQC + MultiQC (QC)

## Files
- `deseq2_analysis.R`: Main R script for DE analysis
- `data/`: Raw/processed count data
- `plots/`: Volcano, PCA, MA plots
- `report.md`: Interpretation summary
