+++
title = 'A PGAS Memory backend for the OP2 HPC Library'
date = 2023-10-06T15:16:17+02:00
draft = true
+++

_A PGAS memory backend for the OP2 HPC library_ is a Masters group project that I participated in, together with Nick (a great project leader), Nat and Ben. THe purpose of theproject was to implement a new backend, responsible for managing memory and inter-process communication in the OP2 library. OP2 is a domain-specific language, so a library with a partial compilation step, which allows for conducting computations on unstructued meshes, highly optimised for specific platforms, but with single codebase, with many such platforms supported. 

The task that we undertook comprised of porting some parts of the MPI code to GPI, which uses direct reading adn writing to foreign processes' memory instead of the common message passing. My work focused on integrating the new backend with the existing build infrastructure, as well as conducting testing and measuring performance.

The original OP2 website can be accessed here: LINK

Our modified version (a non-stable in-development varsion) is available here: LINK

__Please note that a supported, more official port might be available in due course.__


## Related blog posts
