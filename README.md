# -AI_and_Drug_Discovery_Course_2026
# ~ASSIGNMENT 2- QSAR Data Curation Using ChEMBL

Target selected for ligand data curation using ChEMBL and further pre-processing was "BRAF" or "Serine/threonine-protein kinase B-raf" [CHEMBL5145]
The number of bioactivity records for this target is 25,907.
For curating data for target "BRAF", ChEMBL was used. Target protein was searched in the ChEMBL database using python library in a jupyter notebook interface on google colab. The data generated was filtered for only bioactivity records. Out of the several bioactivity types, we chose IC50 value metric for selecting our ligands. The lower the IC50 values, the higher the inhibition potency of the ligand. After removing the duplicate values, and saving the raw data file, we removed NA or missing values. Then we set threshold for IC50 values that was used to characterise ligands as active, inactive or intermediate. 4 columns including molecular ids, canonical smiles, standard values and bioactivity class were extracted out as these were relevant to our research. Finally, after removing entries without relevant smiles, we saved our processed data.
