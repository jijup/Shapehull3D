# Shapehull
Delaunay sculpting for 3D surface reconstruction

## Introduction
The repo contains the implementation(exe) of the paper, Jiju Peethambaran and Ramanathan Muthuganapathy, "[Reconstruction of Water-tight Surfaces through Delaunay Sculpting](https://www.sciencedirect.com/science/article/pii/S0010448514001900)", Computer Aided Design, 2015.
The software provides a Qt based interface to load point clouds of geometric models and display the resultant triangular mesh generted by the shape-hull algorithm. The algorithm is implemented using the geometric predicates available in [CGAL](https://www.cgal.org/project.html)(Computational Geometry Algorithms Library) 

## Abstract

Given a finite set of points S ⊆ R^2, we define a proximity graph called as shape-hull graph(SHG(S)) that contains all Gabriel edges and a few non-Gabriel edges of Delaunay triangulation of S. For any S, SHG(S) is topologically regular with its boundary (referred to as shape-hull(SH)) homeomorphic to a simple closed curve. We introduce the concept of divergent concavity for simple, closed, planar curves based on the alignment of curves in concave portions and discuss various measures to characterize curves having divergent concavity. Under sufficiently dense sampling, we prove that SH(S), where S is sampled from a divergent concave curve sigma(D), represents a piece-wise linear approximation of sigma(D). We extend this result to provide a sculpting algorithm for closed surface reconstruction from a set of raw samples. The surface is constructed through a repeated elimination of Delaunay tetrahedra subjected to circumcenter and topological constraints. Theoretically, we justify our algorithm by establishing a topological guarantee on the 3D shape-hull with the help of topological rules. We demonstrate the effectiveness of our approach with experimental results on models with sharp features and sparsely distributed point clouds. Compared to existing sculpting approaches for surface reconstruction that require either a parameter tuning or several stages, our approach is simple, non-parametric, single stage and reconstructs topologically correct piece-wise linear approximation for divergent concave surfaces.

## Bibtex

@article{Peethambaran201562,
title = "Reconstruction of water-tight surfaces through Delaunay sculpting ",
journal = "Computer-Aided Design ",
volume = "58",
pages = "62 - 72",
year = "2015",
note = "Solid and Physical Modeling 2014 ",
author = "Jiju Peethambaran and Ramanathan Muthuganapathy",
}

## Data

A few input data used in the paper are taken from [AIM@SHAPE](http://visionair.ge.imati.cnr.it/ontologies/shapes/) repository.
