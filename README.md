# Codes_TranscriptomicAnalysis
This repository contains thefiles and scripts used for the analysis of embryogenesis time-course RNA-seq data, including tasks from expression quantification to summarisation and generatio of results figures. R packges used include *ggplot2*, 
*dplyr*, *tidyverse*, *DESeq2* and *RSubreads*.

In **3_1_Transcriptomic data analysis.nb.html** are the files and scripts to:
- Run gene expression quantification quantification at the gene, exon and intron level using *FeaturesCounts* (https://www.rdocumentation.org/packages/Rsubread/versions/1.22.2/topics/featureCounts)
- Run PCA analysis
- Run TPM normalisation across expression count matrix
- Test for epxression correlations between stages and library types
- Summarise stage-specific epxression
- To interpretate and generate figures showing main results

In **3_3 Maternal mRNAS - PolyA tail state analysis.nb.html** are the files and scripts to:
- Identify set of matenrally provided mRNAs using expression thresholds
- Infere polyadenyaltion state by testing  PolyA and Total expression fold change dynamics
- Cluster polyadenyation rate scores across developmental stage
- Test for epxression correlations between libraries for each identified cluster

In **3_4 Expression analysis during MZT.nb.html** are the files and scripts to:
- Analyse trancriptome dynamics during embryogenesis by integrating PolyA and Total expression data
- Cluster gene expression  across several developmenatl time-points

In **3_5 Zygotic genes - First expression.nb.html**
- This notebook describes the identification of zygotic transcripts detected using the *First Expression* method. Briefly, zygotic genes were defined as those:
  * Not maternally provided
  * Significantly upregulated in each stage, usign as 0-9 hrs sample as reference timepoint

Please email *alexjapes@gmail.com* if there is any problem, thanks! (Manuel)

[This](https://htmlpreview.github.io/) is a tool to view the html files. 
