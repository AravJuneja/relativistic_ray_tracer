# Relatavistic Ray Tracer on the GPU  
`author gh: @aravjuneja` 

currently the point of the project is to implement papers/interstellar.pdf for my own learning. i will be diverging from the paper by implementing this in cuda. the paper originally implemented in c++. i will be parallelizing the geodesic integration cross pixels on the gpu.

i realized a little later than i should have that to code a relatavistic ray tracer on the gpu i first need to be able to code a regular ray tracer. my implementation can be found in 'regular_ray_tracer/`.  

notes from `papers/interstellar.pdf`

## dngr: double negative gravitational renderer code

dngr is computer code for making images of what a camera would see in the vicinity of a black hole or wormhole. 

### raytracing
The ray tracing part of dngr produces a map from the celstial sphere to the camera's local sky. 



