# The Phylogenetic Position of Latimeria: Investigating the "Living Fossil" Fish's Relation to Common Fish and Tetrapods

## Abstract

Latimeria menadoensis, known as the coelacanth or "living fossil," represents a unique lineage of fish that has persisted for over 360 million years. This study aims to elucidate the phylogenetic position of Latimeria within the tree of life, investigating whether it is more closely related to common fish or to tetrapods (amphibians, reptiles, and mammals). The RAG2 (Recombination Activating Gene 2) gene was selected as the primary molecular marker for this analysis due to its conserved nature and significant role in the immune response across vertebrates. A phylogenetic tree was constructed using sequence data from Latimeria and twenty seven additional species, with a focus on analyzing evolutionary relationships through different methodologies, including distance-based and likelihood methods. The results will be interpreted in the context of anatomical, geographical, and ecological characteristics, providing insights into the evolutionary transitions from aquatic to terrestrial life.

## Introduction

Latimeria menadoensis, a member of the class Sarcopterygii, has fascinated scientists and researchers since its rediscovery in 1938 off the coast of South Africa. Often referred to as a "living fossil," this species offers a unique opportunity to study the evolutionary processes that have shaped vertebrate history. Understanding its phylogenetic relationships is essential for elucidating the evolutionary transitions that have occurred in vertebrates, particularly the shift from aquatic to terrestrial environments.

## Objectives
To determine the phylogenetic position of Latimeria menadoensis in relation to common fish and tetrapods.
To assess whether Latimeria is more closely related to common fish or to tetrapods using the RAG2 gene as a molecular marker.
To provide a comprehensive analysis of the findings, incorporating additional data on geographical distribution, lifestyle, and anatomical features.

## Materials and Methods

### Molecular Marker Selection
The RAG2 gene was chosen for this study due to its phylogenetic significance across vertebrate lineages. Its presence and conservation across a wide range of species make it an ideal candidate for analyzing evolutionary relationships.

### Sample Selection
A total of 28 samples were selected from GenBank for this study, including 1 Latimeria menadoensis organism, 12 fish, and 5 species each from mammals, reptiles, and amphibians. This diverse selection ensures a comprehensive analysis of phylogenetic relationships across a broad range of vertebrate lineages.

### Data Alignment and Phylogenetic Analysis
The gene sequences were aligned using MAFFT to ensure optimal alignment of homologous sequences. A phylogenetic tree was then constructed using FastTree, a method known for its efficiency in estimating large phylogenies. The resulting tree was visualized using the Bio.Phylo module, facilitating a clear representation of the evolutionary relationships.

### Comparative Analysis
The findings were compared with additional data on the geographical distribution, lifestyle, and phenotypic characteristics of Latimeria and related species to draw conclusions about their evolutionary relationships.

## Results

The phylogenetic tree, constructed using the RAG2 gene and generated through FastTree after alignment with MAFFT, provides a clear representation of the evolutionary relationships between Latimeria menadoensis and 27 other selected species, including various fish, amphibians, reptiles, and mammals. On the tree, latimeria is grouped with such species as Protopterus sp. from the class of lobe-finned lynxes, as well as sharks: Torpedo californica, Chiloscyllium punctatum and Triakis sp.

![The position of Latimeria menadoensis on the "tree of life"](./pictures/output%202.png)
*The position of Latimeria menadoensis on the "tree of life"*


Despite its status as a "living fossil" with traits that resemble early tetrapods, such as lobed fins, Latimeria menadoensis is shown to be evolutionarily closer to fish than to tetrapods. This is evident from its distinct branching away from amphibians, reptiles, and mammals, all of which are placed in separate, well-supported branches. The bootstrap values across the tree are high (many close to 1.0), indicating strong support for the inferred relationships. The branch connecting Latimeria to other fish species has particularly robust support, further confirming its closer relationship to modern fish rather than to tetrapods.

## Discussion
These results offer important insights into the evolutionary placement of Latimeria menadoensis. Although often considered a transitional species due to its retention of primitive characteristics, the phylogenetic analysis using the RAG2 gene reveals that Latimeria is more closely related to fish species than to amphibians, reptiles, or mammals. This conclusion is supported by the topology of the tree and the high bootstrap values for key branches.

The choice of the RAG2 gene for this phylogenetic analysis was based on its utility in resolving deeper evolutionary relationships among vertebrates, rather than its role in immune function. The results align well with the current understanding that coelacanths, despite their ancient lineage, are still more closely related to fish than to tetrapods.

## Conclusion
In conclusion, the phylogenetic analysis of Latimeria menadoensis based on the RAG2 gene demonstrates that this species is evolutionarily closer to fish than to tetrapods. The findings challenge the perception that Latimeria's morphological similarities to tetrapods reflect a close evolutionary relationship. Instead, it retains a deep evolutionary connection with other lobe-finned fish.

This study contributes to our understanding of the evolutionary history of Latimeria menadoensis and emphasizes the importance of using molecular data, alongside morphological characteristics, to accurately infer evolutionary relationships. Further studies incorporating additional genetic markers and ecological data would be valuable in providing a more comprehensive picture of the evolutionary forces shaping these lineages.

## Appendix
| Identifier        | Species                                  | Common Name                     | Type       |
|-------------------|------------------------------------------|----------------------------------|------------|
| DQ082330.1        | Felis catus                              | Cat                              | Mammal     |
| DQ119641.1        | Cyclura nubila                           | Iguana                           | Reptile    |
| DQ119640.1        | Leiocephalus barahonensis                | Lizard                           | Reptile    |
| DQ119639.1        | Liasis savuensis                         | Python                           | Reptile |
| DQ119638.1        | Charina trivirgata                       | Rosy Boa                         | Reptile |
| AF447537.1        | Bos taurus                               | Cow                              | Mammal     |
| AY011972.1        | Sus scrofa                               | Pig                              | Mammal     |
| AF080577.1        | Homo sapiens                             | Human                            | Mammal     |
| AB612072.1        | Scaphiopus holbrookii                   | Eastern Spadefoot               | Amphibian |
| AB612064.1        | Megophrys nasuta                        | Horned Frog                     | Amphibian  |
| AB611994.1        | Uperodon montanus                        | Mountain Balloon Frog            | Amphibian  |
| AB611970.1        | Phrynella pulchra                       | Malayan Painted Frog            | Amphibian  |
| AY011980.1        | Ursus arctos                             | Brown Bear                      | Mammal     |
| AF369072.1        | Polypterus sp.                          | Bichir                          | Fish       |
| AF369073.1        | Acipenser sp.                           | Sturgeon                        | Fish       |
| AF369074.1        | Acipenser sp.                           | Sturgeon                        | Fish       |
| AF369075.1        | Polyodon spathula                       | Paddlefish                      | Fish       |
| AF369076.1        | Polyodon spathula                       | Paddlefish                      | Fish       |
| AF369077.1        | Lepisosteus osseus                      | Longnose Gar                    | Fish       |
| AF369078.1        | Lepisosteus osseus                      | Longnose Gar                    | Fish       |
| AF369079.1        | Amia calva                              | Bowfin                          | Fish       |
| AF369080.1        | Amia calva                              | Bowfin                          | Fish       |
| AF369081.1        | Osteoglossum sp.                        | Arowana                         | Fish       |
| AF369082.1        | Chiloscyllium punctatum                 | Brownbanded Bamboo Shark        | Fish       |
| AF369083.1        | Triakis sp.                             | Houndshark                      | Fish       |
| AF369084.1        | Torpedo californica                     | Pacific Electric Ray            | Fish       |
| AF369085.1        | Pachytriton sp.                         | Newt                             | Amphibian  |
| AF369086.1        | Protopterus sp.                         | African Lungfish                | Fish       |
| AF369087.1        | Latimeria menadoensis                   | Coelacanth                      | Unknown    |
| AF369088.1        | Typhlonectes natans                    | Aquatic Caecilian               | Amphibian  |
| AF369089.1        | Trionyx sinensis                        | Chinese Softshell Turtle        | Reptile    |
