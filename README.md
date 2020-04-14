# FARFAR2-SARS-CoV-2
Models of SARS-CoV-2 genomic elements generated by FARFAR2

# How is this repository organized?
We've organized the simulations we ran into directories according to the genomic region they came from: the 5′ or 3′ UTR or the frame shift element. Each simulation's subdirectory contains a pymol session (the exact session used for figure rendering) and a number of PDB files. These PDB files include all the cluster centers from the FARFAR2 clustering protocol, as well as up to 50 additional members of each cluster center. The cluster centers are numbered c.0.0.pdb through c.9.0.pdb, while the best-energy cluster's associated models are numbered c.0.0.pdb to c.0.49.pdb (if all 50 models are present).

# How can I use this repository?
However you want! Of course, our most urgent hope is that these models will be useful to drug development against SARS-CoV-2, but if you are training a new RNA scoring function (...which itself may someday be useful against new viral pandemics), please make use of these models.
