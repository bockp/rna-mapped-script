# RNASeq unmapped contigs comparison project

This project will assemble the unmapped reads from RNASeq data  to produce contigs. The unmapped contigs will then be compared against a local database of virii, allowing the user to find possible virii in the organism.

In the original project, the RNASeq data came from a coral, and the goal was to make this script part of a pipeline to study possible virii that had been integrated into the coral genome, and what their role was. Long-term objective of this is to figure out if these virii have a role in coral bleaching, or, more specifically, if they have a role in the prevention of coral bleaching.

This script was written in 2016, for the HPEI (Host-Parasite-Environment Interaction) lab attached to the  UPVD (University of Perpignan, Via Domitia) during a 1 week Bioinformatics internship as part of the thrid year of a Bachelor's degree in SVT (Science of Life and Earth), with a specialization in Biology and Ecology.

## Steps

* Map RNAseq reads to genome.
* Extract RNASeq reads that do not map against the genome.
* Use RepARK assembler to produce contigs from unmapped reads.
* Use Minia assembler to produce contigs from unmapped reads. # the read distribution had a long tail graph, making Minia unable to create contigs from them. I didn't manage to solve the problem in the 5 days of the internship.
