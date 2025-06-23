# link-node-enrichment-model
This repository contains the code and data for our research paper:

**"Link and node feature enrichment for cancer driver gene prioritization model"**

We propose a GNN-based model that enhances both graph structure and node representations:
- **Link enrichment**: Add edges to the PPI graph using gene co-expression patterns derived from single-cell RNA-seq data.
- **Node feature enrichment**: Combine biological features (gene expression, methylation, CNA, mutation) with **Weisfeiler-Lehman (WL) graph kernel features** to provide rich node representations.

