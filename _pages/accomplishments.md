---
permalink: /
title: "Accomplishment"
excerpt: "Accomplishment"
author_profile: true
redirect_from: 
  - /accomplishment/
  - /accomplishment.html
---
The primary goal of this group is to develop parallel algorithms for updating properties of dynamic networks. The main challenge in scalable parallel algorithms design is poor locality of memory accesses for graph traversals, leading to increased computation time and power requirements, and reduced opportunities for scalability. 

We advocated a three-step process for parallel update of graph properties. In the first step, called Sparsification, we identify key edges in the network. In the second step, called Selection, we test for each changed edge on the sparsified graph, as to whether the edge affected the property or not. In the final step, called Update, the structure of the network is updated based on the selected edges.
 
In the 2019-2020 year, we focused on the following problems: (i) exploring how the three-step process applies to parallel platforms beyond shared memory architecture, such as distributed memory systems and GPUs; (ii) developing algorithms for strongly connected components (SCC), k-core computation and single source shortest paths (SSSP) that are applicable across multiple parallel platforms; (iii) developing adaptive algorithms that can switch between  dynamic updates or recomputation as per the number and type of changes ; and (iv) applying the algorithms to real-world applications including computational epidemiology, bioinformatics and , networks of internet of things (IoT) in fog-based distributed computing systems.

Major Activities:  
======

Develop template for updating dynamic graphs in multiple platforms including shared and distributed memory systems and GPUs for SCC and SSSP
Develop adaptive algorithms for determining when to use dynamic updates and when to use recomputation
Develop predictive algorithms to determine best snapshot of static graphs to be taken for a stream of edges
