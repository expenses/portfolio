+++
title = "Ashley Ruglys' CV"
+++
# Ashley Ruglys
Graphics Programmer

## Experience

### MeetKai Inc.  
Consulting Graphics Programmer  
June 2022 - Present (7 months)  
Berlin, Germany

I am working on an experimental rendering engine named Superconductor that targets both native binaries and the web via WebAssembly and WebGL 2.
The challenge of writing something that managed to be flexible and performant
while still dealing with the strict limitations of WebGL 2 has been very fullfilling.

![](/rendered.png)

Most recently I have been working on a Global Illumination solution inspired by
the work done in the Frostbite engine (See Precomputed Global Illumination
in Frostbite, GDC 2018) that uses the Mitsuba renderer to bake out both
lightmaps and light volumes consisting of L1 spherical harmonics. This work
has involved a ton of learning and writing code across a variety of domains
including scripting Blender (initially to create large arrays of cameras, later
to run xatlas to pack UVs), writing massively parallel code for Mitsuba that
spawns wavefronts with billons of threads and Rust code for pre- and post-
processing.

![](/gi.png)

### Parity Technologies
Software Engineer  
November 2019 - August 2021 (1 year 10 months)  
Berlin, Germany

* Worked on all aspects of the Rust backend.
* Helped to ship an in-browser wasm node.

## Education
### Victoria University of Wellington
Computer Science · (2017 - 2018)