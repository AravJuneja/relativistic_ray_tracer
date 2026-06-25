# Relatavistic Ray Tracer on the GPU  
`author gh: @aravjuneja` 

currently the point of the project is to implement papers/interstellar.pdf for my own learning in cuda. the paper originally implemented in c++ but i plan to do it in cuda so i will be parallelizing the geodesic integration across pixels on the gpu. 


Notes from `papers/interstellar.pdf`

## DNGR: Double Negative Gravitational Renderer Code

DNGR is computer code for making images of what a camera would see in the vicinity of a black holw or wormhole. 

### Raytracing
The ray tracing part of
