# LM2 Data

- [LM2_Cluster_Enrich.tsv](./LM2_Cluster_Enrich.tsv): All clusters were enriched with Enrichr for select libraries and the top results were summarized in this table for the webview
- [LM2_Deidentified.tsv](./LM2_Deidentified.tsv): The de-identified & shuffled patient RNAseq data at each visit
- [LM2_Deidentified_Meta.tsv](./LM2_Deidentified_Meta.tsv): An expanded table for joining with the ids in `LM2_Deidentified.tsv`, purely for convenience as the identifiers contain all the necessary information
- [LM2_Deidentified_UMAP.tsv](./LM2_Deidentified_UMAP.tsv): Pre-computed UMAP Coordinates (see `LM2_all_figures.ipynb`) associated with the RNAseq expression of each patient sample for the webview.
