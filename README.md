# Shapehull

The repo contains the implementation (executable) of the paper, Jiju Peethambaran, Ramanathan Muthuganapathy, "Reconstruction of Water-tight Surfaces through Delaunay Sculpting", Computer Aided Design, 2015.

The software provides a Qt based interface to load the point set in .xyz format and displays the resultant surface when the algorithm is run.
It also provides the computational time incurred in different stages of the algorithm. We have provided a few input data in .xyz format which the users may try out. 

Abstract:
Given a finite set of points S ⊆ R^2, we define a proximity graph called as shape-hull graph(SHG(S)) that contains all Gabriel edges and a few non-Gabriel edges of Delaunay triangulation of S. For any S, SHG(S) is topologically regular with its boundary (referred to as shape-hull(SH)) homeomorphic to a simple closed curve. We introduce the concept of divergent concavity for simple, closed, planar curves based on the alignment of curves in concave portions and discuss various measures to characterize curves having divergent concavity. Under sufficiently dense sampling, we prove that SH(S), where S is sampled from a divergent concave curve sigma(D), represents a piece-wise linear approximation of sigma(D). We extend this result to provide a sculpting algorithm for closed surface reconstruction from a set of raw samples. The surface is constructed through a repeated elimination of Delaunay tetrahedra subjected to circumcenter and topological constraints. Theoretically, we justify our algorithm by establishing a topological guarantee on the 3D shape-hull with the help of topological rules. We demonstrate the effectiveness of our approach with experimental results on models with sharp features and sparsely distributed point clouds. Compared to existing sculpting approaches for surface reconstruction that require either a parameter tuning or several stages, our approach is simple, non-parametric, single stage and reconstructs topologically correct piece-wise linear approximation for divergent concave surfaces.

Bibtex
@article{Peethambaran201562,
title = "Reconstruction of water-tight surfaces through Delaunay sculpting ",
journal = "Computer-Aided Design ",
volume = "58",
pages = "62 - 72",
year = "2015",
note = "Solid and Physical Modeling 2014 ",
author = "Jiju Peethambaran and Ramanathan Muthuganapathy",
}


