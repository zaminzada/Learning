Read Counts

In the context of genomics or transcriptomics, "read counts" refer to the number of times a particular sequence (read) is observed in a sequencing experiment. When researchers conduct sequencing experiments, they generate millions of short DNA or RNA sequences (reads) that represent fragments of the genome or transcriptome. These reads are typically aligned to a reference genome or transcriptome to determine their origin and to quantify the abundance of different sequences. 

Read counts are essential for various analyses in genomics and transcriptomics, including differential expression analysis, variant calling, and quantification of genomic features such as genes or transcripts. By counting the number of reads that align to specific genomic regions (such as genes), researchers can infer the expression levels of those regions. 

For example, in RNA sequencing (RNA-seq), read counts are used to quantify the expression levels of genes or transcripts. Each read that aligns to a gene or transcript is counted, and these counts are used as a measure of gene expression. Higher read counts typically indicate higher expression levels, while lower read counts indicate lower expression levels. 

It's important to note that read counts are raw counts and do not account for differences in sequencing depth or other experimental factors. Therefore, read counts are often normalized before downstream analysis to account for these factors and to enable comparison across samples or experiments. Common normalization methods include Reads Per Kilobase Million (RPKM), Reads Per Million (RPM), or the more robust methods like DESeq2's normalization.
