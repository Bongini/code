Script and data for: master thesis

## raw_data
- metadata_categorized.csv: Ecosystem and habitat data for sequences
- new_taxonomy.csv: New taxonomy for sequences in phylogenetic tree used for reassigning in PR2 (Check if needed)
- seqs_cluster_99.tsv: oOutput data from clustering at 99% with VSEARCH
- sequence_data.csv: All sequences and metadata downloaded from PR2 and GenBank
- tree_taxonomy.csv: New taxonomy of Labyrinthulomycetes based on phylogeny of maximum likelihood tree
- type_seqs.csv: List of type sequences used in phylogenetic analysis
  
### Metabarcode folder
The 'metapr2_ASVs_selected_abundance_Eukaryota_2025-03-13.tsv' used in the distribution.Rmd can be downloaded from the metaPR2 website
- asv_updated.xslx: Reassigned metabarcodes from metaPR2
- samples.xslx: Samples metadata with file_codes corresponding to asv_codes

## output
- eco_tree_data.csv: 

Rmd files: 
- distribution.Rmd: Script for global distribution map, tree map and scatterpie map.
- metadata_ecosystem.Rmd: Script for phylogeneitc tree with clade ecosystem absence/presence data
- phylogenetic_analysis.Rmd: Script for phylogenetic analysis pipeline
