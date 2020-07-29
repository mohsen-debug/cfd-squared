---
layout: page
title: Fermentation Bioreactors (current)
---

The current project that I am working on is about mass transfer intensification
with application in fermentation bioreactors. I am using ANSYS Fluent and 
OpenFOAM for simulating a lab-scale reactor and model developments, accordingly.
The project is a collaboration between 
[fluid dynamics division](https://www.chalmers.se/en/departments/m2/research/fluiddynamics/Pages/default.aspx) 
and [industrial biotechnology department](https://www.chalmers.se/en/departments/bio/research/industrial-biotechnology/Pages/default.aspx) 
where the measurements for are carried out. 

The OpenFOAM line of model development deals with the physical phenomena that 
occur at the gas-liquid interface and the modeling difficulties relevant for 
this length scale. For example the video below shows the treatment of surface 
tension forces at the interface might lead to nonphysical velocities  also known
 as _wobbling interface or parasitic currents_.


{% include responsive-embed url="https://www.youtube.com/embed/jo_ll1XzLRo" ratio="16:9" %}

<!-- <iframe width="600" height="330" src="https://www.youtube.com/embed/jo_ll1XzLRo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

Below is an image of OpenFOAM simulations capturing the thickness of mass 
boundary layer for diffusion of a species. 


<img src="/cfd-squared/images/bl.png?raw=true" class="align-center" width="600" height="300"
title="Thickness mass boundary layer"/>

The other parallel line of work with ANSYS Fluent is concentrated on simulating
the lab-scale bioreactor in terms of mixing time, and mass transfer 
coefficient. A comprehensive model is formulated and implemented that includes
the followings:
- Mixing time based on Coefficient of Variation (CoV)
- Volumetric mass transfer coefficient
- Sherwood number
- Bubble size distribution

The simulations are validated with measurements. The below image and video are 
examples of modeling results.


<img src="/cfd-squared/images/bsd.png?raw=true" class="align-center" 
title="Bubble size distribution"/>

{% include responsive-embed url="https://www.youtube.com/embed/W1bVpep5w4c" ratio="16:9" %}

<!-- <iframe width="600" height="330" src="https://www.youtube.com/embed/W1bVpep5w4c" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->
