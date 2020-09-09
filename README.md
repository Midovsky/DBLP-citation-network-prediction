# DBLP-citation-network-prediction

This project helps prediction of DBLP citation network using LDA model.

## Steps of project

<ol>
<li>Create DBLP citation network in form of graph</li>
<li>Apply PageRank algorithm and sort nodes (choose a number of top nodes)</li>
<li>For every node in top nodes, create the ego centric graph and then fusion these graphs in order to obtain the Ginf Graph</li>
<!-- <li>Create Ginf graph for every top nodes by aggregating the ego centric graphs of this top nodes </li> -->
<li>Apply LDA model</li>
</ol> 

## Usage

Open a Jupyter Notebook and import the file .ipynb


## LDA

Latent Dirichlet Allocation (LDA) is an unsupervised machine-learning model used to classify text in a document to a particular topic. It builds a topic per document model and words per topic model, modeled as Dirichlet distributions.

More details about LDA in [this link](https://towardsdatascience.com/topic-modeling-and-latent-dirichlet-allocation-in-python-9bf156893c24) 
