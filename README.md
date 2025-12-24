# Genomic-and-Protein-Sequence-Analysis/
MAO Protein Identification and Validation using Biopython and BLASTP
# Overview
This project demonstrates a professional bioinformatics workflow involving gene annotation parsing, protein sequence extraction, and functional validation using BLAST.

# Workflow
- Retrieved MAO gene in GenBank format from NCBI
- Parsed GenBank annotations using Biopython
- Extracted CDS and translated it into a protein sequence
- Validated protein identity using BLASTP against the NCBI nr database
- Interpreted similarity using identity percentage, E-value, and alignment coverage

# Tools Used
- Python
- Biopython
- NCBI BLAST
  
# Key Results
- Extracted a full-length MAO protein (520 aa)
- BLASTP confirmed high sequence identity (>95%) with annotated MAO-B proteins
- Alignment covered the full protein length, confirming accurate extraction

# Input
- GenBank file (.gb)
# Output
- Protein FASTA file
- BLASTP interpretation summary

# Purpose
This project highlights annotation-aware sequence analysis and validation, a core bioinformatics competency in research and industry.
