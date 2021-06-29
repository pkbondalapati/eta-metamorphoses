# Exporatory Text Analysis on Ovid's *Metamorphoses*

Author: Pavan Kumar Bondalapati

DS 5001: Exploratory Text Analytics

University of Virginia

School of Data Science

May 11, 2021

## Overview

The goal of this project is to extend the tools of exploratory text analysis to Ovid's *Metamorphoses*. Specifically, clustering is employed on the 15 books of *Metamorphoses* to potentially identify the latent chronology nature of the poem. Then, topic modeling is applied in order to better understand the composition of these derived clusters. This project is fully articulated in this [paper](./paper.pdf).

## Notebooks

1. `1-Conversion.ipynb`
    
    Converts plain text files of Ovid's *Metamorphoses* into library, vocabulary, and token tables.

2. `2-Clustering.ipynb`

    Applies clustering on the 15 books under numerous linkage methods.

3. `3-PCA.ipynb`
    
    Applies principal component analysis (PCA) to better characterize the fables.

4. `4-LDA.ipynb`

    Applies latent Dirichlet allocation (LDA) to understand the composition the clusters.
    
5. `5-Word2Vec.ipynb`

    Generates a "word2vec" model and applies t-SNE to cluster related words from the entire poem.
    
6. `6-Sentiment.ipynb`

    Applies sentiment analysis on the clusters to help assess congruence.
