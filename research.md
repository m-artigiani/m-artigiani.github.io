---
layout: page
title: "Research"
permalink: /research/
author_profile: true
---

**Dynamics** is the study of objects that evolve in time. Examples of dynamical systems are clouds in the Earth’s atmosphere, electrons moving in a magnetic field and balls on a billiard table.

<img style="float: right; width:40%; margin-left:2%; margin-bottom:2%; margin-top:3%;" src="../images/billiard.jpg" title="A billiard table">

All the previous are examples of continuous-time dynamical systems. We can define a *discrete-time* one by considering subsequent applications of a self-map of a space into itself. For instance, we could look at a self-map of a surface. If we have a particle moving according to some law on the surface, we can think of this discrete-time system as taking snapshots of the particle every second.
Dynamics is a relatively new branch of mathematics, dating back only a hundred years or so, and it has not only proved interesting on its own right, but it has been useful in solving many problems for other areas of mathematics, most notably for my work, in **_number theory_**.

My work has mostly been on dynamics on **_translation surfaces_** and their moduli spaces. These are higher genus generalization of flat tori. For example, identifying by translation opposite sides of a regular octagon yields a translation surfaces.
Translation surfaces are beautiful and rich objects which sit at the crossroad between hyperbolic and complex algebraic geometry, geometric group theory and, of course, dynamical systems themselves.
Below is a list of my research papers, divided by topic, with an informal introduction to the problems. For a more detailed and formal description of the topics, see the relevant papers.

<!-- <p float="left">
  <img src="http://ancientrome.ru/art/artwork/mosaic/rom/santa-costanza-roma/cos002.jpg" width="75%" />
  <img src="https://upload.wikimedia.org/wikipedia/commons/a/ad/ModularGroup-FundamentalDomain-01.png" width="20%" title="The fundamental domain for SL(2,Z)">
</p> -->
<center><img src="../images/hyperbolic.svg" width="60%"></center>

## Lagrange Spectrum
**_Diophantine approximation_** is the area of number theory which studies how well real numbers can be approximate by rational ones.
It dates back to the 19th century and it has been generalized to a variety of context.
Badly approximable numbers are real numbers which cannot be approximated better than quadratically in the denominator of the rational approximand.
Given a badly approximable number, we can improve this quadratic error by a constant factor.
The union of such constants forms the **_Lagrange Spectrum_**, a classical object in Diophantine approximation.
Using a different point of view, the Spectrum has been generalized to hyperbolic surfaces (via the well-known link between continued fractions and geodesic flow on the modular surface) and to a particularly symmetric kind of translation surfaces, called Veech surfaces.
The idea behind this generalization is that the Lagrange Spectrum measures the asymptotic excursions of geodesics into cusps, and thus has a natural dynamical interpretation.
Together with Luca Marchese and Corinna Ulcigrai, we proved that the Spectrum of a Veech surface and of a hyperbolic one both contain a semi-infinite interval, called *Hall ray*.
In the hyperbolic case we furthermore prove that this is stable under small perturbations of the way in which we measure the excursions into the cusps.

#### Papers
1. Mauro Artigiani, Luca Marchese and Corinna Ulcigrai: [*Persistent Hall rays for Lagrange spectra at cusps of Riemann surfaces*](https://arxiv.org/abs/1710.02042), Accepted for publication in *Ergodic Theory and Dynamical Systems*.
2. Mauro Artigiani, Luca Marchese and Corinna Ulcigrai: [*The Lagrange spectrum of a Veech surface has a Hall ray*](https://doi.org/10.4171/GGD/384), Groups, Geometry, and Dynamics, **10** (2016), 1287--1337. [arXiv version](https://arxiv.org/abs/1409.7023)

<center>
<figure>
<img src="http://ancientrome.ru/art/artwork/mosaic/rom/santa-costanza-roma/cos002.jpg" width="90%">
<figcaption>A hyperbolic mosaic in the church of Santa Costanza in Rome. Photo taken from <a href="http://ancientrome.ru/art/artworken/img.htm?id=6707">here.</a></figcaption>
</figure>
</center>

## Eaton lenses and infinite translation surfaces
<img style="float: left; width:25%; margin-right:2%; margin-bottom:2%; margin-top:3%;"  src="../images/eaton.svg" width="40%" title="An Eaton lens">
In the last ten years there has been a growing interest on **_infinite_** translation surfaces, where the adjective infinite can stand both for infinite topological type and for infinite area.
I have been working on the surface obtained from an infinitely periodic pattern of identical Eaton lenses in the plane. These lenses are examples of perfect retroflector, meaning that when a light-ray comes into one of them it gets reflected exactly in the same direction but with opposite orientation. Via a standard procedure this yields an infinite (both in genus and area) translation surface.
The geodesic flow on this family of surfaces has been shown to be generically non-ergodic, in contrast to what happens for compact translation surfaces, where the flow in almost every direction is uniquely ergodic. More precisely, a trajectory of the flow in a generic direction on a generic surface is trapped inside an infinite strip of bounded width.
I have constructed exceptional surfaces on which the flow in the vertical direction is ergodic and, in particular, fill out the infinite surface. The set of these exceptional surfaces is small in the sense of measure due to the above result, but I showed that it has big Hausdorff dimension.

#### Papers
1. Mauro Artigiani: [*Exceptional ergodic directions in Eaton lenses*](https://doi.org/10.1007/s11856-017-1509-8), Israel Journal of Mathematics, **220** (2017), 29--56. [arXiv version](https://arxiv.org/abs/1503.02191)
