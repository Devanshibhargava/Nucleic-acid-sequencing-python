# Nucleic-acid-sequencing-python

This repository contains a .ipynb notebook which is a compilation of my notes from coursera's guided project - Reverse and complement nucleic acid sequences (DNA, RNA) using Python.

The objective of this project is to build a method that creates reverse, complement, and reverse‐complement sequence for any given DNA and RNA sequences using Python. As a final step of the project, the method will be used to analyse the whole genome sequence of coronavirus.

## Background

Computational sequence analysis of DNA, RNA or peptide sequence provides information on its properties, biological function, structure and evolution(1). Sequence alignment tools such as FASTA and BLAST help extract sequence identity and similarity between protein sequences of any organisms(2).
One function of the alignment tools is to determine reverse, complement and reverse-complement sequences for any nucleic acid sequence. 

### Complementary Base Pairing Rule

Given below are the complementary base pairing rules for DNA and RNA respectively with the only difference of Adenine (A) is complement with Thymine (T) in DNA, whereas Adenine (A) is complement with Uracil (U) in RNA:

  DNA complementary base pairing rule
    A -> T
    C -> G
    G -> C
    T -> A

  RNA complementary base pairing rule
    A -> U
    C -> G
    G -> C
    T -> A

### Reverse, complement and reverse-complement sequences

DNA has two strands of nucleotide sequences (it is a double helix) that go in opposite direction. The "reverse" sequence is the template strand being flipped such that the 3' end of the template strand is the 5' end of the reverse. Because of the nature of complementary base pairing a "complement" strand is the strand that will pair with the template strand of nucleic acid. A reverse-complement strand is a complement strand of the reverse strand. 

For example, 

for the template DNA strand as follows:
5' ATGCCGCTAAACT 3'

the reverse strand is:
5' TCAAATCGCCGTA 3'

the complementary strand is:
5' AGTTTAGCGGCAT 3'

and the reverse-complement strand is:
5' TACGGCGATTTGA 3'

## Project code

Refer to the RNA_DNA sequencing project with Python.ipynb file

## References: 
1. Prjibelski, A. D., Korobeynikov, A. I., &amp; Lapidus, A. L. (2019). Sequence analysis. Encyclopedia of Bioinformatics and Computational Biology, 292–322. https://doi.org/10.1016/b978-0-12-809633-8.20106-4 
2. Pathak, R. K., Singh, D. B., &amp; Singh, R. (2022). Introduction to basics of bioinformatics. Bioinformatics, 1–15. https://doi.org/10.1016/b978-0-323-89775-4.00006-7 
