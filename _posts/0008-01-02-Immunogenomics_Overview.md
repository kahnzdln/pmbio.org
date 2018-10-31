---
feature_text: |
  ## Precision Medicine
title: Intro to Immunogenomics
categories:
    - Module-08-Immune
feature_image: "assets/genvis-dna-bg_optimized_v1a.png"
date: 0008-01-01
---

### Introduction to Immunogenomics
Nonsynonymous coding mutations alter the amino acid sequences of endogenous proteins. Proteins are naturally processed by the immunoproteasome, and the lysed peptides are loaded into the antigen presentation complexes on the surface of the cell. Sometimes, mutant peptides due to nonsynonmyous mutations have increased affinity to the antigen presentation complex, effectively eliciting a tumor-specific adaptive immune and T cell response. These peptides are called *neoantigens* and can be inferred for a patient's tumor by their genomic and somatic profiles. The interaction between neoantigens and tumor-specific T cells has led to the discovery of personalized therapeutics (e.g. personalized cancer vaccines) and mechanisms of immunotherapeutic response.

{% include figure.html image="/assets/module_8/Fixed_Neoantigen filtering strategy.png.png" position="right" width="600" %}

Following the identification of somatic mutations, the steps associated with identifying neoantigens include:
1. Determine the normal HLA haplotypes
2. Perform peptide affinity predictions
3. Filter high-binding neoantigens based upon their tumor-specific expression

#### HLA haplotyping
The human leukocyte antigen (HLA) genes encode the major histocompatibility complex (MHC) molecules in humans. The MHC gene complex in humans is contained in a 3Mbp region on chromosome 6p21. While there are over 40 genes within this gene complex, there are nine HLA genes that are the most studied and well characterized. These genes can be very diverse across individuals, and there have been hundreds to thousands of haplotypes identified for each allele, encoding thousands of different HLA proteins. From an immunogenomics perspective, this is important because each person will present different peptides to the immune system, since different HLA proteins bind peptides and neoantigens differently.

Antigen presentation complexes are distinguished as either Class I or II. Class I complexes comprise a Class I-specific MHC molecule (encoded by *HLA-A, -B,* or *-C*) and beta-2-microglobulin (*B2M*), and are recognized by CD4+ T cells. Class II complexes include **two** MHC molecules (encoded by *HLA-DPA1, DPB1, DQA1, DQB1, DRA,* and *DRB1*), and are recognized by CD8+ T cells. Since there are nine canonical HLA genes, and each individual can have two different alleles for each gene (one each from paternal and maternal chromosomes), a person can have up two six different types of MHC-1 and 6-8 functioning MHC-II alleles.

HLA haplotyping is performed algorithmically by aligning and assembling normal DNA sequencing data to chromosome 6. There are many HLA typing tools available; however, we will be using xHLA in this workshop. One limitation of many HLA typing tools is the ability to predict both Class I and II haplotypes, since Class II HLA typing is not as well established. xHLA performs both Class I and II HLA haplotyping, allowing further characterization of both the Class I and II neoantigen landscape.

#### Predicting peptide affinity

#### Filtering neoantigens

