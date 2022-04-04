***Title of the dataset / Data underlying the publication: ‘Effects of E. coli Nissle 1917 on the Porcine Gut Microbiota and Immune System in Early Life’***

***Creators***
Mirelle Geervliet 1,†, Hugo de Vries 2,3,†, Christine A. Jansen 1,4, Victor P.M.G. Rutten 4,5, Hubèrt van Hees 6, Caifang Wen 3, 
Kerstin Skovgaard 7, Giacomo Antonello 8, Huub F.J. Savelkoul 1, Hauke Smidt 3, Edwin Tijhaar 1,†, and Jerry M. Wells2,†,*

1	Cell Biology and Immunology Group, Wageningen University & Research, Wageningen, The Netherlands; mirelle.geervliet@wur.nl; huub.savelkoul@wur.nl; edwin.tijhaar@wur.nl; christine.jansen@wur.nl 
2	Host-Microbe Interactomics Group, Wageningen University & Research, Wageningen, The Netherlands; jerry.wells@wur.nl
3	Laboratory of Microbiology, Wageningen University & Research, Wageningen, The Netherlands; hugo.devries@wur.nl; caifang.wen@wur.nl; hauke.smidt@wur.nl 
4	Department of Biomolecular Health Sciences, Division of Infectious Diseases and Immunology, Faculty of Veterinary Medicine, Utrecht University, Utrecht, The Netherlands; v.rutten@uu.nl 
5	Department of Veterinary Tropical Diseases, Faculty of Veterinary Science, University of Pretoria, Pretoria, South Africa; v.rutten@uu.nl 
6	Research and Development, Trouw Nutrition, Amersfoort, The Netherlands; hubert.van.hees@trouwnutrition.com
7       Department of Biotechnology and Biomedicine, Technical University of Denmark, Lyngby, Denmark; kesk@dtu.dk
8       Department of Cellular, Computational and Integrative Biology, University of Trento, Trento, Italy; giacomo.antonello@unitn.it

* Correspondence: jerry.wells@wur.nl

† These authors have contributed equally to this work and share first or last authorship.

***Related publication***
Title: Effects of E. coli Nissle 1917 on the Porcine Gut Microbiota and Immune System in Early Life
DOI: 10.3389/fcimb.2022.842437
Received: December 23th, 2021; Accepted: February 1st, 2022; Published: 2022

***General Introduction***
This dataset contains data collected during an in vivo experiment with pigs at the Wageningen University as part of the PhD Thesis Projects of Mirelle Geervliet and Hugo de Vries (first authors of the manuscript). 
This research project was made possible by The Netherlands Organisation for Scientific Research and Vereniging Diervoeders Nederland (VDN).

***Purpose of the study***
In this study, we investigated whether early life supplementation of EcN affects the gut microbiota as well as the immune system. 
In addition, we examined the temporal presence of EcN in feces and digesta.
We hypothesized that early life consumption of EcN alters gut microbiota development (composition) and the immune system. 
A more developed and mature gut microbiota and immune system in early life could make the animals more resilient against invasive pathogens during the weaning phase and later in life.

***Structure***
Data_analyses_in_R_Studio/ # Main data analysis folder.
				|---- Figures # folder where raw figures are placed when generated in R-Studio.
				|---- input_data # this folder contains data files that are imported into R-Studio for microbiota related analyses, such as the .biom, .tre and metadata files.
				|---- input_data_flow_cytometry # this folder contains data files that are imported into R-Studio for flow cytometry related analyses.
				|---- Input_data_restimulation_assay # this folder contains data files that are imported into R-Studio for restimulation assay related analyses.
				|---- input_data_vaccination_response # this folder contains data files that are imported into R-Studio for vaccination response related analyses.
				|---- output_data # two data files were generated in the R code, which are placed into this folder.
				|---- phyobjects # phyloseq objects that were generated in the R code are placed into this folder. these .rds files are frequently imported into R (with every new analysis they are re-imported).
				|---- Porcine_study_EcN_R_analyses_nov2020.Rproj # Rproject file.
				|---- Porcine_study_EcN_R_analyses_nov2020_markdown_file.html # HTML file that was generated using the knitr function in R-Studio. This file has been copied to the master folder, as it contains a complete overview of the analyses performed.
				|---- Porcine_study_EcN_R_analyses_nov2020_markdown_file.rmd # Codes used during the analyses.
				
***Instructions***
1. Open 'Porcine_study_EcN_R_analyses_nov2020.Rproj' in R-Studio.
2. Open 'Porcine_study_EcN_R_analyses_nov2020_markdown_file.RMD' and click knit to reproduce the analyses and re-create the HTML file.
3. If an error occurs, make sure to use the same version of R and install the same versions of the R packages used. This info can be found at the end of the HTML file.

The final figures in the manuscript were adjusted using Adobe Illustrator to improve their clarity (i.e. label font/direction).
			