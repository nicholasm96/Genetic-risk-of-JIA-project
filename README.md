# Genetic-risk-of-JIA-project
JIA is a childhood onset autoimmune disease that affect millions of people worldwide
many GWAS studies have found SNPs/Single Nuceotide Polymorphism in the human genome that are associated with the development of JIA.
In this project we want to understand the tissue specific changes caused by these SNPs
We will use CoDeS3D, a python script that combine Hi-C chromatin contact information and eQTL data
Basically this software (CoDeS3D) will query multiple Hi-C database to see if the input JIA associated SNPs makes physical contact with genes.
For those SNPs that make physical contact with genes, CoDeS3D will query eQTL information from GTEx (genotype tissue expression) to see if the SNPs cause change in the gene expression level of the contacted gene.\
If the SNP cause changes in the expression level of the gene it contacts, the SNP is called an eQTL and the gene is called an eGene (eQTL-eGene pair)
This eQTL-eGene pair is tissue specific since the GTEx data is also tissue specific.
