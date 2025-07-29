# Soil Macrofauna Biodiversity Analysis – Code and Scripts Repository

This repository contains all scripts, code, and relevant resources used in the analysis of soil macrofauna communities associated with forest soil biodiversity assessments. 
The work is part of the EnGeL SOP and [BENCHMARKS](https://soilhealthbenchmarks.eu/) project and includes bioinformatic processing, spatial sampling design comparisons, and ecological statistics.

## 📁 Folder Structure

```
/code/
├── 01_sequence_processing/       # Scripts for OBITools4, VSEARCH, LULU pipelines
├── 02_sampling_analysis/         # R scripts comparing k-means vs. random sampling
├── 03_diversity_analysis/        # Scripts for alpha/beta diversity, rarefaction, NMDS
├── 04_taxonomic_assignment/      # BOLDigger or custom scripts for OTU annotation
├── utils/                        # Utility functions and helper scripts
├── data/                         # Input files (or symlinks) if appropriate
└── figures/                      # Output figures and plots
```


## 🧪 Requirements

Depending on the scripts used, you may need the following tools and packages:

### R (≥ 4.2.0)
- `vegan`
- `iNEXT`
- `ggplot2`
- `tidyverse`
- `VennDiagram`
- `lulu`
- `phyloseq`

### Python / Command-line tools
- [OBITools4](https://git.metabarcoding.org/obitools/obitools3)
- [VSEARCH](https://github.com/torognes/vsearch)
- [BOLDigger](https://github.com/DominikBuchner/BOLDigger)
- `seqkit`, `cutadapt` (optional preprocessing)

### Hardware
- A system with ≥16 GB RAM is recommended for sequence clustering and rarefaction analyses.

## ▶️ How to Run

1. **Sequence Processing**  
   Navigate to `/01_sequence_processing/` and follow the stepwise bash or Python scripts (requires FASTQ input and primer information).

2. **Sampling Design Analysis**  
   Open `/02_sampling_analysis/kmeans_vs_random.R` to replicate spatial richness comparison analyses.

3. **Diversity and Statistical Analyses**  
   Use `/03_diversity_analysis/` to run alpha/beta diversity assessments and NMDS plots.

## 📄 Data Sources

Raw and processed data used in these scripts were generated as part of the Sabugal forest biodiversity case study. For access, please contact the corresponding author or consult the project's data sharing policy.

## 📚 Citation

If you use or adapt this code, please cite:

> Steiner, L. et al. (2025). *Assessing Soil Variability in Oak and Pine Forests Through Macrofauna Communities*. Master’s Thesis. University of Coimbra.  
> Plus any additional packages or tools used (see individual scripts for details).

## 📬 Contact

For questions, please contact:  
**Luis Kalchhauser Cunha** – ewormuc@gmail.com

---


