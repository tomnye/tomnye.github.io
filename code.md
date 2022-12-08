<link rel="stylesheet" type="text/css" href="/css/main.css">
<meta name="keywords" content="Tom Nye; probability; statistics; Newcastle; geometry; phylogenetics; phylogenetic tree;">

<div class="topnav">
<ul>
  <li style="display:none;"></li>
  <li><a href="index.html">Home</a></li>
  <li><a href="code.html">Code</a></li>
  <li><a href="group.html">Group</a></li>
</ul>
</div>


## Software

Java source code and executables for software associated with several of my publications is available on github. 
Instructions for running the software will be given for each project -- [email me](mailto:tom.nye@ncl.ac.uk) if these are not posted yet. 


### GATSby (Geometry and Analysis in Tree Space)

[GATSby](https://github.com/tomnye/GATSby) is required to run all my other software. 
It provides a very wide variety of structures and methods for phylogenetic trees. 
Most importantly, it combines representations of trees as (a) graph structures (sets of vertices and edges) and (b) as weighted sets of compatible splits. 
The former representation allows efficient representation of Markov substitutions on trees and associated probability calculations (simulating alignments, calculating likelihoods); 
the latter representation is the best for analysis of trees in Billera-Holmes-Vogtmann (BHV) tree space. 
The libraries include methods to swap between these representations. 
It is possibly unique in proividing this combination of representations. 
Features include:

* the Owen-Provan algorithm for construction of geodesics in BHV tree space;
* projection of trees onto BHV geodesics;
* a variety of nucleotide and amino acid substitution models; 
* simulation of alignments and likelihood calculation given an alignment;
* topological operations on trees (e.g. subtree-prune-and-regraft); and
* basic graphics for drawing rooted and unrooted trees.


### Compare2Trees

[Compare2Trees](https://github.com/tomnye/Compare2Trees) is a popular program for comparing phylogenetic trees. 
It is showing its age now as it was [first published](https://academic.oup.com/bioinformatics/article/22/1/117/217975) in 2006. 
In order to run the executable, you need to download the Compare2Trees jar files and those for GATSby. 


### GeoPhytter

[GeoPhytter](https://github.com/tomnye/GeoPhytter) fits geodesics and higher-dimensional surfaces to data in BHV tree space. 
It provides methodology associated with three of my publications for tree space PCA:

* [Principal components analysis in the space of phylogenetic trees](https://projecteuclid.org/journals/annals-of-statistics/volume-39/issue-5/Principal-components-analysis-in-the-space-of-phylogenetic-trees/10.1214/11-AOS915.pdf), Annals of Statistics, 2011;
* [An algorithm for constructing principal geodesics in phylogenetic treespace](https://ieeexplore.ieee.org/abstract/document/6755452), IEEE/ACM Transactions on Computational Biology and Bioinformatics, 2014; and
* [Principal component analysis and the locus of the Fréchet mean in the space of phylogenetic trees](https://academic.oup.com/biomet/article/104/4/901/4259146), Biometrika, 2017.


### ProbDist

[ProbDist](https://github.com/tomnye/ProbDist) uses simulation methods to compute probabilistic distances between phylogenetic trees. 
It provides methodology associated with my paper on [probabilistic distances between trees](https://academic.oup.com/sysbio/article/67/2/320/4344841?login=false), Systematic Biology, 2018.

