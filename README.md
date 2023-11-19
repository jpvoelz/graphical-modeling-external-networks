# Understanding Mechanisms of Fetal Inflammatory Response through Graphical Modeling with External Network Data
In this paper submitted as our master project for the Data Science Methodology program at the Barcelona School of Economics in 2023, we augment a graphical model with external network data to improve inference on small samples of high-dimensional gene expression data from neonates with and without fetal inflammatory response (FIR).

Using a penalized likelihood framework, we demonstrate that incorporating network data of gene interactions from the Gene Ontology (GO) database improves inference across three different sets of clinical data. 

Using a Bayesian spike-and-slab approach, we confirm that gene pairs with more connections in the GO database are more likely to have a non-zero partial correlation. Our results show agreement across models about the existence of edges between gene pairs known to be upregulated with FIR, demonstrating that our model captures biologically relevant relationships. 

In our analysis, we explore the limitations of our data and possible interpretations that could connect our graphical models to the understanding of the mechanisms behind FIR.

