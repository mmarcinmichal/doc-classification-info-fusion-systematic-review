# Supplementary Materials and Replication Package for - Document Classification Pattern Recognition via Information Fusion: A Systematic Review of Multimodal and Multiview Representation Approaches

This repository provides the complete replication package and supplementary materials supporting the systematic review submitted to *Information Fusion*.

## Abstract
Information fusion improves document classification through integration of multiple data sources (multimodal) or representations (multiview).  
This review analyses 139 primary studies, introduces a formal framework structuring the field, presents qualitative trend synthesis, and performs a random-effects meta-analysis quantifying performance gains.

Key findings:
- **Multimodal fusion:** significant accuracy improvement (+5.28 pp, *p* = 0.0016); F1 positive but not statistically significant.  
- **Multiview fusion:** consistent gains in accuracy (+4.67%), F1 (+3.08%), and recall (*p* < 0.05).  
- **Reproducibility gap:** statistical validation used in only 11.8% (multimodal) and 23.3% (multiview) of studies.

The study contributes a unifying framework, the first quantitative synthesis in this domain, and methodological guidance for rigorous evaluation.

## Repository Contents

### Data and metadata
- `2-articles-information-fusion-summarisation-cleaned.xlsx`  
- `bibtex-information-fusion-document-classification.bib`  

### Qualitative analysis
- `qualitative-analysis.Rmd`  
- `qualitative-analysis.html`  

### Quantitative meta-analysis
- `quantitative-analysis.Rmd`  
- `quantitative-analysis.html`  

### Supplementary documentation
- `supplementary-materials.pdf`

## Reproducibility Statement
All statistical results, tables, and figures reported in the article can be reproduced directly from the provided R Markdown scripts using the included datasets and documented procedures.

## Requirements
- R (≥ 4.x)  
- Required R packages specified within the scripts

## Citation
- **Article DOI:** https://doi.org/10.1016/j.inffus.2026.104247  
- **Replication package DOI:** https://doi.org/10.5281/zenodo.17141560

## Author and Affiliation
**Marcin Michał Mirończuk**  
National Information Processing Institute, Warsaw, Poland  
Contact: marcin.mironczuk@opi.org.pl