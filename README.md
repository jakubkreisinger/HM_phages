# HM_phages

This archive contains scripts related to gut phageome and bacterial analyses of wild and captive house mice.

## Content of https://github.com/jakubkreisinger/HM_phages/tree/Scripts folder:
<br />
<br />
__01.phyloseq_phages.Rmd__ 
Scripts decribing preparation of phyloseq object based on SAMtools outputs.<br />
**02.Stat_phages.Rmd** Main statistical analyses for phage data, including alpha and beta diversity analyses, analyses of temporal stability and the effects of the trasplantation experiment on differences between donors and recipients (or controls) at the community level.<br /> 
**03.Life.cycle_phages.Rmd** Analyses for predicted life cycle.<br />
**04.Sub_contig_anl.Rmd** Analyses testing the effect of phage treatment on subcontig phage community divergence assessed using FST statistics.<br />
**05.Stat_bacteriome.Rmd** Main statistical analyses for bacterial data, including alpha and beta diversity analyses, analyses of temporal stability and the effects of the trasplantation experiment on differences between donors and recipients (or controls) at the community level. Most of the steps are almost the same as in 02.Stat_phages.Rmd. The Phyloseq database for these analyses was created following the steps described in https://github.com/jakubkreisinger/HM_soc_gen/blob/main/01.demultiplexing.sh, https://github.com/jakubkreisinger/HM_soc_gen/blob/main/02.QF_dada2.R and https://github.com/jakubkreisinger/HM_soc_gen/blob/main/03.build_phyloseq.Rmd.<br />  
**06.Procrustes.Rmd** Correlation between the composition of phage and bacterial communities tested with Procrustes analyses.<br />  
**07.SPLS.Rmd** Correlation between the composition of phage and bacterial communities tested with SPLS analyses.<br />
<br />
<br />

