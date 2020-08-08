---
permalink: /
title: "Introduction"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Networks are ubiquitous, they can be categorized as static network and dynamic networks. There are many optimized graph algorithms to analyze static networks,however there are very few algorithms which analyze dynamic networks.

We use an elegant technique called graph sparsification to create fast and scalable parallel algorithms for updating properties of dynamic networks. Using a divide and conquer approach, the original network is divided recursively into several small subgraphs over a structure called the sparsification tree, until each subgraph represents an edge in the network. Graph sparsification is based on the observation that the edges that pertain to the property to be computed, here termed as key edges, often form a very small portion of the total edges of the network, and therefore requires less time to be updated. Also when a new edge is added or deleted, we only need to consider the subgraph to which it belongs.


