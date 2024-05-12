# Clustering Businesses Based on Categorical Features

## Data

Obtained from sam.gov; look for sam.csv

## Purpose

I was assisting someone competing in a Tableau IronViz competition. They wanted me to create something like a knowledge graph of the different businesses based on `'Legal Business Name', 'NAICS Description', 'Product or Service Description', 'Description of Requirement'`


## Methodology 

1. Create dummy variables from naics and product fields since some values are shared across multiple businesses. 

2. Used TSNE to scale the data to 2-dimensions

3. Used AffinityPropogation to transform the TSNE embeddings to clusters

4. Used NLP similarity scores to show how related clusters might be



