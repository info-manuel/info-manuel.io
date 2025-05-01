---
layout: post
title:  "Necklace design"
date:   2025-05-01 10:00:49 +0200
categories: jekyll update
---
I want to gift something hand-made to my wife, the idea is to create a neclkace that holds a coin without the need of damaging it (drill a hole/solder a hook) 

This is the diagram I expect will turn in success:
![Project Schema](/assets/images/Project-schema.png)

I have labeled the steps Ill follow, 1. Is the concept Schematic, as I want to be able to extract the coin whenever I like it is important that the container can be open/sepparated in two parts, I came out with this design:
![Full-Design-Constrained](/assets/images/Full-Design-Constrained.png)

*Drawn in [ExcaliDraw](https://excalidraw.com)*

In this design the first piece will hold the coin from one face and the second piece will hold the coin from the other face, a groove will secure one part of the coin from above and a rivet will secure it from below.

* Coin dimensions: Diameter 27mm, thickness 2.1 mm.

After learning some [FreeCad](https://www.freecad.org), I create the models of both parts as shown below:
![3d_part1](/assets/images/3d_part1.png)
![3d_part1](/assets/images/3d_part2.png)

You will notice two main differences against the original design:

1. The pin in the first piece that inserts into the groove of the second is not centered, but it extends to the edges
2. There are no holes

Both are driven by ease of casting reasons, it is easier to create an object like this and then file the excess or drill than to create a mold with that small and difficult geometry.

**Simplify the Z axis geometry in the mold to improve the chances of success!**

.... Lets see how the 3d prints turns out (it will continue..) ....
