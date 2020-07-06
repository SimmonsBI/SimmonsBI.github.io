---
layout: page
title: Software
permalink: /software/
---

### BMOTIF

bmotif is software for motif analyses of bipartite networks. It can count occurrences of motifs in bipartite networks, as well as the number of times each node or link appears in each unique node or link position within motifs (a node or link’s structural role). bmotif also supports weighted networks and can calculate the mean weight of motifs, as well as the standard deviation of motifs mean weights. Various weighted node and link position measures are also available. bmotif is primarily an R package, but core functionality is also available in MATLAB and Python.

Developed in collaboration with Riccardo Di Clemente, Maybritt Schillinger and Michelle Sweering (alphabetical order).

[Paper](https://doi.org/10.1111/2041-210X.13149); [CRAN](https://cran.r-project.org/package=bmotif); [Github R](https://github.com/SimmonsBI/bmotif); [Github MATLAB](https://github.com/SimmonsBI/bmotif-matlab); [Github Python](https://github.com/SimmonsBI/bmotif-python)

### MAXNODF

maxnodf is software in R for calculating the maximum nestedness (measured as NODF) that can be achieved in a bipartite network with a given number of rows, columns and links, subject to the constraint that all nodes must have at least one link.  This allows nestedness values to be normalised as NODF/max(NODF) following Song et al (2017). To control for connectance and network size, Song et al. (2017) suggest an additional normalisation that can be used: (NODF/max(NODF))/(C * log(S)) where C is the network connectance and S is the geometric mean of the number of plants and pollinators in the network. maxnodf features three different algorithms: a greedy algorithm that is fast but finds lower quality solutions; a greedy algorithm with hillclimbing that is a bit slower but finds better solutions; and a simulated annealing algorithm that is slowest but finds the best solutions.

Developed in collaboration with Christoph Hoepkke.

[Preprint](https://doi.org/10.1101/2020.03.20.000612); [CRAN](https://cran.r-project.org/package=maxnodf); [Github R](https://github.com/christophhoeppke/maxnodf/)

Song, C., Rohr, R.P. and Saavedra, S., 2017. Why are some plant–pollinator networks more nested than others?. Journal of Animal Ecology, 86(6), pp.1417-1424.
