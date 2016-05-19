# RNASeq unmapped contigs

This project will assemble the unmapped reads from RNASeq to produce contigs that
will be used to search for evidences of Virus.

## Steps

* Map RNAseq reads to genome.
* Extract RNASeq reads that do not map against the genome.
* Use RepARK assembler to produce contigs from unmapped reads.
* Use Minia assembler to produce contigs from unmapped reads.