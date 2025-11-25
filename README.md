# Peer-to-Peer Teaching Summer Season 2025: Beyond gene lists. Explore Gene Co-expression with WGCNA package in RStudio - Yale Medical School
In the era of high-throughput sequencing, exploratory data analysis tools such as DESeq2 and edgeR have become essential for identifying differentially expressed genes in omics studies. While powerful, these methods often fall short when the goal is to understand the underlying regulatory mechanisms driving complex phenotypes. Differential expression alone does not necessarily reflect functional relevance—genes may appear significantly regulated due to secondary effects or noise, rather than their active role in phenotype generation.

To move beyond gene lists and toward functional insight, network-based approaches offer a more holistic view. This workshop will focus on Weighted Gene Co-expression Network Analysis (WGCNA), a systems biology method that identifies modules of co-expressed genes and correlates them directly with traits or phenotypes of interest. WGCNA enables the discovery of core regulatory genes and hidden pathways that might be missed by classical approaches. By integrating gene expression patterns and network topology, WGCNA provides a powerful framework for prioritizing candidate genes and unraveling the molecular architecture behind complex biological processes.

Whether you're working with development, disease models, or drug response, WGCNA offers an advanced lens to explore the coordinated behavior of genes driving the phenotypes you observe.

Attendees to this session will learn:

1. Understand the rationale and workflow of WGCNA to identify and interpret co-expression modules associated with phenotypic traits.
2. Explore network construction using soft-thresholding power selection and topological overlap matrices (TOMs);
3. Visualize module–trait associations through heatmaps and correlation plots.
4. Learn how to extract hub or driver genes from key modules using intramodular connectivity and gene significance analysis.

📘 Dataset Description

This project uses a publicly available bulk RNA-seq dataset derived from peripheral blood mononuclear cells (PBMCs) to explore immune responses during SARS-CoV-2 infection.
The dataset includes samples from:

- COVID-19 patients

- age- and sex-matched healthy controls

Originally published in the study “Systems biological assessment of immunity to severe and mild COVID-19 infections”, the dataset captures transcriptomic changes associated with mild, moderate, and severe disease. It provides a clean and well-annotated resource for demonstrating WGCNA-based construction of gene co-expression networks.

This dataset is ideal for teaching purposes because it:

- Contains a clear binary trait (COVID vs. Control)
- Has sufficient sample size for network analysis
- Shows coordinated immune-related expression changes that produce interpretable modules
   
