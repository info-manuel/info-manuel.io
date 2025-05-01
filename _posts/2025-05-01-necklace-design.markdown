---
layout: post
title:  "Necklace design"
date:   2025-05-01 10:00:49 +0200
categories: jekyll update
---

# Project Necklace

I want to create a handmade gift for my wife: a necklace that securely holds a coin without damaging it (e.g., by drilling a hole or soldering a hook).

Here is the design plan I believe will succeed:

![Project Schema](/assets/images/Project-schema.png)

I’ve outlined the steps I’ll follow. Step 1 is the conceptual schematic. To allow the coin to be removable, the container must be separable into two parts. I developed this design:

![Full-Design-Constrained](/assets/images/Full-Design-Constrained.png)

*Drawn in [ExcaliDraw](https://excalidraw.com)*

In this design the first piece will hold the coin from one face and the second piece will hold the coin from the other face, a groove will secure one part of the coin from above and a rivet will secure it from below.

* Coin dimensions: Diameter 27mm, thickness 2.1 mm.

After learning [FreeCad](https://www.freecad.org), I modeled both parts as shown below:

![3d_part1](/assets/images/3d_part1.png)
![3d_part1](/assets/images/3d_part2.png)

You will notice two key differences against the original design:

1. The pin on the first piece, which fits into the groove of the second, is not centered but xtends to the edges.
2. There are no holes.

These changes simplify casting. It’s easier to create a solid object and later file excess material or drill holes than to cast a mold with complex, small geometries.

**Recommendation: Simplify the Z-axis geometry in the mold to increase the likelihood of a successful cast!.**

.... Lets see how the 3d prints turns out (it will continue..) ...
