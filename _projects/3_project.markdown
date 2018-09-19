---
layout: page
title: Pattern Formation in Reaction-Diffusion Systems
description: In collaboration with D. Towsley and S.Guha
img: /assets/img/pattern.jpeg
---
<h4>Turing Patterns in Reaction Difussion Systems</h4>

In his 1952 paper (<a href="http://www.dna.caltech.edu/courses/cs191/paperscs191/turing.pdf" target="blank">The Chemical Basis of Morphogenesis</a>), Alan Turing introduced the concept of Turing patterns. Since his nominal paper, scientists have broadened the scope of reaction diffusion systems that could result in Turing patterns. THese patterns appear in distinct natural phenomena ranging from vegetation patterns in deserts (<a href="https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.87.198101" target="blank">vegetation patterns</a>) to laser filamentation governed by nonlinear Schrodinger eqution (<a href="https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.114.063903" target="blank">laser filamentation</a>). 


<h4>Laser Filamentation as a New Phase Transition</h4>

My research was motivated by this paper on <a href="https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.114.063903" target="blank">laser filamentation</a>. A extremely high power laser passes through a medium. This causes the medium to become plasma at some points in the space. The interaction of the high power laser and the plasma immitates the setting of a reaction diffusion system with different interacting entities. 

The image below, shows the evolution of the intensity of the laser pulse as it travels in space. Each image is taken at a cross sextion of the laser beam at a certain distance from the source. The left most image is the nearest and the right most image is furthest one. Colors denote, the size of the connected clusters. Dark red colors denote larger components. As it can be seen from the image, at some point between image (h) and (i) the system looses its global connectivity. 

<div class="img">
    <img class="col" src="{{ site.baseurl }}/assets/img/laser.png" alt="" title="example image"/>

<div class="col three caption">
 Evolution of a high power laser pulse in the air. taken from <a href="https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.114.063903" target="blank">this</a> paper.
</div>


<h4>My Research Contribution</h4>

I developped a very simple single species reaction diffusion model with that mimics the phase transition behavior and percolation behavior of a wide variet of physical systems, one being the lase filamentation phenomena. The dynamics of the proposed model passes through various regimes of Turing patterns and is controllable by parameters in the model. The image below shows an snapshot of the system at the critical point. 

<div class="img">
    <img class="col" src="{{ site.baseurl }}/assets/img/pattern.jpeg" alt="" title="example image"/>

<div class="col three caption">
    An example image of my single species reaction diffusion model at the critical point.
</div>

<h4>The Model</h4>
The proposed model is a very simple model in which the diffusion of particles in the system is dependant on the sum of the number of particles surrounding them. At time t, let n be the number of walkers on a lattice site and m the sum of the number of walkers on the neighboring sites. If n≥m the walker hops to one of the neighboring sites with equal probability and if n<m it does a lazy walk, i.e., hops only with probability exp(m-n). We declare a site active if there is at least one walker on it and inactive otherwise. Two neighboring sites have an edge if both are active. We compute the wrapping probability of the clusters formed at each time step, averaging over many simulations. We observe a sharp phase transition in the wrapping probability at a time threshold.

<br>
<br>

This work has been presented in <a href="https://meetings.aps.org/Meeting/MAR18/Session/K47.8" target="blank">American Physical Society March Meeting 2018</a> in Spatiotemporal Pattern Formation session and is in preparation for submission to Physical Review E.



