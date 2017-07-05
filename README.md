# Topic exploration
## Meissner-like effect for rotating black holes
In this topic exploration, we study the Meissner-like effect for rotating black holes.
It describes the expulsion of stationary axisymmetric magnetic fields from the outer horizon when the black hole reaches its maximum angular momentum. 

# WSS17 Project
## Growth and spreading of topics on arXiv.org
### Goal of the project: 
The project has a twofold goal. Given a keyword representing a scientific topic (e.g., entanglement, gravitational waves, etc...), we compute the number of occurrences of the keyword that appears in the abstracts of papers in a given time interval and we study how papers about a specific topic are related to each other by analyzing the corresponding citations. In particular, we construct the citation graph associated to the topic and we display its time evolution. 

### Summary of the work: 
As a preliminary step, we download an updated snapshot of record metadata in JSON format containing information about one million of papers posted on inSpireHEP. After adjusting the database to our purposes, we collect the abstracts year by year. The first goal is reached by using the built-in function StringCount, which counts how many times the keyword appears in the abstracts within a given time interval. Then we chart the occurrences by using DateListPlot and few examples of keyword search are shown. The second goal is achieved by selecting those papers concerning the chosen topic and by associating each of these papers to their list of citations. We construct the corresponding citation graph and highlight the communities by centrality-based clustering criterion. We emphasize those papers whose position is relevant for the topology of the graph. Finally, we introduce a further time selection of papers (in addition to the topic selection) in order to display the time evolution of the graph.

### Result and future work: 
In this project, we defined a search engine that charts occurrences of any keyword in the abstracts of papers posted on inSpireHEP/arXiv.org. As an example, we studied the occurrences of "LHC" and "Higgs" from 1985 to 2015. As expected, the "LHC" occurrences increase after the first run in 2008 and the "Higgs" occurrences increase soon after the announcement of the Higgs boson discovery in 2012. Another result is to emphasize those papers about one specific chosen topic that play an important role in the structure of the citations graph, because of their high degree of centrality and not only because they are the most cited papers in the field. Future directions are to study the properties of the citation graph in detail.
