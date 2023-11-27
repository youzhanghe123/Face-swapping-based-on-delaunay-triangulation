# Face-swapping-based-on-delaunay-triangulation
In this project, I apply delaunay triangulation algorithm to swap source face to target face.

The first step is using Dlib face detector to detect faces in the source and target image.

The second step is building delaunay triangules for source and target face.

The third step is building convex hulls for source and target image.

The fourth step is wraping delaunay triangules of the source image to the target image.

The fifth step is smoothing the swapped face to make it more natural. 
