# Tabu search on Travelling Salesman Problem
Implementation of Tabu Search algorithm combined with 2-opt and Hill climbing on Travelling Salesman Problem

Sample datasets are given with their ground-truth.
Dataset format is like
nodefrom nodeto weight
1 2 5
1 3 10
2 4 3

if you want to use undirectional edges you can write reverse edge also. That works.
e.g.

1 2 5
2 1 5  


2-opt is not the original implementation here, it is more like randomized version of it to put pseudo-random shuffling.