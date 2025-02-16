---
layout: page
title: Projects
permalink: /Projects/
---

#### Modelling Shear-Horizontal waves in a 2D medium [(bibliography)](https://library.seg.org/doi/10.1190/1.1441605).

![photo](/assets/Snapshot_SHwaves.png)

I developed this code based on the performance-portability approach described in my [publication](https://link.springer.com/chapter/10.1007/978-3-031-50684-0_22). In brief, the code is desinged in high-level using C++ to create an abstraction layer, which allows to integrate any number of architecture-specific backends. In this implementation OpenMP and CUDA are the supported backends. The build process is based on CMake. Find instructions for compiling and running a demo of this code in the [repository](https://github.com/ahadji05/SH_waves_2d).
