# tRNA Binary Classifier
My attempt at creating a binary classifier where, given a sequence of DNA, the classifier determines if your sequence is a tRNA sequence.

tRNA is a crucial molecule in protein synthesis and thus, their sequences are highly conserved. Eukaryotic tRNAs range between 75 and 90 basepairs. They are responsible for carrying the correct amino acid to the ribosome.

![image](https://github.com/malabi3393/tRNA_Binary_Classifier/assets/66332965/245c5aad-4f1f-47e2-b502-13d1bf0f4623)
Source: https://en.wikipedia.org/wiki/Transfer_RNA

tRNA sequences were obtained from http://gtrnadb.ucsc.edu/. Given the sequences, I calculated the probability of a base (A,C, G or T) for every given position in the sequence. 

$`\ P(tRNA_{n}) = \sum_{i=0}^{n} \log(P(b_{i}))`$

