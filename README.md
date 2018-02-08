# Shader Graph Example Library

![Player Lineup](https://i.imgur.com/kASJxN1.png)

**Description**

This project is a library of different custom shaders created using [Unity 2018.1's Shader Graph feature](https://forum.unity.com/threads/feedback-wanted-shader-graph.511960/). All of the shaders are compatible for the [Lightweight Scriptable Render Pipeline](https://forum.unity.com/threads/feedback-wanted-scriptable-render-pipelines.470095/).

These Shader Graphs are provided as-is; so your mileage may vary! You are more than welcome to modify/change/extract/use any of the examples.

The current list of Shader Graphs included:

Any Mesh:
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



**Software Requirement**

Required: [Unity 2018.1b4](https://unity3d.com/unity/beta/unity2018.1.0b4)


**Known Issues**

There is sometimes an issue when opening the project for the first time that textures set in the Material Inspector aren't being applied properly; the current 'fix' is to open the related Shader Graph, click the "Save' button and the Material should update. :)


**Contact**

if you have any issues & requests for the Shader Graph Example Library; please reach out to Andy Touch:
- Email: andyt[at]unity3d.com
- Twitter: [@andytouch](https://twitter.com/andytouch)

And please get in touch if you use any of the examples for anything! :)
