[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/27410-2020-group-project-group-7_vibrio-natriegens/main)

# 27410 - Group assignment - Group 7 - Vibrio natriegens producing beta-carotene

## Project summary
This project aims to build a genome-scale model (GSM) of the emerging cell factory, Vibrio natriegens. The draft GSM is constructed using carveme and further improved by validating it with experimental data found in literature. The model ended up getting an overall score of 23% in MEMOTE. Beta-carotene production is added as a heterologous pathway for the GSM of V. natriegens. The model is subsequently used to predict the theoretical maximum yields of beta-carotene in V. natriegens, and different process conditions are assessed by plotting and analyzing phenotypic phase planes. The beta-carotene pathway reactions ate also inserted in *E. coli* iML1515 for comparison. Production of beta carotene in the V. natriegens model is 2-fold higher than in the E. coli model, but the yield of beta carotene on glucose is more or less the same.

## Project overview
The Report.ipynb notebook contains the main report of this project. The Models folder contains the GSMs used in this project. modelc.html is the memote report created for the GSM model in which modifications/alterations have been made; Vibrio-natriegens-ATCC_14048-M9.html is the memote report of the original report of *V. natriegens* ATCC 14049. In FindMetaboliteIDs.ipynb, the different metabolites already present in the model are found, which are used when creating the reactions needed for the production of beta-carotene. The different reactions for the production of beta-carotene can be found in Beta+MVA-pathway.ipynb. In Betacarotene_in_Ecoli.ipynb, the beta-carotene pathway reactions are inserted and production calculated in *E. coli* iML1515 GSM.  In requirements.txt, all of the packages applied in this project are listed. 

