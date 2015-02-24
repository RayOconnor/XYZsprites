# XYZsprites
Create a system for printing sprites to a screen based on their X, Y, and Z coordinates.  The resulting image should have some offset to show distence.  Images should also scale. Images with a farther away Z should appear smaller.

for example: a square1 image has an x = 0, y = 0, z = 0,
               square2 image has an x = 0, y = 0, z = 400.
               
normally printing this image with their respective x and y coordinates would place the images on top of each other, but square2 
is 400 pixels away so it should be offset and smaller


   |       |                          |
   |       |                          |
   |       |                          |    |
   |       |                          |    |
   |       | square2                  |    |
   |       |__                        |    |
   |   x=0 |__|_______________________|x=400
   |      /                           \    |
   |     /                             \   |
   |____/                               \  |
   |    | square2                        \ |
x=0|____|_________________________________\|x=400
