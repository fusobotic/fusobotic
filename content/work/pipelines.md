---
title: "Pipelines"
date: 2024-03-29T14:45:11-04:00
draft: false
---

### Realize
![Demo of Realize App](/images/gifs/realize_demo.gif)
*Working at Realize I had to create a unique pipeline for a wide variety of source assets. Every retailer we collaborated with, from IKEA to Target to Wayfair, had a different format. The file types, textures, fidelity and scale of objects changed between and within their catalogues which made for a very challenging workflow. I worked with outsourcers and developed a quality assurance document to make sure the 3D files we received were perfected for use inside our app, with the right texture sizes and mesh density.*

![Realize Pipeline](/images/pipeline_realize.png)

Handling over 5,000 cloud-based assets was difficult but made easier by automating some of the file naming, poly and texture size checking, and origin/transform freezing inside Unity and Blender. I had to write custom Python and C# plugins to accomplish this and even uncovered some bugs in both software while doing so- namely bugs in Blender's .obj exporter and Unity's texture memory management.

### LF Studios

![Realize Workshop](/images/pipeline_lf_extra.jpg)

Working for LF Studios I had a similar challenge in that the movie studios, theme parks, and museums we contracted for provided us with a large variety of file formats. Sometimes we had easy to use .fbx or .obj files but other times we were provided surface files, specialized animation files or in the worst case, partial 3D scanned data. In every scenario we had to clean up the extraneous bits and fill in incomplete portions using ZBrush, Maya, Rhino, Solidworks and Blender. We worked closely with engineers passing mesh, animation and CAD data back and forth on a daily basis. Projects would take months to years to go from 3D concepts to manufactured animatronics and set pieces.

![LF Studios Pipeline](/images/pipeline_lf.png)

### GE

![Vectre Image 1](/images/vectre_1.jpg)

![Vectre Image 1](/images/vectre_2.jpg)

I contracted with Vectre to create Unreal-Engine-based, VR-optimized models of additive metal manufacturing printers and accesories. Using CAD data provided by GE we were able to produce high fidelty models that were used in a VR app that helped factory designers lay out where these machines would go on the production floor. I had to convert extremely dense CAD drawings into mesh data, then UV unwrap and replicate materials according to photos of the actual hardware.

{{< vimeo 307562513 >}}

### Brukel

{{< youtube id="pN7lzQ5R3zM?si=8q9_8jl4qcBPGI4l" >}}

As a lead 3D artist on [Brukel](https://store.steampowered.com/app/1073900/Brukel/) I was tasked with creating a pipeline from scratch. We were given photos as reference from a real location and expected to create AAA quality assets for use in this historical-horror game. We used Unreal for development which meant setting up materials for Physically-Based Rendering before it was a standard. We also used map-packing and automated LODs to make sure the game ran well on all platforms. I was in charge of a team of six entry-level artists and taught them techniques for building game-ready models. This game ultimately won four different game awards and was featured by the Smithsonian Arcade in 2019.

![Brukel Pipeline](/images/pipeline_brukel.png)

