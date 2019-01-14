Modulate K/R

Allows choosing the cut-off net charge and ratio K/R of the analysis. 

Usage:
modulate_KR.py <example.fasta> <output_example>
input (required): Input complete file name as for example "example.fasta"
output (required): Output file name, it generates "output_example.txt"

The input is a uniprot.fasta archive obtained from https://www.uniprot.org/uniprot/
The output file contains only the header of protein sequences which had stretches with values of 
net charge and ratio greater than or equal to the chosen cut-off.
