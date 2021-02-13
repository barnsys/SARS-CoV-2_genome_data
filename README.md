# SARS-CoV-2_genome_data
252 complete genomes of the SARS-CoV-2 virus, the first wave (December 2019 - July 2020) of the global COVID-19 pandemic from 21 countries of the world

BEAST_Exp_RC_dated_tree.tree - dated phylogenetic tree, reconstructed using the BEAST 2.6.2 software. The tree was dated by the time of isolation of the virus strains. Coaliscent model - exponential population growth, relaxed molecular clock.

SARS-CoV-2_genome_coding_part.fas - SARS-CoV-2 dataset containing the coding portion of 252 complete viral genomes from 21 countries. The names of the sequences indicate the country of origin of the strain, the time of isolation of the strain, the number from the GISAID database (https://gisaid.org) or Genbank (https://www.ncbi.nlm.nih.gov/).

SARS-CoV-2_genome_coding_part_1+2_codon_positions.fas - SARS-CoV-2 dataset containing 1 + 2 codon positions for the coding portion of 252 complete virus genomes from 21 countries.

SARS-CoV-2_genome_coding_part_3_codon_positions.fas - SARS-CoV-2 dataset containing the third codon position for the coding portion of 252 complete viral genomes from 21 countries.

SARS-CoV-2_xml_for_BEAST_2.6.2.zip- BEAST 2.6.2 xml files for reconstructions of the evolutionary histories of SARS-CoV-2: Const - reconstruction with a coalescent model of constant population size, Exp - reconstruction with a coalescent model of exponential increase in population size, SC - reconstruction with a strict clock, RC - reconstruction with relaxed clock, no_tips - reconstruction without dating the tree by the time of strain isolation. For all reconstructions, division of the dataset into 1 + 2 and 3 codon positions was applied; for each part of the dataset, the HKY + I + G4 nucleotide evolution model was used. To achieve ESS statistics values of more than 200 were used 600000000 generations of Markov chains. During the reconstruction were saved the results of each 30000 generation.

SARS-CoV-2_xml_for_BEAST_2.6.2_Path_sampling.zip - BEAST 2.6.2 xml files for testing and selecting the best evolutionary model of SARS-CoV-2 using path sampling analysis: Const - reconstruction with a coalescent model of constant population size, Exp - reconstruction with a coalescent model of exponential increase in population size, SC - reconstruction with a strict clock, RC - reconstruction with relaxed clock, no_tips - reconstruction without dating the tree by the time of strain isolation. For all reconstructions, division of the dataset into 1 + 2 and 3 codon positions was applied; for each part of the dataset, the HKY + I + G4 nucleotide evolution model was used. Path sampling parametrs value: chainLength="2000000", preBurnin="30000000", nrOfSteps='300'

Path_sampling_marginal_likelihood.xlsx - the values of the marginal likelihoods calculated using the path sampling analysis when testing the evolutionary models of the SARS-CoV-2 virus genomes data. The table contains the results of three independent (different random starting seed values) runs of path sampling analysis for all tested phylogenetic reconstructions model.
