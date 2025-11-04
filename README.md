This directory contains all files related to the paper.

### 01_protein_sequences:

Full-length protein sequences of human proteins which were retrieved from the Consensus Coding Sequence (CCDS) database (version 24). 

### 02_assigned_domains:

This file contains identified and annotated protein domains. 
Human protein domain profiles were obtained from the Pfam database (version 37.0), downloaded via the Pfam FTP service. To assign domains to the protein sequences, the HMMER tool (hmmsearch, version 3.4) was used to scan the sequences against the Pfam hidden Markov models (HMMs). Domain boundaries were annotated based on hits passing a stringent E-value cutoff ≤ 1 × 10⁻⁸.


### 03_aligned_domains:

This directory contains multiple sequence alignments (MSAs) of protein domains.
Domain sequences were aligned using the MUSCLE program (version 3.8.31).

### 04_mapped_mutations:

This file contains the pan-cancer missense mutations mapped onto the corresponding domain multiple sequence alignments (MSAs).
If a mutation was mapped to two different Pfam domains, the one with the lowest E-value was used for the analyses. 
