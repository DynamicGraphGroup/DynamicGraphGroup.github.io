---
permalink: /
title: "Accomplishments"
permalink: /accomplishments/
excerpt: "accomplishments"
author_profile: true
redirect_from: 
  - /accomplishments/
  - /accomplishments.html
---

The primary goal of this group is to develop parallel algorithms for updating properties of dynamic networks. The main challenge in scalable parallel algorithms design is poor locality of memory accesses for graph traversals, leading to increased computation time and power requirements, and reduced opportunities for scalability. 

We advocated a three-step process for parallel update of graph properties. In the first step, called Sparsification, we identify key edges in the network. In the second step, called Selection, we test for each changed edge on the sparsified graph, as to whether the edge affected the property or not. In the final step, called Update, the structure of the network is updated based on the selected edges.
 
In the 2019-2020 year, we focused on the following problems: (i) exploring how the three-step process applies to parallel platforms beyond shared memory architecture, such as distributed memory systems and GPUs; (ii) developing algorithms for strongly connected components (SCC), k-core computation and single source shortest paths (SSSP) that are applicable across multiple parallel platforms; (iii) developing adaptive algorithms that can switch between  dynamic updates or recomputation as per the number and type of changes ; and (iv) applying the algorithms to real-world applications including computational epidemiology, bioinformatics and , networks of internet of things (IoT) in fog-based distributed computing systems.

Major Activities:  
======

Develop template for updating dynamic graphs in multiple platforms including shared and distributed memory systems and GPUs for SCC and SSSP
Develop adaptive algorithms for determining when to use dynamic updates and when to use recomputation
Develop predictive algorithms to determine best snapshot of static graphs to be taken for a stream of edges
Design graph algorithms for identifying protein complexes in PPI networks
Design graph algorithms for fast simulation of epidemic spread 
Design efficient graph-based algorithms for task throughput maximization in IoT networks where the topology changes dynamically.
 
Specific Objectives: 
======
(i) develop distributed memory algorithms and GPU based for updating strongly connected components (in directed graphs) and shortest paths;
(ii) develop adaptive algorithms for dynamic networks
(iii) develop  algorithms for identifying appropriate snapshots of streaming graphs
(iv) apply graph algorithms for simulation of epidemics and identifying protein complexes in PPI networks
(v) develop efficient multi-graph-coloring based algorithm, for task execution in an IoT-enabled network in presence of heterogeneous task demands and limited resources. 

Significant Results: 
======
We proposed the first parallel algorithm for updating strongly connected components (SCC) for dynamic (directed) networks.  
We developed a novel distributed computing approach to updating single-source shortest paths (SSSP) and implemented on GPU architecture.
We developed a template for switching between dynamic updates and recomputing algorithms
We  developed probabilistic techniques for finding appropriate snapshots of graphs
We developed a fast algorithm for simulating spread of epidemics in a college network
We leveraged properties of planar graphs for finding important proteins in biological networks
We designed dynamic algorithms for social networks and mobile crowdsensing applications.
We developed efficient graph-based solutions for IoT networks. 

Key outcomes or other achievements: 
======


Our key achievement during this period is to extend our template of parallel algorithms for dynamic networks from shared memory models to distributed memory models and GPUs. We have developed the first algorithm for dynamically updating strongly connected components in parallel on shared and distributed memory systems. Due to its distributed nature, our algorithm can analyze much larger networks than previously possible. We have also applied our template to updating single source shortest paths. We compared our results with state-of-art parallel graph analysis softwares like Galois and Gunrock and demonstrated that our algorithm is much faster.
As part of our experiments we observed that depending on the size and types of changed edge sets, sometimes updating can be more expensive than recomputing. To take this into account, we also developed an adaptive algorithm for deciding when to use dynamic updates and when to use recomputing
[The work on SSSP on different templates is in preparation for a journal submission.]
[The work on SCC is  in preparation for submission to IEEE Big Data Conference.]
[The work on adaptive algorithms is  in preparation for submission to SC IAAA workshop.]

We investigate the planarity property in network models of protein complexes. We hypothesize that complexes represented as PPI subgraphs will tend to be planar, reflecting the actual physical interface and limits of components in the complex. When testing the planarity of known complex subgraphs in S. cerevisiae and selected mammalian PPIs, we found that a majority of validated complexes possess this planar property. Our  results provide a new quantitative and biologically motivated measure of real protein complexes in the network model, important for the development of future complex-finding algorithms in PPIs. Accounting for this property paves the way to new means for discovering new protein complexes and uncovering the functionality of unknown or novel proteins.
[This work is published in the ICCS 2020 conference.]

We proposed a novel method which we call the Probabilistic Infection Model (PIM). Our model gives an improved resolution of transitions between states, and allows for a more comprehensive view of outbreak dynamics at the individual level. Moreover, by using a probabilistic approach, our model gives a representative understanding of the overall trajectories of simulated outbreaks without the need for numerous (order of hundreds) of repeated Monte Carlo simulations.
We simulated our model over a contact network constructed using registration data of university students. We model three diseases; measles and two strains of influenza. We compare the results obtained by PIM with those obtained by simulating stochastic SEIR models over the same the contact network. The results demonstrate that the PIM can successfully replicate the averaged results from numerous simulations of a stochastic model in a single deterministic simulation.
[This work is published in the ICCS 2020 conference and was awarded the Best Paper Award]


In the IoT-based ubiquitous computing platforms, due to resource limitations of wireless IoT devices (e.g., sensors), an important consideration in designing efficient solutions is optimize the resource (including energy) usage while executing tasks within a specific deadline. Assuming edge, fog, and cloud computing layers, we derived analytically the total delay and energy consumption for heterogeneous task execution with deadline constraints. We experimentally validated our approach by demonstrating the impact of data size, network topology changes, deadline, and sensor characteristics on the energy consumption, delay, and accuracy of the proposed solutions.
[This work is published in the IEEE Transactions on Network and Service Management.]

Another work dealt with heterogeneous IoT networks supporting diverse task demands with different priorities. Our specific goal was to maximize the task throughput of an IoT-enabled wireless network  under limited communication and computational resources. To this end, we propose an efficient two-stage solution based on multi-graph-coloring. We analyzed  the computational complexity of our algorithm, and proved its correctness. Experimental results demonstrated the effectiveness of the proposed algorithm in comparison with state-of-the-art approaches in the literature.
[A preliminary version of this work was published in IEEE SMARTCOMP 2019 conference and a substantially extended version is currently under revision in a special issue of  the Pervasive and Mobile Computing journal.] 

Online Social Networks (OSNs) generate a massive volume of data that must be analyzed while preserving user privacy. Leveraging limited local social network topological properties, we developed effective and efficient search techniques for OSNs, in particular to discover the connectivity of a group of target users from the perspective of a third-party analyst who does not have full access to the network. Our proposed searching techniques demand only a few queries for discovering the connectivity. Extensive experiments on both real-world and synthetic data sets demonstrate the effectiveness of incorporating topological properties of social networks into searching the OSNs. Additionally, our distributed techniques perform very well compared to the centralized detection algorithm that assumes the availability of the entire data set.
[This work is published in Online Social Networks and Media, 2020.]
