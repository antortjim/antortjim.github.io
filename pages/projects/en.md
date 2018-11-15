---
layout: page
title: Portfolio
permalink: /portfolio/
ref: portfolio
lang: en
weight: 2
---
<style>
  .span4 {
    list-style-position: inside;
    margin-left: 10em;
  }
</style>

### Original work ###

These projects comprise either extended analysis of published data, or  completely independent work.

**2018**

* [Master Thesis titled "Development of label-free quantification methods in proteomics".](http://people.binf.ku.dk/rnq313/master_thesis/thesis.pdf) (I) Compilation of an open-source free (cost and license) pipeline for the analysis and quantification of DDA proteomics datasets in a GNU/Linux environment. Makes extensive use of the tools developed at the Compomics group at UGhent (Belgium). (II) Writing of a statistical model for the probabilistic quantification of protein ratios between samples using the PyMC3 framework, focusing on the assessment of uncertainty. Carried out at Advanced analytics in Novozymes.


<div class="container">
    <div class="row">

      <div class="span4">
          <p><strong>What I learned:</strong></p>
          <ul>
          <li>Probabilistic programming in PyMC3</li>
          <li>DDA Proteomics analysis</li>
          <li>Pipelining in bash</li>
          </ul>
      </div><!--/span-->
</div>
</div>


* [Bioinformatics project titled "Classification and prognosis of Rheumatoid Arthritis patients. A case study".](http://people.binf.ku.dk/rnq313/binfProject2/report.pdf)
Data cleaning and engineering (Scikit-learn), and development of a vanilla neural neutwork (TensorFlow) for classification of patients into 2 remission groups (progressor or not). An exploration of the architecture space revealed the dimensions of the best NN model and achieved a 0.78 AUC in the test set. Carried out at Nordic Bioscience.

<div class="container">
    <div class="row">

      <div class="span4">
          <p><strong>What I learned:</strong></p>
          <ul>
          <li>Data preprocessing in Python</li>
          <li>Vanilla NNs with TensorFlow</li>
          <li>Classifier evaluation with scikit-learn</li>
          </ul>
      </div><!--/span-->
</div>
</div>



**2017**

* [Bioinformatics project titled "An interactive visualization tool for clinical hypothesis generation".](http://people.binf.ku.dk/rnq313/binfProject1/report.pdf)
Development of a Shiny App for straightforward visualizations of health data. Powered by ggplot2, the app performs an exploratory analysis of the PERF database using boxplots, scatterplots, and a correlogram. The data can be filtered by different categories to interactively modify the graphics and download subsets of the databse. Carried out at Nordic Bioscience.


* ["Bioinformatics project titled "Finding patterns in fitness, nutrition and lifestyle-associated genomics data".](http://people.binf.ku.dk/rnq313/binfProject4/report.pdf)
Analysis of SNP array datasets from a client database together with the 1000 genomes panel, drawing conclusions on the predictive power of genomic variants. I worked with PLINK, Bedtools, ADMIXTURE, SQL and ggplot2.





* [Assessing admixture proportions.](http://people.binf.ku.dk/rnq313/ATB/part2.html) Playing on top of the NGSadmix program output, a likelihood model is built to assess the significance of the found admixture contributions.

* [EM Algorithm and NGS data.](http://people.binf.ku.dk/rnq313/ATB/part1.html) An implementation of the Expectation Maximization algorithm applied to the estimation of base composition in haploid genomes.


* [Population Genetics final exam](http://people.binf.ku.dk/rnq313/report.pdf). Working with SNP data from zebra species in the PLINK suite. The main topics focused on the genetic support for the distinction between plains subspecies and the position of the extinct _E. quagga quagga_ in the phylogenetic tree of zebras.

* [Statistics for e-Science work](https://antortjim.github.io/posts/2016/12/21/ioslides-and-Shiny-apps-showcase.html), a ioslides presentation and Shiny apps developed as part of the weekly exercises in this subject at KU.

* [Structural Bioinformatics final exam](http://people.binf.ku.dk/rnq313/rmsd_nmers/protein.pdf). Students were asked to implement a Python pipeline to compute RMSD distributions on 5-mer peptides and interpret the results. Code  available at [Github](https://github.com/antortjim/structural_bioinformatics).


**2016**

* [Bioinformatics and Genomic Analysis final exam](http://people.binf.ku.dk/rnq313/EXAM/examen.pdf) consisting of 2 parts:
-Extended ChIP-seq analysis for prediction of PIF1 and PIF4 interaction in *A. thaliana*.
 -RNA-seq *de novo* analysis of early and late embrionary states in *X. tropicalis* using edgeR.

* [Bachelor Thesis](http://people.binf.ku.dk/rnq313/TFG/tfg.pdf), entitled "Caracterización de la proteína All1873" (in Spanish).


### Replicates of previously published scientific works ###

The projects below are just replicates of the published computational analysis carried out by other scientists. Thus, despite there might be minor differences, the bulk of the creation is *not* my own original work. Reference to the scientific article projects are based on may be found in the *references* section.

{% include portfolio.html %}

