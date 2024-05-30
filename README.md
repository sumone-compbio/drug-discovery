# Drug-Discovery
A simple easy-to-follow tutorial on Drug Discovery with Machine Learning. Here I chose the target protein PIK3CA phosphatidylinositol-4,5-bisphosphate 3-kinase catalytic subunit alpha (human). First, I fetched the data from the chembl of known experimentally validated inhibitors of our target. Using the smiles of each compound I calculated the rdkit descriptors which later on serve as features while the corresponding pic50 value is the the label. Since the pic50 is continuous, I trained a regression model. 
Below are the regression plots of train and test data comparing the R2 score of real vs predicted values. 

![Screenshot from 2024-05-30 16-19-54](https://github.com/sumone-compbio/drug-discovery/assets/43076959/61fae071-1bc8-4d7c-944e-34b57999eabb)
