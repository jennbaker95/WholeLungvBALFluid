# WholeLungvBALFluid

The purpose of this repository is to provide public access to the R code and data files used in the following publication: 

Baker et al. 2020. Application of a novel analytic approach to discriminate signal and noise in low-biomass microbiome studies: Whole lung tissue is the preferred sampling method for amplicon-based characterization of murine lung microbiota (in preparation). 


#### Outline of Analytical Approach for Low-Biomass Specimens

1) Specimen collection and processing 
  - Goal: Selection of appropriate numbers and types of negative and positive controls - sample all potential source communities
  - Method: Thoughtful experimental design and sterile specimen collection 
 
2) Quantification 
  - Goal: Confirm sufficient quantities of DNA (bacterial and total) have beeen isolated from low-biomass samples
  - Method: droplet digital PCR or qPCR for bacterial DNA quantification, Qubit or Nanodrop for total DNA quantification
  
3) Sequencing, Identification, and Quantification of Bacterial Reads
  - Goal: Amplify, sequence, identify, and quantify bacterial reads in low-biomass specimens
  - Method: PCR amplification, 16S rRNA gene amplicon sequencing, mothur, calculation of read counts per specimen
  
4) Diversity of Identified Bacterial Taxa
  - Goal: Determine bacterial signal is distinct from controls and reproducible among biological replicates
  - Method: Calculation of alpha (e.g. rarified richness, Shannon diversity index) and beta (e.g. Bray-Curtis dissimilarity index) diversity metrics

5) Relative Abundance of Identified Bacterial Taxa 
  - Goal: Determine the biological plausibility of bacterial taxa identified in low-biomass samples 
  - Method: Principal component analysis and ranked relative abundance of bacterial taxa
  
 
#### Description of Files included in Repository

- Rmarkdown with code 
- taxonomy file
- shared file 
- quantification data 
- read count data


#### External Links: 
- Link to publication: 
- Link to SRA submission: 

Packages and dependencies required to run code in the repository can be found in session info in the knitted Rmarkdown pdf and html.
