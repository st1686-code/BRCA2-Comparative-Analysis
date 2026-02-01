# BRCA2-Comparative-Analysis

## Identification of BRCA2 Proteins and Transcripts Across Primates

## Project Overview

This project aims to identify BRCA2-related proteins and transcripts across four species:

- Nasalis larvatus  
- Plecturocebus cupreus  
- Saguinus oedipus  
- Homo sapiens (positive control)

The goal is to compare evolutionary conservation and genomic localization of the BRCA2 gene among primates.

## Project Workflow

### 1. Protein Identification
- The human BRCA2 protein sequence was used as a query.
- BLASTp searches were performed against the predicted protein sets of all four genomes.
- Candidate BRCA2-like proteins were identified based on sequence similarity.

### 2. Transcript Retrieval
- Corresponding transcript IDs were retrieved from GTF annotation files.
- Transcript analysis depended on the presence of annotated CDS features.

### 3. Genomic Localization
- Identified transcripts were used as queries in BLASTN searches.
- Genomic regions containing conserved BRCA2 loci were located.
- Conserved regions were compared across species.

## Repository Structure

- `index.html` → Project visualization and results webpage

## Tools and Methods

- BLASTp and BLASTN
- Command-line bioinformatics tools
- Genome annotation (GTF files)
- Sequence alignment

## How to Use

1. Download or clone this repository.
2. Open `index.html` in any web browser.
3. View the project results and analysis.


## Author
SUBINA
