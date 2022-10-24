# NetworkAnalysis
Network Analysis Using Graph C++
Datasets
1. General Relativity and Quantum Cosmology collaboration network Dataset
Description
Arxiv GR-QC (General Relativity and Quantum Cosmology) collaboration network is from the e-print arXiv
(https://arxiv.org/archive/gr-qc) and covers scientific collaborations between authors papers submitted
to General Relativity and Quantum Cosmology category. If an author i co-authored a paper with author j,
the graph contains a undirected edge from i to j. If the paper is co-authored by k authors this generates a
completely connected (sub)graph on k nodes.
The data covers papers in the period from January 1993 to April 2003 (124 months). It begins within a few
months of the inception of the arXiv, and thus represents essentially the complete history of its GR-QC
section.
2. Astro Physics collaboration network Dataset Description
Arxiv ASTRO-PH (Astro Physics) collaboration network is from the e-print arXiv
(https://arxiv.org/archive/astro-ph) and covers scientific collaborations between authors papers
submitted to Astro Physics category. If an author i co-authored a paper with author j, the graph contains
a undirected edge from i to j. If the paper is co-authored by k authors this generates a completely
connected (sub)graph on k nodes.
The data covers papers in the period from January 1993 to April 2003 (124 months). It begins within a few

months of the inception of the arXiv, and thus represents essentially the complete history of its ASTRO-
PH section.

3. Amazon product co-purchasing network and ground-truth communities Dataset
Description
Data was collected by crawling Amazon website. It is based on Customers Who Bought This Item Also
Bought (explained here: https://davidgaughran.com/also-boughts-amazon-recommendations/) feature
of the Amazon website. If a product i is frequently co-purchased with product j, the graph contains an
undirected edge from i to j. Each product category provided by Amazon defines each ground-truth
community.
We regard each connected component in a product category as a separate ground-truth community. We
remove the ground-truth communities which have less than 3 nodes.


Tasks Implemneted:
First Set of Tasks – Graph Stats
1. Display the number of nodes 
2. Display the number of edges 
3. Display the number of source nodes 
4. Display the number of sink nodes 
5. Display the number of isolated nodes 
6. Display the number of bridge edges 
7. Display the number of articulation nodes 
8. Display the shortest path length distribution 
9. Display the diameter of the graph 

Second Set of Tasks – Degree Distributions
10. Display the in-degree distribution in the form of a table 
11. Display the out-degree distribution in the form of a table

Third Set of Tasks – Connected Components
For the original graph:
12. Display the size of the largest strongly connected component (SCC) 
13. Display the size distribution of all SCCs 
Considering the graph as an undirected graph:
14. Display the size of the largest weakly connected component (WCC) 
15. Display the size distribution of all WCCs 



