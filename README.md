# Ting_signature_analyse

In this github you can find the script used for the analysis of the cancer signature, the data required and some results

### Data used (In DATA repository)

"BLUEPRINT_fragments_good.tsv": File that contains genes and coordinates of their promoter based on hg19/18?

"Final.Tumor.RNAseq.sig.txt": File that contains marker genes of the signature and their weight for each of the cell type.

"Final.Tumor.sig.annotation.txt": File that contains marker CpGs of the signature and the genes that they are associated to.

"pchic.RData": File that contains a network of chromatin conformation network that will be used to represent promoter/enhancer contacts.

### Scripts (In Script repository)

"Analyse_overlap_signatures.Rmd":






### Comments

In the analysis, promoter can be associated to more than one gene. From the cpgs signature file, genes are not filtered by the location of the methylation and genes that correspond to cpgs signature can be not affected in their promoter.
