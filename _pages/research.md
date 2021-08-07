---
title: "Huang Lab - Research"
layout: textlay
excerpt: "Huang Lab -- Research"
sitemap: false
permalink: /research/
---

## Research
Our research is focused on examining how natural selection shapes human evolution and disease. A common theme of our work is to combine realistic biological models and machine learning techniques to make sense of large-scale genomic data.

#### 1. Population Genetics-based prediction of disease-causing variants

Millions of genetic variants have been identified in the human genome. Understanding the functional and clinical significance of genetic variants has become a central question in biology and precision medicine.
However, it is challenging to distinguish between pathogenic and benign variants. Thus, many genetic variants in patients' genomes are marked as variants of uncertain significance (VUS), which forms a major hurdle for both basic research and medical practice.

We are interested in addressing the problem of VUS by unifying population genetics and machine learning. Our research is motivated by the insight that evolution operates like a high-throughput mutagenesis experiment: deleterious mutations are quickly purged from populations due to natural selection, which in turn leaves detectable marks on human genomic sequences.
We have been developing multiple population genetics-based machine learning models to predict deleterious coding and noncoding variants in the human genome. Our methods have been widely used to prioritize genetic variants associated with human disease.

#### 2. Positive selection and lineage-specific selection in the human genome

A key question in biology is to understand what genetic changes make us human. To answer this question, we need to pinpoint genes and noncoding sequences under positive selection and/or lineage-specific selection during the course of human evolution.  Unfortunately, this is a challenging task because the signals of selection are often very weak at individual genes and regulatory elements.

We are developing novel statistical methods that may boost the statistical power to detect weak signals of selection. By combining evolutionary theory and statistical modeling, our new methods will elucidate new insights into genetic changes that make us apart from other primates.

#### 3. Functional and fitness effects of structural variation

A large portion of genetic diversity in human populations is attributable to structural variants, such as deletions, insertions, and inversion. 
Unlike single nucleotide variants that affect a single gene or noncoding element, a structural variant may span multiple loci.
Thus, it is challenging to infer the functional and fitness effects of structural variants.

We are developing novel computational methods to infer the effects of structural variants from large-scale population genomic data. By combining population genetic models and machine learning techniques, our new methods will shed new light on how structural variation contributes to human disease and evolution.

<!--
# While numerous statistical methods have been developed to identify 
#### 2. Genomic determinants of human adaptative evolution
#### Estimation of selection coefficients associated with human coding variants 
<p>
<img src="../images/slider7001400/SmartTipSide.jpg" alt="LASSIE" width="50%" height="50%" style="float:left;margin:0px 10px">

A central challenge in human genomics is to understand the cellular, evolutionary, and clinical significance
of genetic variants. We recently developed a unified population-genetic and machine-learning model,
called Linear Allele-Specific Selection InferencE (LASSIE), for estimating the fitness effects of all potential
single-nucleotide variants, based on polymorphism data and predictive genomic features. We applied
LASSIE to 51 high-coverage genome sequences annotated with 33 genomic features, and constructed a
map of allele-specific selection coefficients across all protein-coding sequences in the human genome. This
map is generally consistent with previous inferences of the bulk distribution of fitness effects, but reveals
pervasive weak negative selection against synonymous mutations. In addition, the estimated selection coefficients
are highly predictive of inherited pathogenic variants and cancer driver mutations, outperforming
state-of-the-art variant prioritization methods. By contrasting our estimated model with ultra-high coverage
ExAC exome-sequencing data, we identified 1,118 genes under unusually strong negative selection, which
tend to be exclusively expressed in the central nervous system or associated with autism spectrum disorder,
as well as 773 genes under unusually weak selection, which tend to be associated with metabolism. This
combination of classical population genetic theory with modern machine-learning and large-scale genomic
data is a powerful paradigm for the study of both human evolution and disease.
</p>

<ul>
  <li>Yi-Fei Huang and Adam Siepel. Estimation of allele-specific fitness effects across human protein-coding sequences and implications for disease. <em>Genome Research</em>. 2019;gr. 245522.118</li>
</ul>


#### Scalable prediction of deleterious noncoding mutations in the human genome

<p>
<img src="../images/slider7001400/LINSIGHT.png" alt="LASSIE" width="50%" height="50%" style="float:left;margin:0px 10px">
Many genetic variants that influence phenotypes of interest are located outside of protein-coding genes, yet existing methods for identifying such variants have poor predictive power. Recently, we developed a new computational method, called LINSIGHT, that substantially improves the prediction of noncoding nucleotide sites at which mutations are likely to have deleterious fitness consequences, and which, therefore, are likely to be phenotypically important. LINSIGHT combines a generalized linear model for functional genomic data with a probabilistic model of molecular evolution. The method is fast and highly scalable, enabling it to exploit the "big data" available in modern genomics. We show that LINSIGHT outperforms the best available methods in identifying human noncoding variants associated with inherited diseases. In addition, we apply LINSIGHT to an atlas of human enhancers and show that the fitness consequences at enhancers depend on cell type, tissue specificity, and constraints at associated promoters.
</p>

<ul>
  <li>
  Yi-Fei Huang, Brad Gulko, and Adam Siepel. Fast, scalable prediction of deleterious
  noncoding variants from functional and population genomic data. <em>Nature Genetics</em>.
  2017;49:618-624
  </li>
</ul>

#### Statistical phylogenetic models for inferring functional protein patches
<p>
<img src="../images/slider7001400/gp4rate.jpg" alt="LASSIE" width="50%" height="50%" style="float:left;margin:0px 10px">
A variety of statistical phylogenetic models have been developed to predict functionally important protein sites, e.g. ligand binding sites or protein-protein interaction interfaces, by comparing sequences from different species. However, most of the existing methods ignore the spatial clustering of functionally important sites in protein tertiary/primary structures, which significantly reduces their power to identify functionally important regions in proteins. We developed several new statistical phylogenetic models for inferring functionally important protein regions in which Gaussian processes or hidden Markov models are used as prior distributions to model the spatial correlation of evolutionary patterns in protein tertiary/primary structures. Both simulation studies and empirical data analyses suggest that these new models outperform classic phylogenetic models. Therefore, these new models may be useful tools for extracting functional insights from protein sequences and for guiding mutagenesis experiments. Furthermore, the new methodologies developed in these models may also be used in the development of new statistical models to answer other important questions in phylogenetics and molecular evolution.
</p>

<ul>
  <li>
  Yi-Fei Huang and G. Brian Golding. FuncPatch: A web server for the fast Bayesian
  inference of conserved functional patches in protein 3D structures. <em>Bioinformatics</em>.
  2015;31:523-531
  </li>

  <li>
  Yi-Fei Huang and G. Brian Golding. Phylogenetic Gaussian process model for
  the inference of functionally important regions in protein tertiary structures. <em>PLoS
  Computational Biology</em>. 2014;10:e1003429.
  </li>

  <li>
  Yi-Fei Huang and G. Brian Golding. Inferring sequence regions under functional
  divergence in duplicate genes. <em>Bioinformatics</em>. 2012;28:176-183.
  </li>
</ul>
-->
