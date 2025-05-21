Script and data for: master thesis

## output
- eco_tree_data.csv: Sum of sequences present or absent in the ecosystem types
- reassigned_all_seqs_edit.csv: Manual edits of the reassigned_all_seqs_edit.csv
- reassigned_all_seqs: New taxonomy of all reference sequences based on phylogeny
- seqs_cluster_in.dfasta: fasta file with all sequences input into VSEARCH
- new_and_old_taxonomy.csv: Sequences with accession nr., old and new taxonomy used to reassign sequences in PR2
- 500_seq.dfasta: sequences between 500-1000 bp input into MAFFT to create alignment
- 1000_seq.dfasta: sequences between 1000-1600 bp input into MAFFT to create alignment
- 1600_seq.dfasta: sequences over 1600 bp intput into MAFFT to create alignment

## raw_data
- metadata_categorized.csv: Ecosystem and habitat data for sequences
- new_taxonomy.csv: New taxonomy for sequences in phylogenetic tree (Check if needed)
- seqs_cluster_99.tsv: Output data from clustering at 99% with VSEARCH
- sequence_data.csv: All reference sequences and metadata downloaded from PR2 and GenBank
- tree_taxonomy.csv: New taxonomy of Labyrinthulomycetes based on phylogeny of maximum likelihood tree imported from TreeViewer
- type_seqs.csv: List of type sequences used in phylogenetic analysis
  
### Metabarcode folder
The 'metapr2_ASVs_selected_abundance_Eukaryota_2025-03-13.tsv' used in the distribution.Rmd can be downloaded from the metaPR2 website
- asv_updated.xslx: Reassigned metabarcodes from metaPR2
- samples.xslx: Samples metadata with file_codes corresponding to asv_codes



Rmd files: 
- distribution.Rmd: Script for global distribution map, tree map and scatterpie map.
- metadata_ecosystem.Rmd: Script for phylogeneitc tree with clade ecosystem absence/presence data
- phylogenetic_analysis.Rmd: Script for phylogenetic analysis pipeline
