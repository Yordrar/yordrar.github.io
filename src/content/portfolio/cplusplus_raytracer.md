+++
categories = ["graphics", "raytracing"]
coders = []
date = 2020-07-06T00:00:00Z
description = "A software C++ ray tracer made with no graphics API for my Bachelor's thesis"
github = ["https://github.com/yordrar/thesis-raytracer"]
image = "images/portfolio/raytracer/raytracer.png"
title = "C++ Ray tracer"
type = "post"
[[tech]]
logo = "../../images/skills/cplusplus.png"
name = "C++ 11"
[[tech]]
logo = "../../images/skills/qt.png"
name = "Qt 5"
url = "https://qt.io/"
+++

This is a C++ ray tracer I developed for my Bachelor's thesis.
I developed it with the purpose of learning the foundations of computer graphics and ray tracing.
Because of that, it uses no graphics API, only pure C++ 11.

It supports many rendering features, such as:
- Unbiased Monte Carlo integration of the Rendering Equation via Path tracing
- Global illumination
- Anti-aliasing
- Defocus blur with customizable aperture and focus distance
- Importance sampling via BRDF sampling
- Next event estimation with shadow rays
- Smooth and flat shading
- Diffuse, Crystal, Metal, Blinn-Phong and Emissive materials with parameterizable roughness, metallicity, reflectance and intensity
- Fresnel reflections in diffuse materials
- PBR materials with support for texture maps, normal maps, roughness/glosiness maps, metallicity maps and ambient occlusion maps
- Point lights, area lights, and directional lights
- Image-based Lightning with sphere mapping
- Support for importing multiple asset formats such as OBJ, FBX and PLY via the [Assimp](http://assimp.org/) library.
- Support for saving completed renders in various formats (JPEG, PNG, TIFF, BMP, XBMP, WebP, PPM, PBM, XBM and XPM)
- Editable scene via selecting objects and changing their position and orientation
- Quaternions for representing orientations and rotations
- Blender-like orbital camera

It was initally developed following the great book series "Ray Tracing in One Weekend" by Peter Shirley, although it quickly diverged from it when I added features not present in the books, such as shadow rays, mesh loading and management, PBR materials and image-based lightning with sphere mapping.

## Images

!["cornell_box"](../../images/portfolio/raytracer/raytracer.png "Cornell box")

A classic cornell box with one area light at the ceiling.

!["pbr_materials"](../../images/portfolio/raytracer/pbr_materials.png "PBR materials")

Some PBR materials. From left to right: leather, scratched metal and marble.

!["rusty_metal"](../../images/portfolio/raytracer/rusty_metal.png "Rusty metal PBR")

A rusty metal PBR.

!["emissive_material"](../../images/portfolio/raytracer/emissive_material.png "Emissive material")

A small scene with a sphere that has an emissive material.

Visit the github page for this project to see the code and more images (link is up top).