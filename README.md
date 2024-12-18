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
It contains scripts to modify four input features of drugs (Target, Enzyme, Pathway, Substructure). Features are extracted from DrugBank, PubMed, Kegg. Then, the features are done with one-hot encoding and Jaccard Similarity matrix calculation to uniform the input size as 556*556. This file is mainly focusing on the data preprocessing part. Details are explained in the comment part in the .ipynb file

# Encoder
This file is using sentence transformer to translate drug-drug interaction description to vectors. Then, k-means cluster is applied to group the description into categories based on the embedding space.

# Author
Created by: Qiuyang Feng

Contact: frankfeng1202@gmail.com
