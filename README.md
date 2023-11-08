# Identification of a Notch transcriptomic signature for breast cancer

## Background:  
Dysregulated Notch signalling contributes to breast cancer development and progression, but validated
tools to measure the level of Notch signalling in breast cancer subtypes and in response to systemic
therapy are largely lacking. A transcriptomic signature of Notch signalling would thus be warranted, and
in this report, we have established such a classifier.

## Methods:  
To generate the signature, we first identified Notch-regulated genes from six basal-like breast cancer cell
lines subjected to elevated and reduced Notch signalling by culturing on immobilized Notch ligand Jagged1
or blockade of Notch by -secretase inhibitors, respectively. From this cadre of Notch-regulated genes, we
developed candidate transcriptomic signatures that were trained on a breast cancer patient dataset (the
TCGA-BRCA cohort) and a broader breast cancer cell line cohort.

#Results:  
An optimal 20-gene transcriptomic signature was selected. We validated the signature on two
independent patient datasets (METABRIC and Oslo2) and it showed an improved coherence score and
tumour specificity compared with previously published signatures. Furthermore, the signature score was
particularly high for basal-like breast cancer, indicating an enhanced level of Notch signalling in this
subtype. The signature score was increased after neoadjuvant treatment in the PROMIX and BEAUTY
patient cohorts, and a lower signature score generally correlated with better clinical outcome.

## Conclusions:  
The 20-gene transcriptional signature has the potential to better stratify patients and to evaluate the
response of future Notch-based therapies for breast cancer.

## Keywords:  
Breast cancer, Notch signalling, transcriptomic signature, therapy, diagnostics

# Prepare Additional Files needed:

Store files in: **"../data/"**  

**Mouse-Human Homologues**  
From: http://www.informatics.jax.org/downloads/reports/HOM_MouseHumanSequence.rpt  

Store files in: **"../data/CCLE/"**  

**CCLE phenotype data**  
Phenotype data were downloaded from depmap-CCLE (21q1)  
From: https://depmap.org/portal/download/all/  
and stored in "data/CCLE/CCLE_sample_info_21Q1.csv"  

**CCLE mutation data**  
Mutations were downloaded from depmap-CCLE (21q1)  
https://depmap.org/portal/download/all/  
and stored in "data/CCLE/CCLE_mutations.csv_21Q1.csv"  

## Signatures from publications:

**Braune et al.**: https://www.sciencedirect.com/science/article/pii/S2213671116000850
File: Braune_2016_1-s2.0-S2213671116000850-mmc4.xls

**Castel et al.**: http://genesdev.cshlp.org/content/27/9/1059.full
File: Castel2013_Dll1_vs_DAPT_Table_S4.xlsx

**Dieguez-Hurtado et al.**: https://www.nature.com/articles/s41467-019-10643-w
File: Dieguez-Hurtado2019_RBPJ_targets_in_pericytes_41467_2019_10643_MOESM7_ESM.xlsx

**Pinell et al.**: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4654973/
File: Pinell2015_NOTCH1_ZMIZ1_NIHMS729606-supplement-4.xlsx

**Wang et al.**: https://www.pnas.org/content/108/36/14908
File: Wang2011_Notch1_target_genes.xls

## Get Known Canonical sequences from UCSC:  
File: http://genome.ucsc.edu/cgi-bin/hgTables?hgsid=1412888849_rKl43K1tPzDSPfIqfyeoGkuta8Vr&clade=mammal&org=Human&db=hg38&hgta_group=genes&hgta_track=knownGene&hgta_table=knownCanonical&hgta_regionType=genome&position=chrX%3A15%2C560%2C138-15%2C602%2C945&hgta_outputType=primaryTable&hgta_outFileName=

## Get Estimate Scores:
File: https://bioinformatics.mdanderson.org/estimate/tables/breast_cancer_RNAseqV2.txt
