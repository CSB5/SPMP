Raw inputs from jupyter lab scripts. Some inputs were preprocessed to be easily exported here and may not directly reflect software output.

### Listing and files description

**Kraken/Bracken**:
* bracken_self_combine_result.tsv.gz: Concatenated bracken report of Illumina reads against a single database composed of SPMP SLCs.
* bracken_western_combine_result.tsv.gz: Bracken result of western reads against SPMP dataset
* cre_classified.tsv: Percentage of reads classified by kraken for each CRE sample against various database
* kraken_self_single_results.tsv.gz: Concatenated kraken reports of Illumina reads against short-read and hybrid assemblies. 
* kraken_standard_all.parquet.tsv.gz: Concatenated kraken reports of Illumina reads against the Kraken Standard database (saved in parquet format).

**Reads data**:
* illumina_reads_statistics.tsv.gz: Illumina reads statistics data
* nanopore_reads_statistics.tsv.gz: ONT reads statistics data
* illumina_nanopore_reads_correlation.tsv.gz: Illumina and ONT reads mapping against the kraken standard database, used for reads correlation

**GTDB**:
* gtdb_mash_distances.tsv.gz: Mash distance between Hybrid assemblies and GTDB genomes
* gtdb_metadata.tsv.gz: GTDB genomes metadata

**Mags info**:
* mags_info_hybrid.tsv: Hybrid MAGs assembly statistics and annotations. Only MAGs of medium, near-complete and high quality were conserved.
* mags_info_shortread.tsv: Short-read MAGs assembly statistics and annotations. Only MAGs of medium, near-complete and high quality were conserved.
* mags_info_hic.tsv: HiC MAGs assembly statistics

**Strains clustering**:
* strains_clustering_results.tsv.gz: All MASH strains clustering results
* 280.fastani.tsv.gz: Pairwise FastANI distances of SLC280 strains

**Other metadata**:
* subjects_metadata.tsv: SPMP subject metadata
* uhgg-genomes-all_metadata.tsv.gz: UHGG all genomes metadata

**BGC**:
* bgc_novel_bact_corr_edge_bins.tsv: Correlation subset values used for bacteriocin network (with transporter)
* bgc_bact_no_trans_corr_edge_bins.tsv: Correlation subset values used for bacteriocin network (without transporter)