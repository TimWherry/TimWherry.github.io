---
layout: post
title: "You're up and running!"
published: true
---


Hello World
=====
Just spent 3 hours fighting with figuring out how to sample a texture from a pixel shader. Finally found someone who got just as lost as I was. It turns out, over time, the function signature code base kinda fell apart on some platforms, as in, if you leave off one of the first parameters, it would push the rest of the registries forward which in turn would cause invalid data and nothing would get passed into the pixel shader(well for me at least). Leaving off later parameters has no downside.

Here's a good [link](http://www.software7.com/blog/pitfalls-when-developing-hlsl-shader/) describing it. 

I'm planning out a tutorial series that will hopefully shed more light into it for whoever else hits the same pitfall.