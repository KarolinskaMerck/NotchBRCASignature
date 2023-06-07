# Identification of a Notch transcriptomic signature for breast cancer

**Introduction**

We want to identify robust NOTCH signatures for the activation and inactivation of the NOTCH pathway. Therefore, the group of Urban Lendahl at the Karolinska Institutet, Stockholm, Schweden and the group of Dirk Wienke at the Translational Innovation Platform Oncology and Immuno-Oncology at Merck KGaA, Darmstadt, Germany teamed up.  

**Research Questions**

*Treatments:*  

We treated six basal-like breast cancer cell lines either with the gamma-secretase inhibitor DAPT or cultivated the cells on immobilized NOTCH ligand Jagged1. Subsequently, the cells were harvested after 8h or 72h of incubation time and their transcriptome analyzed by RNASeq.  

Each condition was treated for both 8h and for 72h:  

* normal (no treatment): "FC"
* NOTCH ON (cultured on immobilised Jagged1 ligand): "Jagged1"
* NOTCH OFF (blocked with GSI): "DAPT"

Of special interest is the comparison: Jagged1 (NOTCH high) vs. DAPT (NOTCH low)  

**Specific goals:**  

Identify a Notch signature:  

* that defines active and hyperactive notch
* that may identify responsive cell lines / patients

# Prepare Downloads:

Store files in: "../data/"

**Mouse-Human Homologues**
From: http://www.informatics.jax.org/downloads/reports/HOM_MouseHumanSequence.rpt

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
http://genome.ucsc.edu/cgi-bin/hgTables?hgsid=1412888849_rKl43K1tPzDSPfIqfyeoGkuta8Vr&clade=mammal&org=Human&db=hg38&hgta_group=genes&hgta_track=knownGene&hgta_table=knownCanonical&hgta_regionType=genome&position=chrX%3A15%2C560%2C138-15%2C602%2C945&hgta_outputType=primaryTable&hgta_outFileName=

## Get Estimate Scores:
File: https://bioinformatics.mdanderson.org/estimate/tables/breast_cancer_RNAseqV2.txt
