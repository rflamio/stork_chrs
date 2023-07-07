# stork_chrs

R markdown files and companion files associated with the manuscript "Chromosome-level genome of the wood stork (Mycteria americana) provides insight into avian chromosome evolution."

Description of R markdown files:

1. Genome_Comparison.Rmd: R markdown for variant calling of sockeye salmon dataset from raw reads to filtered variants.

Description of companion files in  (files needed for Genome_Comparison.Rmd):

1. map_S.sh: Script for mapping raw reads to the sockeye reference genome.
2. coordsort_S.sh: Script for sorting the BAM files by coordinate (round 1). 
3. markdup_S.sh: Script for marking and removing duplicates.
4. bcoordsort_S.sh: Script for sorting the BAM files by coordinate (round 2). 
5. settags_S.sh: Script for fixing NM, MD, and UQ tags. 
6. addrg_S.sh: Script for adding read groups.
7. baserecalib_S.sh: Script for generating a recalibration table. Note: The file for known sites "Christensen_filter1.vcf.gz" was retreived from Christensen et al. (2020) and is not provided here. 
8. applyrecalib_S.sh: Script for applying the recalibration.
9. haplotypecaller_S.sh: Script for calling variants per sample. 
10. revised_S.bed: Intervals list with 29 sockeye salmon chromosomes and mitochondrion for GenomicsDBImport. 
11. consolidate_S.sh: Script for consolidating GVCFs.
12. jointcall_S.sh: Script for genotyping GVCFs.
13. hardfilt_S.sh: Script for hard filtering of variants. 
