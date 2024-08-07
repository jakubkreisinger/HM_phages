# HM_phages

This archive contains scripts related to gut phageome and bacterial analyses of wild and captive house mice.

## Content of https://github.com/jakubkreisinger/HM_phages/tree/Scripts folder:
<br />
<br />
<strong>01.phyloseq_phages.Rmd</strong> 
Scripts decribing preparation of phyloseq object based on SAMtools outputs.<br />
<strong>02.Stat_phages.Rmd</strong> Main statistical analyses for phage data, including alpha and beta diversity analyses, analyses of temporal stability and the effects of the trasplantation experiment on differences between donors and recipients (or controls) at the community level.<br /> 
<strong>03.Life.cycle_phages.Rmd</strong> Analyses for predicted life cycle.<br />
<strong>04.Sub_contig_anl.Rmd</strong> Analyses testing the effect of phage treatment on subcontig phage community divergence assessed using FST statistics.<br />
<strong>05.Stat_bacteriome.Rmd</strong> Main statistical analyses for bacterial data, including alpha and beta diversity analyses, analyses of temporal stability and the effects of the trasplantation experiment on differences between donors and recipients (or controls) at the community level. Most of the steps are almost the same as in 02.Stat_phages.Rmd. The Phyloseq database for these analyses was created following the steps described in https://github.com/jakubkreisinger/HM_soc_gen/blob/main/01.demultiplexing.sh, https://github.com/jakubkreisinger/HM_soc_gen/blob/main/02.QF_dada2.R and https://github.com/jakubkreisinger/HM_soc_gen/blob/main/03.build_phyloseq.Rmd.<br />  
<strong>06.Procrustes.Rmd</strong> Correlation between the composition of phage and bacterial communities tested with Procrustes analyses.<br />  
<strong>07.SPLS.Rmd</strong> Correlation between the composition of phage and bacterial communities tested with SPLS analyses.<br />
<br />
<br />
## Content of https://github.com/jakubkreisinger/HM_phages/tree/Data folder:
<br />
<br />
<strong>diamond_blastn_taxonomy_all</strong> Phage taxonomy<br />
<strong>Host_prediction_to_genus_m75_unique_clean.txt</strong> Bacterial host predictions<br />
<strong>phatyp_prediction.csv</strong> Life cycle predictions<br />
<strong>phatyp_prediction_KimBae.csv</strong> Life cycle predictions for data from KimBae <br />
<strong>PHYLOSEQ.prop.BP_100322.R</strong> Phage dataa<br />
<strong>PHYLOSEQ_merged.gm_NewMeta.Rv/strong> Bacterial data<br />
<strong>PHYLOSEQ.prop.BP.KimBae.R</strong> Phyloseq data for data from KimBae<br />
<strong>separate_reads_rijen21_k31_probWJ_trsh2_distance.txt</strong> probWJ distance matrix<br />
<strong>separate_scaffolds_rijen21_k31_Jexact_distance.txt</strong> Jexact distance matrix<br />

