CMP5359 Computer Graphics Reassessment
Rendering Techniques, RTX On vs RTX Off

Jaydon Annobil
CMP5359 Computer Graphics
2025-26

Project Overview
This project recreates an Outlast bedroom scene using three different rendering techniques from the same camera viewpoint.

The project includes:

- A Blender Cycles render(path traced).
- A C++ software rasteriser.
- A C++ software raytracer.

The aim was to demonstrate real-time graphics, lighting, and rendering techniques while recreating a scene from a video game.

Rasteriser
Contains the C++ software rasteriser project, including:

- OBJ loading
- Perspective projection
- Triangle rasterisation
- Back-face culling
- Image output using LodePNG

Raytracer
Contains the C++ raytracer project, including:

- OBJ model loading
- BVH acceleration
- Lambertian shading
- Phong shading
- Mirror shader support
- Point and directional lighting

Blender
Contains the final '.blend' file used to create the Cycles render.



Rasteriser
- OBJ model loading
- Perspective projection
- Wireframe rendering
- Triangle filling
- Back-face culling
- PNG image output

Raytracer
- Ray-object intersection
- BVH acceleration
- Lambertian shading
- Phong shading
- Point light
- Directional light
- PNG image output

Reference Images
- my own Outlast Trials bedroom 

Models
- Outlast bedroom recreation created in Blender.

Libraries
- Eigen (math library)
- LodePNG (PNG image output)
- nlohmann/json (configuration loading)

This submission was developed as an individual coursework project for CMP5359 Computer Graphics, but overall i found this project very fun, but also very stressful alot of the time. 

Thank You.