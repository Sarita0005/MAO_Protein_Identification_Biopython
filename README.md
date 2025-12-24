# MAO Protein Identification, Validation, and Phylogenetic Analysis using Biopython and BLASTP
# Overview
This project demonstrates an end-to-end bioinformatics workflow for protein identification, validation, and evolutionary analysis using the MAO (Monoamine Oxidase) protein as a case study.
It integrates annotation-aware sequence extraction, BLAST-based functional validation, and comparative protein phylogenetics across multiple species.

# Workflow
 # Module 1: MAO Protein Identification and Validation
- Retrieved the MAO gene in GenBank format from NCBI
- Parsed GenBank annotations using Biopython
- Extracted the CDS and translated it into a protein sequence
- Validated protein identity using BLASTP against the NCBI nr database
- Interpreted BLAST results using:
- Percentage identity
- E-value
- Alignment coverage

 # Module 2: Comparative and Phylogenetic Analysis of MAO-B
- Identified homologous MAO-B protein sequences from multiple species using BLASTP
- Downloaded full-length protein FASTA sequences
- Performed multiple sequence alignment (MSA) using Clustal Omega
- Constructed a Neighbor-Joining phylogenetic tree based on protein sequence divergence
- Visualized and interpreted evolutionary relationships using Biopython and Matplotlib

# Tools Used
- Python
- Biopython
- NCBI BLAST / BLASTP
- Clustal Omega
- Matplotlib

# Key Results
- Protein Identification & Validation
- Extracted a full-length MAO protein (520 amino acids)
- BLASTP confirmed high sequence identity (>95%) with annotated MAO-B proteins
- Alignment covered the entire protein length, confirming accurate CDS extraction
- Phylogenetic Analysis
- MAO-B protein shows high conservation among primates
- Homo sapiens MAO-B clusters most closely with Pan troglodytes
- Ursus arctos forms a distant outgroup, reflecting evolutionary divergence
- Phylogenetic relationships align with known mammalian evolution

# Input
- GenBank file (.gb)
- Protein FASTA sequences (.fasta)
# Output
- Translated MAO protein FASTA file
- BLASTP validation summary
- Multiple sequence alignment file
- Phylogenetic tree:
- Newick format (.dnd)
- High-resolution PNG image

# Purpose
This project highlights core bioinformatics competencies including:
- Annotation-aware sequence analysis
- Protein validation using BLAST
- Multiple sequence alignment
- Phylogenetic tree construction and interpretation
