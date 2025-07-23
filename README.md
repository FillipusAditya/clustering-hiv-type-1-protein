# HIV-1 Protein Clustering using Graph-Based Algorithms (DPClusO & BiClusO)

## Overview
This project focuses on clustering key HIV-1 target proteins using graph clustering algorithms, specifically DPClusO and BiClusO. The study focuses on four major protein targets: HIV Protease, Reverse Transcriptase (RT), Envelope Glycoprotein, and Capsid. The project was conducted at the Computational Systems Biology Laboratory, NAIST.

## Methodology
- **Data Collection:** Protein structures were retrieved from the Protein Data Bank (PDB), filtered to four key categories.
- **Preprocessing:** FASTA sequences were extracted, cleaned, and deduplicated.
- **Clustering:** Applied DPClusO and BiClusO based on sequence similarity (graph-based network).
- **Visualization:** Nodes represent proteins, edges represent similarity, clusters are visualized separately.

## Results Summary
- Total protein sequences: 343
- Number of clusters: 10
- Protein categories: RT, Protease, Envelope Glycoprotein, Capsid
- Clustering helps identify structural similarity and potential drug target candidates.
  <img width="975" height="564" alt="image" src="https://github.com/user-attachments/assets/2a45bba0-fd7f-4c7e-90d6-f7e4201d5ea5" />


## Technologies Used
- Python (pandas, biopython, matplotlib, networkx)
- DPClusO & BiClusO (Java/C++)

## File Structure
- `hiv_type_1.ipynb`: Main notebook for preprocessing and clustering

## Purpose and Impact
- Enables identification of potential HIV-1 drug inhibitors
- Supports drug-target interaction studies
- Dataset can be used to train ML models for bioinformatics applications

## References
- DPClusO: Altaf-Ul-Amin et al. (2006)  
- BiClusO: Hasan, Md. Al-Amin et al. (2013)  
- RCSB PDB: https://www.rcsb.org/
