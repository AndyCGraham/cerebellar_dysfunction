# cerebellar_dysfunction
This repository contains code analysing a pilot scRNA-seq dataset, from the cerebellum of mice which are either WT or contain a mutation in a Transcription Factor (TF), which is important for cerebellar development.

code/scanpyQC.ipynb QC's, normalises, clusters, annotates the cells, and identifies clusters whose abundance differs in the mutated sample.
code/deeper_analysis.ipynb assesses the effect of the mutation on gene and gene-set expression in very cluster, developmental pseudotime trajectories, and predicts target genes of the TF using a random forrest model.
