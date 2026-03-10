---
title: Efficient Inference for Sparse Latent Variable Models of Transcriptional Regulation
authors:
- Zhenwen Dai
- Mudassar Iqbal
- \Neil D\ Lawrence
- Magnus Rattray
date: '2017-12-01'
publishDate: '2026-03-10T23:51:22.092805Z'
publication_types:
- article-journal
publication: '*Bioinformatics*'
doi: 10.1093/bioinformatics/btx508
abstract: 'Regulation of gene expression in prokaryotes involves complex co-regulatory
  mechanisms involving large numbers of transcriptional regulatory proteins and their
  target genes. Uncovering these genome-scale interactions constitutes a major bottleneck
  in systems biology. Sparse latent factor models, assuming activity of transcription
  factors (TFs) as unobserved, provide a biologically interpretable modelling framework,
  integrating gene expression and genome-wide binding data, but at the same time pose
  a hard computational inference problem. Existing probabilistic inference methods
  for such models rely on subjective filtering and suffer from scalability issues,
  thus are not well-suited for realistic genome-scale applications. Results: We present
  a fast Bayesian sparse factor model, which takes input gene expression and binding
  sites data, either from ChIP-seq experiments or motif predictions, and outputs active
  TF-gene links as well as latent TF activities. Our method employs an efficient variational
  Bayes scheme for model inference enabling its application to large datasets which
  was not feasible with existing MCMC-based inference methods for such models. We
  validate our method on synthetic data against a similar model in the literature,
  employing MCMC for inference, and obtain comparable results with a small fraction
  of the computational time. We also apply our method to large-scale data from Mycobacterium
  tuberculosis involving ChIP-seq data on 113 TFs and matched gene expression data
  for 3863 putative target genes. We evaluate our predictions using an independent
  transcriptomics experiment involving over-expression of TFs.'
---
