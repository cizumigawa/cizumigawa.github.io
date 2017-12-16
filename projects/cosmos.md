---
layout: project
type: project
image: images/cosmos.png
title: COSMOS - ADCS Library
permalink: projects/cosmos
date: 2017
labels:
  - C++
  - Qt
  - Flight Software
summary: A co-developed library for ADCS operations in flight software.
---

# COSMOS
COSMOS (Comprehensive Open-architecture Solution for Mission Operations Systems) is a C++ framework which provides software support for many different aspects of satellite flight control: flight software, ground station tools, testbed tools, etc. Although the [COSMOS Project](http://cosmos-project.org/) is currently built with mostly C++ and object-oriented programming concepts, it is quickly evolving to include Python and JavaScript libraries.

# ADCS
The ADCS (Attitude Determination and Control System) is a device which monitors and controls satellite movement in space.  Equipped with torque rods, reaction wheels, a star tracker, gyros, nadir sensors, and sun sensors, the ADCS is an important and complicated aspect of all satellites; however, in order for the COSMOS framework to communicate with this device, a library of ADCS commands had to be developed.  As such, this project focused on creating the command and telemetry library for the ADCS (specifically, the CubeSpace CubeADCS) in order for COSMOS to communicate properly with the ADCS.  

While this library was co-developed with two other developers, my contribution to this project was the foundation for the library.
