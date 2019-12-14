# MetabaR-F external data
This folder is a repository of external toy data examples for the R package MetabaR-F:


## Raw data tables

## SILVAngs outputs
- lit_euk---ssu---otus.csv:    
    A file containing taxonomic assignments for each sequence submitted to SILVAngs    
- lit_euk---ssu---sequence_cluster_map---litiere_euk_cl97_agg_filt.clstr:     
    A file containing the mapping of each sequence submitted to SILVAngs. Even if no clustering is supposed to be done (i.e. sequence similarity set at 100% in the pipeline), sequences that are strict suffix/prefix of another can still be clustered together with the clustering algorithm used by SILVAngs (CD-HIT).
