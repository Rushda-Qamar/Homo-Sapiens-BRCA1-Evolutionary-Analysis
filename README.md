# BRCA1 Gene Analysis – Bioinformatics Project

## Project Overview
This project focuses on analyzing the Homo sapiens BRCA1 (Breast Cancer 1) gene using its mRNA reference sequence **NM_007294.4** downloaded from NCBI.

The workflow includes:
- Sequence retrieval
- BLAST analysis
- Multiple sequence alignment (MSA)
- Interpretation of conserved regions

## About the BRCA1 Gene
- **Gene Name:** BRCA1 – Breast Cancer 1, DNA Repair Associated
- **Organism:** Homo sapiens (Human)

## Data Source
The BRCA1 reference sequence used in this project was downloaded from:
- NCBI Nucleotide Database
- **Accession ID:** NM_007294.4
- **Format:** FASTA (.fasta)

## Tools and Software Used

| Task                       | Tool                                |
|---------------------------|--------------------------------------|
| Sequence retrieval        | NCBI                                 |
| BLAST search              | NCBI BLASTn                          |
| Downloading BLAST hits    | BLAST FASTA download                 |
| MSA                       | Clustal Omega / ClustalW             |
| Visualization & analysis  | Jupyter Notebook (Biopython, Matplotlib) |
| File formats used         | FASTA, ALN                           |

## Workflow Steps

### 1. Retrieve BRCA1 Sequence
- Go to the NCBI Nucleotide database
- Search “BRCA1 Homo sapiens”
- Select **NM_007294.4**
- Download the sequence in FASTA format

### 2. Run BLASTn
- Upload or paste the BRCA1 FASTA sequence in BLASTn
- Select the default **nr/nt** database
- Run BLAST to find homologous sequences
- Download the top **10–20 sequences** in FASTA format

### 3. Multiple Sequence Alignment (MSA)
- Upload the multi-FASTA file to Clustal Omega (web version)  
  OR use ClustalW locally
- Export the alignment file in **.aln** format
- Analyze:
  - Conserved regions
  - Mutations across homologs
  - Evolutionary relationships

## Project Goals
- Understand how to retrieve genetic data
- Learn BLAST for similarity searching
- Perform multiple sequence alignment
- Interpret alignment results
- Build confidence for genome analysis tasks