Following is the explanation of scripts, files and folders used in for the phylogenetic and ecology analysis of Labyrinthulomycetes in my master thesis. 

### output
These files are outputs from the R-scripts
- eco_tree_data.csv: Sum of sequences present or absent in the ecosystem types
- reassigned_all_seqs_edit.csv: Manual edits of the reassigned_all_seqs_edit.csv
- reassigned_all_seqs: New taxonomy of all reference sequences based on phylogeny
- seqs_cluster_in.dfasta: fasta file with all sequences input into VSEARCH
- new_and_old_taxonomy.csv: Sequences with accession nr., old and new taxonomy used to reassign sequences in PR2
- 500_seq.dfasta: sequences between 500-1000 bp input into MAFFT to create alignment
- 1000_seq.dfasta: sequences between 1000-1600 bp input into MAFFT to create alignment
- 1600_seq.dfasta: sequences over 1600 bp intput into MAFFT to create alignment
  
metabarcode folder
All of these .pdf files were imported into Affinity Designer 2 and edited.
- laby_neurope.pdf: output of distribution map of North Europe
- laby_scatter.pdf: output of scatterpie maps
- laby_tree.pdf: output of tree maps
- laby_worldmap.pdf: output

### raw_data
These files were input into R-scripts.
- metadata_categorized.csv: Ecosystem and habitat data for sequences
- new_taxonomy.csv: New taxonomy for sequences in phylogenetic tree (Check if needed)
- seqs_cluster_99.tsv: Output data from clustering at 99% with VSEARCH
- sequence_data.csv: All reference sequences and metadata downloaded from PR2 and GenBank
- tree_taxonomy.csv: New taxonomy of Labyrinthulomycetes based on phylogeny of maximum likelihood tree imported from TreeViewer
- type_seqs.csv: List of type sequences used in phylogenetic analysis
  
metabarcode folder
The 'metapr2_ASVs_selected_abundance_Eukaryota_2025-03-13.tsv' used in the distribution.Rmd can be downloaded from the metaPR2 website
- asv_updated.xslx: Reassigned metabarcodes from metaPR2
- samples.xslx: Samples metadata with file_codes corresponding to asv_codes


### R-scripts
Scrips of phylogenetic and ecology analysis

- distribution.Rmd: Script for global distribution map, tree map and scatterpie map.
- metadata_ecosystem.Rmd: Script for phylogeneitc tree with clade ecosystem absence/presence data
- phylogenetic_analysis.Rmd: Script for phylogenetic analysis pipeline
