---
layout: default
lightbox: true
---

...updating page

Just some stuff I worked on.

All of the following projects are(were) developed as personal projects, including the
ones that started at work, in some cases the code and documents are not yet publicly available
because:

* I did not have time OR
* I am waiting until I publish a paper/article  OR
* I need to make sure I can legally opensource the project under the proper license. 

#Molekel

![](pics/molekel/bannerbw.jpg)

Multiplatform molecular visualization/analysis program.

Checkout the presentation given(upon invitation) at the _American Chemical Society_ as well 
as gallery and videos on the official website.

[Website](http://molekel.cscs.ch)

This project has been discontinued in 2010, but it is still being downloaded at
a rate of about 1k downloads per months.

I am now working on my own at a very slow pace to build a replacement for the program with a
brand new rendering engine and trying to include some of the many feature requests received
from users, including scripting, plugins and the ability to directly interface with the computing infrastructure (both HPC and grid/cloud).

I am expectig to release a 1.0 version by fall/winter 2013 under a BSD-like license.

#Crystal Viewer

![](pics/crystal_viewer/bannerbw.jpg)

Real-time visualizaiton of large (multi-million atoms) chemical compounds.
Features:

* color coding of scalar fields
* picking of individual atoms
* support for symmetry and replication of unit cell 

Discontinued; originally developed with another researcher and in collaboration with 
_EMPA_(material science lab).

#Interactive visualization for quantum chemistry

![](pics/funorbitals/bannerbw.jpg)

Research on techniques for analyzing molecules, scalar and vector fields from direct
real-time evaluation of approximate solutions to the Schroedinger equation.

Paper, articles and poster published.

#Graphics kernel for interactive molecular modeling

Some features:

* precomputed ambient occlusion of molecular surfaces(SES & SAS).
* real-time ambient occlusion of animated molecules
* order-correct transparency to mix surfaces with atoms and bonds
* volume-rendering of scalar fields, orbitals & density matrix
* real-time rendering of multi-million atom datasets 
* application of user defined programmable shaders to any graphical object
* high quality output suitable for publications
* distributed version through equalizer graphics
* novel approach to distributed rendering and compositing based on RDMA and
  direct intra- and inter-node GPU to GPU transfer
* fast (multithreaded and GPU-enabled) K-d tree implementation 

#(Reverse) global illumination

![](pics/rglobal_illum/bannerbw.jpg)

Research on how to infer properties of 3d shapes from global illumination-related properties.
Cannot disclose more at this time. 

#Real-time raytracing of quadric surfaces

Implementation of a real-time ray-tracing engine using point and quadrangles
as proxy geometry for quadric primitives.

OpenSceneGraph code available GitHub, temporarily hosted in a private project.

#OpenBabel

Contributed code to parse and interpret quantum chemistry data formats.

#ParaView/VTK

Contributed real-time raytracing code to particle renderer. 

#Parsley

Parsing framework originally developed to exctract and interpret data from results
of quantum chemistry/physics computations.

[Hosted on GitHub](http://github.com/candycode/parsley)

#Loco.js

JavaScript/C++ application framework: Develop multiplatform desktop applications
with CoffeeScript/JavaScript/Python/Scheme...anything that compiles to
JavaScript, together with Knockout, jQuery(UI) or any of your favorite JS framework.

Implement modules as C++ loadable objects and use a scripting language as glue/controller.

Distribute apps as a single executable or a player application which downloads
objects on the fly.

Network(w/ SSL), services provided with configurable resource access control.

Full integration with WebKit: expose any object to WebKit context.

[Hosted on GitHub](http://locojs.net)

#QLua

Make any QObject-derived class instance available to Lua; connect:

* QObject signals to QObject slots
* QObject signals to Lua callbacks

directly acces QObject properties and invokable methods from Lua.

[Hosted on GitHub](http://github.com/candycode/qlua)

#Free Dimensions

This is a program from the previous century. It started as  a proof of concept for a distributed CAD/3D modeler on SGI hardware and was lately rewritten to work on Windows around 1998, used mainly as a workbench for experimenting with computer graphics algorithms, OpenGL and Windows GUI programming. I also built it to generate (animated) data for RenderMan compliant renderers, unfortunately I never had access to the real thing so the shader interface only works with BMRT.

Free Dimensions can generate any sort of geometry from F-Rep with CSG and blending to NURBS and has limited support for animation. It can also generate depth maps and perform preview of applied shadows and light maps (all done painfully slowly on the CPU). Last but not least it can export a 3D world to Windows, X, and Java3D source code.

It turns out that the program (together with BMRT 2.6) does work on Windows 7 (although with issues with resizing and when using multi-level undo/redo) including the scripting interface and some networking features.

#sMesh

Subdivide with Catmull-Clark, Loop and other techniques and decimate high polygonal count
meshes.

...to be continued
