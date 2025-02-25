# `metabaR` external data
This folder is a repository of external resources and toy data examples for the `R` package `metabaR`:

## SILVA Taxonomy
- release 138.1 : tax_slv_ssu_138.1.txt

## Raw data tables for the `soil_euk` dataset

### Basic table inputs
- litiere_euk_reads.txt:    
        A PCR (rows) by OTU (columns) table: amount of reads of each OTU in each PCR.    
- litiere_euk_motus.txt:    
        A OTU (rows) by OTU information (columns) table: e.g. taxonomy, sequence, etc.    
- litiere_euk_pcrs.txt:    
        A PCR (rows) by PCR information (columns) table: e.g. PCR plate coordinates, primers used, etc.    
- litiere_euk_samples.txt:    
        A sample (rows) by sample information (columns) table: e.g. geographic coordinates.      

### Obitools inputs
- litiere_euk_cl97_agg_filt_tax.tab:    
        A OTU/seq (rows) by OTU informations (columns; including # reads in a given sample, taxonomy, sequence, etc.). Typically an output from obitools (obitab).     
- ngsfilter_GWM-768.new_2.txt:    
        A PCR (rows) by PCR information (columns; any PCR related metadata). Typically a ngsfilter txt file.    
- Litiere_sample_list_2.txt:    
        A sample (rows) by sample information (columns; any metadata for samples)    


### BIOM input
- litiere_euk_reads_hdf5.biom:    
        Soil_euk dataset in the BIOM format.

### SILVAngs outputs
- lit_euk---ssu---otus.csv:    
    A file containing taxonomic assignments for each sequence submitted to SILVAngs    
- lit_euk---ssu---sequence_cluster_map---litiere_euk_cl97_agg_filt.clstr:     
    A file containing the mapping of each sequence submitted to SILVAngs. Even if no clustering is supposed to be done (i.e. sequence similarity set at 100% in the pipeline), sequences that are strict suffix/prefix of another can still be clustered together with the clustering algorithm used by SILVAngs (CD-HIT).
    

## The `karst_euk` dataset
- karst_euk.rds:    
    A metabarlist corresponding to the `karst_euk` dataset. To be loaded using the readRDS function.
 
## The `h20_plants` dataset
- h20_plants.rds:    
    A metabarlist corresponding to the `h20_plants` dataset. To be loaded using the readRDS function.

