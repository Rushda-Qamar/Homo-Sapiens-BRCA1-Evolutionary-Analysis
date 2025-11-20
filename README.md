BRCA1 Gene Analysis – Bioinformatics Project

Project Overview

This project focuses on analyzing the Homo sapiens BRCA1 (Breast Cancer 1) gene, using its mRNA reference sequence NM_007294.4 from NCBI.
The workflow includes sequence retrieval, BLAST analysis, multiple sequence alignment, and interpretation of conserved regions.

About the BRCA1 Gene
Gene Name: BRCA1 – Breast Cancer 1, DNA Repair Associated
Organism: Homo sapiens (Human)

Data Source
The BRCA1 reference sequence used in this project was downloaded from:
NCBI Nucleotide Database
Accession ID: NM_007294.4
Format: FASTA (.fasta)

Tools & Software Used

Task	Tool
Sequence retrieval	NCBI
BLAST search	NCBI BLASTn
Downloading hits	NCBI BLAST result FASTA download
MSA	Clustal Omega / ClustalW
Visualization & analysis	Jupyter Notebook (Biopython, Matplotlib)
File formats used	FASTA, ALN

Workflow Steps
1️⃣ Retrieve BRCA1 Sequence

Go to the NCBI nucleotide database.
Search “BRCA1 Homo sapiens”.
Select NM_007294.4.
Download in FASTA format.

2️⃣ Run BLASTn

Upload or paste the BRCA1 FASTA sequence in BLASTn.
Select default database: nr/nt.
Run BLAST to find homologous sequences.
Download top 10–20 aligned sequences in FASTA format.

3️⃣ Multiple Sequence Alignment (MSA)

Upload the multi-FASTA file to Clustal Omega (web version)
or use ClustalW locally.
Export the alignment file as .aln.
This alignment helps identify:
Conserved regions
Mutations across homologs
Evolutionary relationships

Project Goals

Understand how to retrieve genetic data
Learn BLAST for similarity searching
Perform multiple sequence alignment
Interpret alignment results for biological meaning
Build confidence for genome analysis tasks