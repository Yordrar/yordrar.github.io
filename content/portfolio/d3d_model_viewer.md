+++
categories = ["graphics", "directx"]
coders = []
date = 2020-07-10T00:00:00Z
description = "A Direct3D model viewer"
github = ["https://github.com/yordrar/d3d_model_viewer"]
image = "images/portfolio/model_viewer/dragon.png"
title = "Direct3D model viewer"
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

This is a simple OBJ model viewer I made with DirectX 11 and Dear ImGui with the purpose of learning both of them.

It can load an OBJ mesh file and visualize it.
You can also move the camera around in a Blender-like fashion.
It can also visualize the vertex normals, as well as showing the mesh in wireframe or solid mode.

It is still not finished though, I plan to add some other features such ass different visualization options and shaders.

## Images

!["dragon"](../../images/portfolio/model_viewer/dragon.png "Stanford dragon")

A Stanford dragon being visualized.

!["dragon_normals"](../../images/portfolio/model_viewer/dragon_normals.png "Normals")

The vertex normals of the dragon being visualized.

!["dragon_wireframe"](../../images/portfolio/model_viewer/dragon_wireframe.png "Wireframe")

The dragon in wireframe mode.

!["file_chooser"](../../images/portfolio/model_viewer/file_chooser.png "ImGui file chooser")

Aiekick's [file chooser](https://github.com/aiekick/ImGuiFileDialog) integrated with Dear ImGui.

Visit the github page for this project to see the code (link is up top).