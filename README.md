# Final Project of the Ironhack Data Analytics Bootcamp
![image](https://user-images.githubusercontent.com/90774339/145224140-2fb50217-af3c-4e40-a0d8-20f4ed2b9664.png)![image](https://user-images.githubusercontent.com/90774339/145224177-1c92bb53-451d-4727-91fd-0fb6ca79c763.png)


## Describing and Clustering bacterial isolates
## DATA
Database: PubMLST -  Public databases for molecular typing and microbial genome diversity

Database url: https://pubmlst.org/ 

Subsets:
| Bacterial species          | number of isolates |
| ---------------------------|-----------|
| *Escherichia* spp. 	    	  | 4.683 |
| *Staphylococcus aureus* 	    | 36.980 |
| *Campylobacter jejuni/coli*	| 101.591 | 
| *Steptococcus pneumoniae*	  | 156.961  |

Metadata:
- Location of isolation (region, country, continent); year of isolation; age, sex of patient, disease, source of isolate,
- Info on presence of antimicrobial resistance and virulence genes

Multilocus sequence typing (explained):
- based on sequences of ~7 house keeping genes (differnt for each bacterial species)
- each gene variation (allele) assigned to number
- number combination = Sequence type (ST)
- STs with one allele difference = ST Complex

Multilocus sequence typing (data):
- each housekeeping gene with allel number
- assigend ST
- assigned ST Complex

## OBJECTIVE

Descripte analysis:
- Isolate distribution (country, year, age group)
- ST counts/ ST Complex counts

Modeling:
- Correlation between ST and country, year, antimicrobial resistance genes
- Minimum spanning trees (Clustering) of isolates based on MLST
- Clusters associated with certain disease or resistance etc.

