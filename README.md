# Drug-Discovery
A simple easy-to-follow tutorial on Drug Discovery with Machine Learning. Here I chose the target protein PIK3CA phosphatidylinositol-4,5-bisphosphate 3-kinase catalytic subunit alpha (human). First, I fetched the data from the chembl of known experimentally validated inhibitors of our target. Using the smiles of each compound I calculated the rdkit descriptors which later on serve as features while the corresponding pic50 value is the the label. Since the pic50 is continuous, I trained a regression model. 
Below is the regression plots of train and test data comparing the R2 score of real vs predicted values. 
![PIK3CA_ExtraTrees_training](https://github.com/sumone-compbio/drug-discovery/assets/43076959/2bc4dda2-ec8a-41db-b8cc-d86809517882)
![PIK3CA-ExtraTrees_testing](https://github.com/sumone-compbio/drug-discovery/assets/43076959/17273283-ae6c-429a-ab9e-93266d6a46bd)
