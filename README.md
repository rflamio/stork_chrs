# stork_chrs

R markdown files and companion files associated with the manuscript "Chromosome-level genome of the wood stork (*Mycteria americana*) provides insight into avian chromosome evolution."

Description of the R markdown file "Genome_Comparison.Rmd"

The R markdown contains the script for chromosome orthology analysis of the wood stork (Mycteria americana) genome with the following avian species: chicken (Gallus gallus), zebra finch (Taeniopygia guttata), common cuckoo (Cuculus canorus), Humboldt penguin (Spheniscus humboldti), and maguari stork (Ciconia maguari). Pairwise mApping Format (PAF) files for the analysis were produced using D-GENIES v1.4.0 (Cabanettes & Klopp, 2018). The following analyses are present in the markdown in this order:
1. Alignment of wood stork W and Z scaffolds with chicken and maguari stork.
2. Visualization of the known chromosomal fusion of chicken GGA4.
3. Identification of wood stork chromosome fusions by alignment with penguin and chicken.
4. Chromosome alignments between wood stork chromosomes 25-31 and orthologous chromosomes in other avian genomes (most alignments visualized used penguin, maguari stork, and chicken, rather than finch or cuckoo).
5. Alignments between avian chromosomes (mostly microchromosomes) that had no strong evidence for orthology in the wood stork genome with the wood stork scaffolds with the best alignment. 
6. Mitochondrion alignments between the wood stork and other avian sequences. 


Description of companion files in the folder "PAF files":

1. S2Ch_paf.paf: Pairwise mApping Format (PAF) file output from D-GENIES for the comparison between the chicken and wood stork genomes.
2. S2F_paf.paf: Pairwise mApping Format (PAF) file output from D-GENIES for the comparison between the zebra finch and wood stork genomes.
3. S2Cu_paf.paf: Pairwise mApping Format (PAF) file output from D-GENIES for the comparison between the cuckoo and wood stork genomes.
4. S2P_paf.paf: Pairwise mApping Format (PAF) file output from D-GENIES for the comparison between the penguin and wood stork genomes.
5. S2S_paf.paf: Pairwise mApping Format (PAF) file output from D-GENIES for the comparison between the maguari stork and wood stork genomes.
