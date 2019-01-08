# Shader Graph Example Library

![Player Lineup](https://i.imgur.com/kASJxN1.png)

**Description**

This project is a library of different custom shaders created using [Unity 2018.1's Shader Graph feature](https://forum.unity.com/threads/feedback-wanted-shader-graph.511960/). All of the shaders are compatible for the [Lightweight Scriptable Render Pipeline](https://forum.unity.com/threads/feedback-wanted-scriptable-render-pipelines.470095/).

These Shader Graphs are provided as-is; so your mileage may vary! You are more than welcome to modify/change/extract/use any of the examples.

The current list of Shader Graphs included:

Mesh Renderer:
- Colored Rim
- Scrolling Texture Overlay
- Colored Gradient
- Sliced (Inspired by 
[Sliced Shader in Surface Shader Documentation](https://docs.unity3d.com/Manual/SL-SurfaceShaderExamples.html))
- Snow
- Toon Ramp (No Lighting Data so I used a manual Vector 3 property for Light Direction)
- Texture Dissolve (With Colored Edge)
- Hologram (Using Screen Position)
- Colored Ghost Noise
- Phase In And Out (Split with a Colored Edge)

Particles:
- Basic Solid Circle
- Basic Soft Circle
- Spiral

Sprites:
- Basic Sprite (Simple)
- Basic Sprite (Sub Graph)
- Hologram Overlay
- Glowing
- Gradient
- Normal Map

Procedural:
- Shape Ellipse
- Shape Rectangle
- Shape Rounded Rectangle
- Shape Polygon
- Shape Ring
- Shape Multiple
- Shape Multiple Different Colors
- Shape Inverted
- Shape Tiled 
- UV Offset Ping Pong
- UV Auto Rotation
- UV Auto Scroll
- UV Auto Orbit
- UV Warped
- UV Warped Ping Pong
- UV Spherized Ping Pong
- UV Shape Scale Ping Pong
- UV Auto Transforms Combined
- Color Ping Pong
- Color Random Flicker
- Color Linear Gradient
- Color Radial Gradient
- Color Split
- Color Split Ping Pong
- Color Soft Split
- Color Soft Split Ping Pong
- Pattern Stripes
- Pattern Checkerboard
- Pattern Shatter
- Pattern Shatter Auto Rotation
- Pattern Rings
- Pattern Rings Auto Scroll
- Pattern Spiral
- Pattern Spiral Auto Rotation
- Pattern Fish Eye
- Noise Color Blend
- Noise Color Blend Auto Scroll
- Noise Color Split
- Noise Color Split Ping Pong
- Noise Color Split Waves
- Noise Circle
- Noise Circle Auto Scroll
- Noise Voronoi
- Noise Voronoi Shuffle

**Software Requirement**

Required:
<<<<<<< HEAD
Unity 2018.1.5

Package: com.unity.render-pipelines.lightweight: 1.1.10-preview
=======
Unity 2018.2b7

Package: com.unity.render-pipelines.lightweight: 2.0.3-preview
>>>>>>> 2018.2



**Known Issues**

There is sometimes an issue when opening the project for the first time that textures set in the Material Inspector aren't being applied properly; the current 'fix' is to open the related Shader Graph, click the "Save' button and the Material should update. :)


**Contact**

if you have any issues & requests for the Shader Graph Example Library; please reach out to Andy Touch:
- Email: andyt[at]unity3d.com
- Twitter: [@andytouch](https://twitter.com/andytouch)

And please get in touch if you use any of the examples for anything! :)
