# Project_2D_R

The following files are needed to run the code in R studio:

1. Human and Mouse PPAR alpha fasta files (uploaded here)
2. Human PPAR alpha ligand binding domain crystal structure PDB file (uploaded here)

The Human PPAR alpha and Mouse PPARA alpha protein sequence files were downloaded from Uniprot with the accession IDs Q07869 and P23204 respectively (https://beta.uniprot.org/uniprotkb/Q07869/entry) (https://beta.uniprot.org/uniprotkb/P23204/entry). The sequences saved as fasta files were used to perform pairwise sequence alignment to compare the protein sequences of human PPAR alpha and mouse PPAR alpha. 

The Human PPAR alpha ligand binding domain crystal structure data was obtained from the Protein Data Bank with the accession ID 2ZNN (https://www.rcsb.org/structure/2ZNN). The structure was used as a template to make a homology model using the mouse PPAR alpha protein sequence, since a mouse PPAR alpha crystal structure is not available.
To create the homology model the website (https://swissmodel.expasy.org/) was used. I clicked "start modeling" > "user template" and then pasted the mouse PPAR alpha sequence from Uniprot into the target sequence box. The Human PPAR alpha ligand binding domain crystal structure PDB file was entered as the template file and then "Build Model" was clicked. 

The Scientific Question is:
Do the amino acid sequences and structure between the peroxisome proliferator-activated receptor alpha in humans and mice share enough similarity to consider the PPAR alpha mice model an accurate model of the PPAR alpha receptor in humans?

The Scientific Hypothesis is:
If the peroxisome proliferator-activated receptor alpha is mainly activated through the ligand binding domain, and has been shown to have different binding affinities to ligands between the species human and mouse, then there should be differences in the amino acid residues of the human PPAR alpha receptor ligand binding domain and mouse PPAR alpha receptor ligand binding domain.
