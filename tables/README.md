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
* all_GCF_curated_metadata.tsv: Metadata for each BGC not encoding an unknown product. Includes important information including which predicted product classes and which GCF they belong to. 
* final_rep_clusters.tsv: Metadata for representative clusters for each unique Gene Cluster Family (GCF)
* bgc_novel_bact_corr_edge_bins.tsv: Correlation subset values used for bacteriocin network (with transporter)
* bgc_bact_no_trans_corr_edge_bins.tsv: Correlation subset values used for bacteriocin network (without transporter)

**Anti-microbial/anti-bacterial peptide prediction**:
* ampgram_benchmark_CHOSEN.fasta: Multi-fasta file containing 78 validated anti-microbial/anti-bacterial peptides (AMP/ABPs) and 78 scrambled negative control sequences for benchmarking
* ampgram_benchmark_CHOSEN.fastaheaders: Tab separated file with the names of each peptide in the benchmarking dataset
* AMPDiscover_benchmark_predictions.csv: AMPDiscover prediction results for the benchmarking peptide sequences.
* ampgram_benchmark_df.tsv: AmpGram prediction results for the benchmarking peptide sequences
* ampscannerv2_benchmark_Prediction_Summary.csv: AMPScanner v2 prediction results for the benchmarking peptide sequences
* all_AS_novel_peptides.sizes: AA lengths of every short ORF > 10 AA and < 200 AA in novel BGCs encoding peptides with transporters, after Antismash predictions.
* AS_peptides_with_transporter_gene_funcs_combined.tsv: Antismash annotated gene functions for every short ORF hort ORF > 10 AA and < 200 AA in novel BGCs encoding peptides with transporters
* AS_novel_peptide_transporter_AMPDiscover_predictions.csv: AMPDiscover prediction results for candidate peptide sequences in BGCs with transporters this manuscript.
* all_AS_novel_peptides_ampgram.tsv: AmpGram prediction results for candidate peptide sequences in BGCs with transporters in this manuscript.
* AS_novel_peptides_Prediction_Summary.csv: AMPScanner v2 prediction results for candidate peptide sequences in BGCs with transporters in this manuscript.
