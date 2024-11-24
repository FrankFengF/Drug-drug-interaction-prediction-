# Drug-drug-interaction-prediction
Use similarity-based machine learning approach to predict drug-drug interactions


# Requirements
To run this notebook, the following dependencies must be installed:

Python (version 3.7+)
Common Python libraries:
pandas
numpy
matplotlib
seaborn
scikit-learn (if machine learning-related transformations are included)

# Manipulation
It contains scripts to modify four input features of drugs (Target, Enzyme, Pathway, Substructure). Features are extracted from DrugBank, PubMed, Kegg. Then, the features are done with one-hot encoding and Jaccard Similarity matrix calculation to uniform the input size as 556*556. This file is mainly focusing on the data preprocessing part.
