---
layout: page
title: Future Research Ideas
permalink: /future-research-ideas/
description: Notes on problems, directions, and questions I want to explore.
nav: true
nav_order: 4
---

This page collects research directions I want to develop further.

## 1. From Selection to Generation: Restoring the Frame of Reference for Collaborative Spatial Grounding in Free Space

Establishing a shared Frame of Reference (FoR) is critical for spatial reference in human-robot collaboration. However, referencing a point or region in free space is structurally ambiguous because the absence of a functional relatum (reference object) causes the FoR to collapse. Current selection-based approaches cannot resolve this relatum-less condition, as they treat an essentially ill-posed problem as an estimation task. To resolve this, this work proposes a framework where the robot actively generates and visualizes an intrinsic relatum, such as virtual anchors or grids, using augmented reality. This transforms ambiguous free-space descriptions into well-defined reference tasks. It enables precise and effective bidirectional negotiation for spatial reference. Furthermore, this work highlights appropriateness as a critical design dimension to evaluate how well the generated cues align with human perception and task context. Overall, this direction argues for a shift from passive selection to active generation in spatial grounding.

Video: [YouTube demo](https://youtu.be/sm5bPqOymZk)

## 2. Toward City-scale Spatial Representations for Human-Robot Communication

This idea extends my IEEE VR 2026 poster work on voxel-based surface grid coordinates for outdoor mobile augmented reality toward city-scale spatial representations.

In the poster, I proposed a voxel-based surface grid coordinate system that bridges relative human spatial descriptions and absolute geographic coordinates. By voxelizing reference object models obtained from 3D maps and defining grids on their surfaces, the system creates a surface-based index for placement while preserving correspondence with latitude, longitude, and altitude. Quantitative outdoor experiments and a pilot user study showed that these surface grids and visual cues can support spatial perception at different levels.

As a future direction, I want to expand this idea from object- or building-level reference to city-scale representations. The broader goal is to study how large-scale outdoor environments can be structured into representations that remain compatible with human spatial reasoning while still being computationally grounded. This could support more natural spatial communication with robots and intelligent systems in urban environments, where people refer to locations, surfaces, regions, and landmarks using relative and multi-scale descriptions rather than raw coordinates.

Some of the questions I want to explore are:

- how city-scale environments can be decomposed into human-understandable spatial units
- how surface-based or region-based representations can remain linked to geographic coordinates
- how multi-scale references can support both coarse navigation and fine-grained placement
- how these representations can support communication between humans and robots in real outdoor settings
