---
layout: post-wide
uid: 3dviz_sprint
title: "Camera Color Visualizer"
date: 2023-02-23
categories: project
---

During the second semester of the IMLEX program at UJM, we took the "Real-Time 3D Visualization" course. This course finished with a 3-day "Sprint" where we built a pre-set project. This is the result of that sprint.

The project is built using [Three.js](https://threejs.org/) and javascript. It takes a camera stream from one of the device's webcams and computes an RGB histogram.
Additionally, it visualizes the color distribution in the image with point clouds, in the RGB (input) space, as well as CIExyY and CIELAB.

The code can be found [here](https://github.com/nbieck/3DViz_Sprint), and a live demo is located [here](/IMLEX/3DViz/Sprint/Sprint.html).

Note that at the current time, while it will work on a phone, the layout is not really suitable for it, and performance is likely to be bad as I have not yet implemented any performance gains for less powerful platforms.