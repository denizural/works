## Modelling Complex Urban Networks:
---
* Using proximity graphs and network analysis to investigate the long range relations between urban clusters. Global Urban Footprint (GUF) from DLR is processed processed with urban clustering algorithm and the resulting clusters are transformed into networks such as Delaunay triangulation and Relative Neighborhood Graph (RNG).

* **belgium_delaunay.png:** Delaunay triangulation of the cluster points of Belgium

* **belgium_rng.png:** Corresponding RNG

* **cluster_percolation_animation.gif:** animation of all urban pixels vs 4 largest cluster sizes with respect to different clustering thresholds

* **clusters_belgium_2.png:** Cluster sizes plotted on a map

* **delaunay_rng_animation.gif:** animation of the Delaunay triangulation and the corresponding RNG with respect to different clustering thresholds.

* **finding_edge_neighbors_algorithm_test.png:** output of the edge-based neighbor finding algorithm in a random set of points

* **finding_vertex_neighbors_algorithm_test.png:** output of the vertex-based neighbor finding algorithm in a random set of points

* **nonvectorized_vs_vectorized_speed.png:** optimization of the fluctuation computation code

* **rng_10240_r_package_bugs_detected.png:** the bug I discovered in the R package that can be downloaded from CRAN.

* **rng_10240_my_rng_bug_free.png:**  I developed an optimized and bug-free version of this RNG algorithm

* **rng_speed_comparison.png:** It is also much faster compared to the R version and original RNG algorithm (O(n<sup>3</sup>) complexity). On 10'000 nodes, it runs 150 times faster than the R version.

  
  
  








