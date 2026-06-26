# Ray Tracer Implementation

`author gh: @aravjuneja`

course credit: `https://raytracing.github.io/books/RayTracingInOneWeekend.html`

This implementation is for my own learning of how ray tracing works.

The rest of this md file will contain any notes that i may decide are important as  i implement. 

## NOTES 

### Chapter 2 - PPM: Portable Pixmap 
super basic uncompressed image file format that stores an image as plain pixel data, listing the rgb color values for every pixel in order. its part of the ntpbm format family.

[PPM EXAMPLE](CH2_ppm/ppm_example.cpp)

This file contains an example of PPM image generation.

the main takeaway is that ppm is a way to store images as plain text files and that we use it because it is absurdly easy to write and interpret since it is just a plain text file. 

### Chapter 3 - The vec3 class 
Almost all graphics programs have some class for storing geometric vectors and colors. In many systems these vectors are '4D'

They store a 3d position plus a homogeneous coordinate for geometry, or RGB plus an alpha transparency component for colors. 

The vec3 header filed defined in the course is provided [here](CH3_vec3.h)

implementation memorization does not seem neccesary, just understand how to use the functions. 




