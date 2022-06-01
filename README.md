# BIMM143_Project2_Draft_BT
Draft of all the materials for my Project 2 for BIMM 143

## Scientific Question
Are the 3 most upregulated genes in the coral Balanophyllia elegans in an acidic ocean condition specific to the biological processes that corals undergo (e.g. calcification and skeletal matrix formation), or are they associated with broad biological processes that are shared among other organisms?

## Hypothesis
If the most highly expressed genes in the coral Balanophyllia elegans in acidic ocean conditions are associated with calcification or skeletal matrix formation which are specific to corals, then these corals would undergo specialized changes in response to ocean acidification rather than changing broad cellular or physiological processes that are shared among many other organisms.

## Files
Project_2_rawcounts.csv: The raw counts data contains the number of reads for the genes in the corals in this study. This csv was sourced from another study (https://github.com/JoannaGriffiths/Coral-population-responses-to-acidification), but it was simplified to only include one population instead of two populations that were used in this original study. The raw counts data will be used in conjunction with the metadata to perform differential expression analysis in genes in corals between low and high acidity conditions.

Project_2_metadata.csv: The metadata contains the information about the sample groups and the conditions for the study that I am conducting. This is used in conjunction with the raw counts data to study differential expression in genes based on the sample groups and conditions indicated by the metadata. This csv was sourced from another study (https://github.com/JoannaGriffiths/Coral-population-responses-to-acidification), but it was simplified to only include one population instead of two populations that were used in this original study.

Project_2C.rmd: This is an R markdown file of the code used to perform all the bioinformatics analyses in the study. All the code is contained in the chunks on R and has comments that explain each line of code.

Project_2C_draft.html: This is a knitted html file of the R notebook which contains all the code to perform all the bioinformatics analyses in the study as well as all the resulting outputs of the code.
