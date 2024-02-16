---
title: Micro U-space Visualization
date: 2024-02-16
authors: [Balita_Rakotonarivo]
url: micro-u-space-visualization
---

In Bordeaux UAV Show in October 2023, we showcased a Micro U-space, with physical drones performing operations non-stop during the exhibition ; and a system allowing to visualize the services executed.

<!--more-->

This mix a cyberphysical systems (the drones) and the U-space services allowed autonomous operations for the 
<a href="https://www.bitcraze.io/products/crazyflie-2-1/" target="_blank">Crazyflies</a> used for the demonstration.

Three scenarios were performed by the drones:

- one medical transport from two hospitals (red)
- one police drone doing routine surveillance (blue)
- one taxi drone transporting passengers (yellow)

Of course, the drones had to land and recharge. One of their deconfliction rules was to not to be allowed to take-off until it has enough battery power and that there was a slot available to perform safely its  flight. 


Technical stack:

* Front-end: JS - Leaflet, Pixi
* Backend: Python - Flask
* Physical: Crazyflie

The visualization took some inspiration from CORUS v4, for the different steps of a drone operation as well as some of the recommandations in our <a href="https://dl.acm.org/doi/abs/10.1145/3544548.3581003" target="_blank">CHI paper</a>.


<div align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/tZT0khZ70AQ" title="Micro U-space Visualization" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
