# Convex-Hull-Chans-Alg
Implementation of Chan's Algorithm for discovering the convex hull of a point cloud in two dimensions. 

This program was developed to satisfy requirements for the course:
Computational and Discrete Geoemtry (MATH 380) at the University of San Diego. 

The subroutines: myGrahamScan and GiftWrapping were taken/modified from existing 
subroutines posted on GitHub by Rodolfo Ferro, https://github.com/RodolfoFerro

The primary purpose of the program is to return/plot the convex hull of a 2D point cloud
as an exhibit of 'Chan's Algorithm' which involves the graham-scanning of subsets of 
the point cloud, and then gift-wrapping the subsets. 

See: https://en.wikipedia.org/wiki/Chan%27s_algorithm

Opprotunities for future work:
1. make the program robust with respect to points in degenerate position.
2. stabilize the program with respect to very small point sets. 
3. offer more options for point clouds besides random.uniform and random.normal
