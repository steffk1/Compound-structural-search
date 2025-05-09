This is the GitHub repository to go with the publication Steffen _et al._, XXXX (https://doi.org/10.1101/2025.05.08.652894). 
We aim to to make our methods accessible and reusable for the community. Therefore, subsequently, we provide a tutorial for compound clustering as well as a GUI and the required input files as used in the publication.

Fundamentally, the concept is to make use of existing BGC-SM links gathered from the publicly curated BGC–SM database MIBiG (https://mibig.secondarymetabolites.org/) to compare a structure of interest, i.e. a natural product. This can help to 

 (1) identify compounds for which a BGC is known,   
 (2) suggest structurally similar matches between the compound of interest and a database compound, which could help attribute additional compounds to a known BGC or discover similar BGCs, as well as  
 (3) suggest more unique compounds as research targets for the discovery of new BGCs.

Besides the utility for natural product chemists, this is also a useful tool for biologist to orthogonally validate BGC predictions with the corresponding metabolomic data.
The method as documented subsequently is fast (at the scale performed in the publication) and relies only on open source, well maintained python libraries, which we hope makes this a long-lasting and adaptable method looking forward.
