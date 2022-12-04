---
title: "2D Physics Engine"
layout: post
# date: 2016-01-23 22:10
tag:
- cpp
- c++
- physics engine
- engine
image: https://sergiokopplin.github.io/indigo/assets/images/jekyll-logo-light-solid.png
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
description: "A simple 2D Physics library written in C++."
category: project
author: kalpitborkar
externalLink: false
---

# 2D-Physics-Engine
A simple 2D Physics library written in C++.\
Check the github repository here: [2D Physics Engine](https://github.com/kalpitborkar/2D-Physics-Engine)

## Structure
### Particle
A `Particle` is an object representing a physical particle in `Environment`.<br />
A `Particle` has a mass, speed, position, size, elasticity and other properties.<br />
### Spring
A `Spring` is an object representing a physical spring in `Environment`.<br />
A `Spring` has two `Particles` attached to it's either ends.  A `Spring` has length and strength properties.<br />
### Environment
The `Environment` class represents the environment in which the simulation is occuring.<br />
An `Environment` holds multiple `Particle` and `Spring` objects during simulation. <br />

## License
Distributed under the MIT License. See `LICENSE.md` for more information.

## References
- https://www.petercollingridge.co.uk/tutorials/pygame-physics-simulation/
- https://developer.ibm.com/tutorials/wa-build2dphysicsengine/