# MCB 124 Maxiproject

## What is this project?

This project is an in-depth analysis of Ribose-5-phosphate isomerase, an enzyme essential to the PPP and Calvin Cycle.

## How is this project organized?

- `/E_coli` contains the sequence and crystallographic information for the protein in E. coli, which is the reference organism. It also contains Jpred secondary structure predictions.
- `/Assignments` contains the canvas-submitted written assignments for the project.
	- `Assignment 1.rtf` is about the evolutionary and biological context of rpiA
- `/MSA` contains multi-sequence alignments, which are analyzed in assignment 2.
	- `PF06026_seed` is a pfam alignment
	- `input.fasta` is a combination of all 6 sequence fasta files. This was used as an input for the alignment.
	- `output` files are alignments given from [Clustal Omega](https://www.ebi.ac.uk/Tools/msa/clustalo/), in various formats (see extensions)
	- `diverse_region` gives the sequences of all 6 organisms that represent the most diverse sequence of the protein, which is analyzed in assignment 2.
- `/FASTA` contains fasta files for E. coli and 5 other organisms with sequence identity < 50%. See assignment 2.
	- Note: the fasta files are named for the UniProt accession numbers.
