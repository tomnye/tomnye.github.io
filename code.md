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
I provides a very wide variety of structures and methods for phylogenetic trees. 
Most importantly, it combines representations of trees as (a) graph structures (sets of vertices and edges) and (b) as weighted sets of compatible splits. 
The former representation allows efficient representation of Markov substitutions on trees and associated probability calculations (simulating alignments, calculating likelihoods); 
the latter representation is the best for analysis of trees in Billera-Holmes-Vogtmann tree space. 
The libraries include methods to swap between these representations. 
It is possibly unique in proividing this combination of representations. 
Features include:

* the Owen-Provan algorithm for construction of geodesics in BHV tree space;
* projection of trees onto BHV geodesics;
* a variety of nucleotide and amino acid substitution models; 
* simulation of alignments and likelihood calculation given an alignment;
* topological operations on trees (e.g. subtree-prune-and-regraft); and
* basic graphics for drawing rooted and unrooted trees.
