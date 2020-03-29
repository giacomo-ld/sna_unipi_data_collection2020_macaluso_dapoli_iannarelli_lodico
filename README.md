# Assignment 0 Part 0: Data Collection

Data collection can be carried out without any restriction on programming languages (python is only a warm suggestion) and/or online sources.

The adoption of already crawled network datasets available on the internet (e.g., networks from networkrepository, socialcomputing, snap, konect...) **will not** be considered as a valid option.

## Workflow

1. Identify an online data source,
2. Crawl data from it (or collect them through API if available),
3. Build up a network from the data!

## Requirement:
- The network must have **at least** 10-15k nodes. 
Specific cases involving the analysis of smaller networks must be discussed beforehand with the instructor.

- The produced code must be stored into the *code* folder: please, briefly comment the choices made/strategies adopted to perform the crawling.
- The final version of the data (i.e., the network and, if present, all additional data) must be compressed and stored into the **data** folder.
## Data Sources ideas:
Twitter, Last.fm, Blogs, Reddit, Blabla car, Linkedin, Corpora, Wikipedia, Newspaper...

# Assignment 0 Part 1: Network Analysis

The analysis can either be performed by using a visual tool (i.e., Cytoscape/Gephi) and/or with the support of a programming language.
The use of python libraries ([networkx](https://networkx.github.io/) or [igraph](https://igraph.org/python/)) is not mandatory, although, strongly suggested. 
 
Network analysis must include (but needs not to be limited to):
- Degree distribution analysis;
- Connected components analysis;
- Path analysis;
- Clustering Coefficient, Density analysis;
- Centrality analysis.

Moreover, the statistics computed on the crawled data must be compared with the ones of (i) ER, (ii) BA, (iii) WS and (iv) configuration model graphs having the same number of nodes and edges.

## Requirement:
- The code produced for performing the analysis must be stored in the folder **code**. 
- The plots produced must be stored in the folder **plots**.
