# PB-Final_Project
RNA-Seq Profiling of Drosophila (Fruit Fly) Cells after the  depletion of Pasilla Gene - Using Galaxy software and using the concepts of Bioinformatics, performed RNA-Sequencing of Drosophila Cells on the treated to obtain differentially expressed genes and enriched pathways and analyze them.

### Motivation
Our interest in the particular gene was piqued when we read the study of brooks et al. The paper explored the possibility of conservation of regulatory codes and concluded that the rna map of ps and nova1/2 is highly conserved between mammals and insects.

### Data Sets
4 untreated samples: gsm461176, gsm461177, gsm461178, gsm461182
3 treated samples (pasilla gene depleted by rnai): gsm461179, gsm461180, gsm461181

Each sample constitutes a separate biological replicate of the corresponding condition (treated or untreated). Moreover, two of the treated and two of the untreated samples are from a paired-end sequencing assay, while the remaining samples are from a single-end sequencing experiment.

### Steps Used
- Quality Control
- Mapping
- Counting No of Reads
- Differential Gene Expression Analysis
- Functional Enrichment Analysis of Differentially expressed genes

### Conclusion
- Depleting pasilla gene affects the splicing rate of gene a and b differently.
- Upregulation of gene a and downregulation of gene b suggest that pasilla suppresses and promotes their splicing rate, respectively.
- Pasilla depletion leads to under representation of spliceosome pathway genes, implying that core spliceosome genes are not affected.
- Under representation of the spliceosome pathway does not mean no change in splicing events, and analyzing differential splicing events can provide better insights.
- Pasilla depletion significantly affects the expression levels of genes involved in the glycolysis pathway.
- The observed differential expression in the glycolysis pathway suggests that pasilla depletion has cascading effects on other genes, possibly through altered alternative splicing patterns.
- Pasilla and nova1/2 genes are involved in alternative splicing regulation in insects and mammals, respectively.
- The rna maps of pasilla and nova1/2 are highly conserved between mammals and insects, suggesting similar splicing patterns and conserved roles in biological pathways.
- The study's results can be extended to studying nova genes in mammals


