# ray_tracer
## introduction 
this repo implements a very primitive ray tracer for a specific scene and is based on the book ray tracing in one weekend. 

### the vec3 class
Almost all graphics programs have some class(es) for storing geometric vectors and colors. In many systems these vectors are 4D (3D position plus a homogeneous coordinate for geometry, or RGB plus an alpha transparency component for colors). For our purposes, three coordinates suffice.
it implements the functionality needed to perform addition of vectors, and cross products and dot products and any other operation that can be performed on a vector mathematically. 

### the color class 
implements the vector class to enable writing to a single a pixel a color value. 