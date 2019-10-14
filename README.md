# Bacteria-Biotope-at-BioNLP-OST-2019
The Bacteria Biotope (BB) Task is part of the BioNLP Open Shared Tasks (BioNLP-OST: http://2019.bionlp-ost.org) 

Biology and bioinformatics projects produce huge amounts of heterogeneous information about the microbial strains that have been experimentally identified in a given environment (habitat), and theirs properties (phenotype). These projects include applied microbiology domain (food safety), health sciences and waste processing. Knowledge about microbial diversity is critical for studying in depth the microbiome, the interaction mechanisms of bacteria with their environment from genetic, phylogenetic and ecology perspectives.

A large part of the information is expressed in free text in large sets of scientific papers, web pages or databases. Thus, automatic systems are needed to extract the relevant information. The BB task aims to encourage the development of such systems.


# Dataset 
The representation scheme of the BB task contains four entity types:

# Microorganism
# Habitat
# Geographical
# Phenotype
and two relation types:

Lives_in relations which link a Microorganism entity to a location (either a Habitat or a Geographical entity)
Exhibits relations which link Microorganism entity to a Phenotype entity.
In addition, Microorganisms are normalized to taxa from the NCBI taxonomy, and Habitat and Phenotype entities normalized to concepts from the OntoBiotope ontology.



![image](https://user-images.githubusercontent.com/41851165/66725233-68d20e80-ee4d-11e9-92b2-8c4c3a701756.png)
