# ray_tracer
## introduction 
this repo implements a very primitive ray tracer for a specific scene and is based on the book by peter shirley **ray tracing in one weekend**

## the problem
It allows users to create images using ray tracing techniques, particularly path tracing. Path tracing simulates the behavior of light in a scene, resulting in realistic lighting effects, such as shadows, reflections, and refractions. This tool provides a simple yet effective way for users to generate images with high-quality lighting effects, suitable for various applications like computer graphics, animation, and visual effects in movies and video games.

### the vec3 class
Almost all graphics programs have some class(es) for storing geometric vectors and colors. In many systems these vectors are 4D (3D position plus a homogeneous coordinate for geometry, or RGB plus an alpha transparency component for colors). For our purposes, three coordinates suffice.
it implements the functionality needed to perform addition of vectors, and cross products and dot products and any other operation that can be performed on a vector mathematically. 

### the color class 
implements the vector class to enable writing to a single a pixel a color value. a requirement that should be met while implementing the write color function is making the second function argument an auto type. using int causes weird behaviour. 

### the ray class 
in physics a ray of light can be defenied as a an imaginary line from a light source or reflected that travels in straight line(at least in classical physics), in our cleass we implement members such as the rays origin and direction and associate methods to get the coroordinates of a ray at a point ray::at(t). this method returns a point on the ray at a distance t from the origin 



