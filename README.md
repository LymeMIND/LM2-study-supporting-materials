## <u>LM2-study-supporting-materials as a supplement for:</u>

# Predicting Lyme Disease from Patients’ Peripheral Blood Mononuclear Cells Profiled with RNA-sequencing

<b>Daniel J.B. Clarke<sup>1,+</sup>, Alison W. Rebman<sup>2,+</sup>, Allison Bailey<sup>1</sup>, Megan L. Wojciechowicz<sup>1</sup>, Sherry L. Jenkins<sup>1</sup>, John E. Evangelista<sup>1</sup>, Matteo Danieletto<sup>3</sup>, Jinshui Fan<sup>2</sup>, Mark Eshoo<sup>4</sup>, Michael Mosel<sup>5</sup>, William Robinson<sup>6</sup>, Nitya Ramadoss<sup>6</sup>, Jason Bobe<sup>3</sup>, Mark J. Soloski<sup>2,\*</sup>, John N. Aucott<sup>2,\*</sup>, Avi Ma’ayan<sup>1,\*</sup></b>

<small>
<sup>1</sup> Department of Pharmacological Sciences; Mount Sinai Center for Bioinformatics; Icahn School of Medicine at Mount Sinai, One Gustave L. Levy Place, Box 1603, New York, NY 10029, USA<br />
<sup>2</sup> Lyme Disease Research Center, Division of Rheumatology, Department of Medicine, Johns Hopkins University School of Medicine, Baltimore, MD, United States<br />
<sup>3</sup> Department of Genetics and Genomic Sciences; Icahn School of Medicine at Mount Sinai, One Gustave L. Levy Place, Box 1498, New York, NY 10029, USA<br />
<sup>4</sup> BlueArc Biosciences, San Diego<br />
<sup>5</sup> Janus-I Science Inc. Vista, California<br />
<sup>6</sup> Department of Medicine, Division of Immunology and Rheumatology, Stanford University School of Medicine<br />
<sup>+</sup> Contributed equally
</small>

## Outline

To view the notebook, data, and webviewer online, visit <https://commons.lymemind.org/>. This repository contains all the source code and de-identified data for the project.

### [LM2_all_figures.ipynb](./LM2_all_figures.ipynb)

This is a jupyter notebook which was used to generate all of the LM2 figures. It was run with the **original data** which is not publicly available, please contact us if you'd like to access to that data. Alternatively de-identified version of that same data has been provided and can be used instead to an extent.

### [Data](./data)

This is de-identified data which can be used to re-produce our analysis or find additional things about our cohort as a whole without per-patient specificity.

### [Webview](./webview)

This interactive viewer enables you to explore the <a href="https://www.lymemind.org/">LymeMIND2</a> patient cohort in gene expression space. Each point on the map corresponds to a participant where the position of each participant was computed based on a UMAP projection of their PMBC mRNA RNA-seq expression vector. Enrichment analysis is applied to explore enriched terms for each cluster. You can explore these enriched terms by clicking on a cluster to review the table below. These enrichment results were computed by performing differential expression between clusters and using the most significantly up and down regulated genes to query with <a href="http://maayanlab.cloud/Enrichr/">Enrichr</a>. The <a href="https://maayanlab.github.io/react-scatter-board/">react scatter board widget</a> is used to render this plot.

