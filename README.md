# TibetanAntelope_Microbiome_Hormone

# How to cite:
Shi, Y., Miao, ZY., Su, JP. et al. Shift of Maternal Gut Microbiota of Tibetan Antelope (*Pantholops hodgsonii*) During the Periparturition Period. Curr Microbiol (2021). https://doi.org/10.1007/s00284-020-02339-y
 
# R scripts (.rmd)
**filtering_batchEffect.rmd**: filter raw ASV count table and correct batch effect of different sequencing runs;

**Fig1_pRDA.rmd**: hierarchical clustering analysis, PCoA, alpha diversity measures and pRDA;

**maaslin2.rmd**: MaAsLin2 analysis to identify significant microbial taxa;

**Fig2_Fig3.rmd**: data visualization for Fig 2 and 3 in the manuscript. 


# Data
**ASV_counts.tsv**: ASV count table after DADA2 pipeline;

**ASV_taxonomy.tsv**: ASV taxonomy classification after DADA2 pipeline;

**ASV.fasta**: fasta file for ASV sequence reads;

**meta_filter.csv**: meta sample information;

**Other files**: intermediate files generated from various analyses in the manuscript. 


# Figures
**Fig.1** Shift of maternal gut microbiota in female Tibetan antelope in the transition from late pregnancy to the postpartum period. Hierarchical clustering analysis (A) and principal coordinates analysis (PCoA) (B) for gut microbial communities at the genus level as a function of the reproductive state (N=95). Both analyses were based on a Euclidean distance matrix after variance stabilizing transformation. C) Changes in alpha diversity metrics of the maternal gut microbiota at the ASV level in different reproductive states. Statistical significance was assessed by t-tests. Note: ns: not significant; **: *p* < 0.01.

**Fig.2** Microbial genera identified with significantly differential abundance as a function of reproductive states of Tibetan antelope using general linear mixed model implemented MaAsLin2 R package. *p* values were adjusted with the Benjamini-Hochberg method to control for false discovery rate (FDR). Coefficient indicates the contrast between two reproductive states with late pregnancy as reference.

**Fig.3** Changes in fecal hormone metabolite concentrations (GC and T3) between two reproductive states of Tibetan antelope (A) and microbial genera with significant association with changes in GC (B) and T3 (C) using general linear mixed model implemented MaAsLin2 R package. *p* values were adjusted with the Benjamini-Hochberg method to control for false discovery rate (FDR). Coefficient indicates the degree of correlation.
