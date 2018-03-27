# CS488

## Compilation:
  Run the default premake4/make combination to comile the code.
  Then run './A4 <lua filepath>' to start rendering.
  This assignment was build successfully on lab computer gl28.

## Objectives:
  Objective related images are stored in path 'Assets/objs/pics', and animated
  gif is in 'Assets/objs/animation'. The  corresponding lua file for each objective
  is located in 'Assets/objs'. 

  Note that an objective may have more than one image to illustrate the feature, and the 
  lua file may only corresponding to one of the images. Moreover, some features (for example
  motion blur, animation, anti-aliasing) are turned off by default, which requires manually
  change corresponding flag in 'A4.cpp'. Each field in 'A4.cpp' is straitforward and with
  related feature turned on, expected scene will be generated.

  Here is a list of my objectves and the number of images related:
  
    Objective:            # of Images:
    1: Primitives             (2)
    2: CSG                    (4)
    3: Reflection             (1)
    4: Refraction             (4)
    5: Texture Mapping        (1)
    6: Bump Mapping           (5)
    7: Soft Shadow            (3)
    8: Adaptive Anti-aliasing (4)
    9: Motion Blur            (1)
    10: Final Scene           (2)