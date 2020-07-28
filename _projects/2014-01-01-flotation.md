---
layout: page
title: Flotation Tanks (2010-2014)
description: CFD modeling of flotation tanks
summary: 
---

In South Africa from 2010 to 2014, I developed a CFD model for prediction of 
flotation rate constants in a stirred flotation tank and validated against 
experimental data. The model incorporated local, time-varying values of the 
turbulent flow field into an existing kinetic flotation model. The geometry of 
the tank and the meshing is shown below.

<!-- <img src="/assets/posts_imgs/mesh.png" alt="mesh"
	title="Mesh for flotation tank" width="600" height="650" /> -->

<img src="/assets/images/mesh.png?raw=true" title="Mesh for flotation tank"/>


The modeling stages includes single phase, multiphase simulations using 
Eulerian-Eulerian framework with drag force for the multiphase modeling. A 
parametric study on the available drag coefficients is performed showing that 
some drag models might lead to nonphysical representation of the flow 
characteristics. For instance the figure below depicts how the choice of drag 
coefficient formulations simulates the presence of air cavity.    

<!-- <img src="/assets/images/cavity_comparison.png" alt="cavity"
	title="Different drag models" width="600" height="650" /> -->

<img src="/assets/images/cavity_comparison.png?raw=true" 
title="Different drag models"/>

The flotation sub-processes including collision, attachment and detachment 
between air bubbles and solid particles are also formulated and coded into the
model to evaluate the recovery of valuable minerals. For example the following 
image illustrates the contour plots of collision rates under different rpms.

<!-- <img src="/assets/images/collision.png" alt="collision"
	title="Contours of collision probability" width="600" height="650" /> -->

<img src="/assets/images/collision.png?raw=true" 
title="Contours of collision probability"/>

The main contribution of this work is that it provides a validated and optimized
 numerical methodology that predicts the flotation macro response (i.e., 
 flotation rate constant) by integrating the significance of the hydrodynamic 
 flow features into the flotation micro-processes.


<iframe width="600" height="330" src="https://www.youtube.com/embed/RKcdHj0LnTo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>