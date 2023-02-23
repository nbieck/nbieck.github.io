---
layout: post-wide
uid: cs562
title: "Advanced Rendering Techniques"
date: 2015-11-01
categories: project
---

This is a set of five projects I worked on during Fall 2015 for the Advanced Rendering Techniques course at DigiPen Institute of Technology.

They demonstrate several modern real-time graphics algorithms.

The code can be found [here](https://github.com/nbieck/CS562).

## Deferred Shading

![](/images/portfolio/cs562/CS562_Lit3k.png)

The first project consisted of implementing a Deferred Shading pipeline. The image shows the Crytek Sponza illuminated by a large number of pointlights, made possible by the deferred pipeline.

## Exponential Shadow Mapping

![](/images/portfolio/cs562/CS562_Shadow_Mapping.png)

Exponential Shadow mapping is a technique to produce soft, anti-aliased shadows, as visible in the image.

## Image Based Lighting

![](/images/portfolio/cs562/CS562_final_present_6.png)

Here you can see a modern microfacet-based BRDF (a.k.a. physically based rendering), in combination with image based lighting and HDR rendering.

## Ambient Occlusion

![](/images/portfolio/cs562/CS562_ao_present_shot_2.png)

This image demonstrates screenspace ambient occlusion (SSAO) using the Alchemy algorithm.

## Screenspace Reflections

Finally, the following pictures demonstrate screenspace reflections, computed using the algorithm presented in the article Hi-Z Screenspace Cone-Traced Reflections from GPU Pro 5. Only the sharp reflection is visible, as time issues prevented me from completing the cone-tracing part nevessary for blurred reflections on glossy surfaces.

![](/images/portfolio/cs562/CS562_SSR_1.png)
![](/images/portfolio/cs562/CS562_SSR_2.png)