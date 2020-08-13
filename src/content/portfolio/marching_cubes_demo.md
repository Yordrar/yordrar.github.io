+++
categories = ["graphics", "directx"]
coders = []
date = 2020-08-13T00:00:00Z
description = "An implementation of the Marching Cubes algorithm"
github = ["https://github.com/yordrar/marching-cubes-demo"]
image = "images/portfolio/marching_cubes_demo/sea.png"
title = "Marching Cubes"
type = "post"
[[tech]]
logo = "../../images/skills/cplusplus.png"
name = "C++ 11"
[[tech]]
logo = "../../images/skills/directx.png"
name = "DirectX 11"
[[tech]]
logo = "../../images/skills/dear_imgui.png"
name = "Dear ImGui"
url = "https://github.com/ocornut/imgui"
+++

This is a simple demo showcasing the Marching Cubes algorithm.

It is a really neat algorithm for procedurally generating meshes, specially terrain.
I plan to eventually make a simple terrain editor based on this algorithm generating the mesh via a compute shader.

The GUI was made with the Dear ImGui library, and it allows you to change the grid resolution and cube size, as well as toggling interpolation and changing the mesh color.

I learned the algorithm from the following resources:

[Polygonising a scalar field](http://paulbourke.net/geometry/polygonise/): Article by Paul Bourke.

[Coding Adventure: Marching Cubes](https://www.youtube.com/watch?v=M3iI2l0ltbE): Video by Sebastian Lague.

## Images

!["sea"](../../images/portfolio/marching_cubes_demo/sea.png "sea")

!["mountain"](../../images/portfolio/marching_cubes_demo/mountain.png "mountain")

!["valley"](../../images/portfolio/marching_cubes_demo/valley.png "valley")

Visit the github page for this project to see the code (link is up top).