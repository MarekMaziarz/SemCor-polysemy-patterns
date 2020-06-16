# SemCor-polysemy-patterns
This data set comprises polysemy links and patterns derived from SemCor 3.0 and Princeton WordNet 3.0

SemCor_polysemy_instances_directed_WN30.txt
This resource contains polysemy relation instances linking WordNet synsets. We assumed that meanings that appear in one text are semantically related to each other. The links are directed with the direction from the succeeding sense to the preceding one.

SemCor_LF_polysemy_patterns_directed.txt
This file contains links between lexicographer files being proxy to polysemy patterns. The procedure was following: we started from the file SemCor_polysemy_instances_directed_WN30.txt, through changing synset identifiers into its lexicographer file, we obtained the net of linked semantic domains with known frequencies.

WN30_top_synsets_linked_to_LFs_undirected.txt
Top-most synsets from Princeton WordNet linked to their semantic domains (lexicographer files). Links are bi-directional.
