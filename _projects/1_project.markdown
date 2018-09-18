---
layout: page
title: Robustness Metrics for Networked Structures
description: In collaboration with D. Towsley, S. Guha, A. Swami
img: /assets/img/Grid.jpg
---

Percolation theory predicts a phase transition in the global connectivity of a networked system when the probability of nodes/edges being present in the network passes a certain threshold. This approach has been extensively used in the literature to study the robustness of various networks to failiures. However, this approach has two main shortcommings:
 1. Precolation theory studies the infinite limit behavior in networks and there are limited studies that deal with small networks using percolation theory. 
 2. General network connectivity is not robust enough for most of the technological and natural networks to ensure resilience to dynamics of the networks or failiures in network components. As an illustrative example, it is been observed that cellular networks need to have multiple pathways to maintain stability to perturbations during cellular metabolism.

To address this shortcommings, I am developping and studying novel robustness metrics. Surprisingly, it can be rigorousely proved that for bond/site percolation on the square lattice, the percolation threshold for Biconnectivity and Triconnectivity are the same as regular percolation threshold. Also, Newman et al. (Phys. Rev. Lett. 100, 138701) showed that 




<div class="img">
    <img class="col three" src="{{ site.baseurl }}/assets/img/Newman.png" alt="" title="Newman"/>
</div>
<div class="caption">
    Percolation threshold for biconnectivity on configuration model networks. k=1 corresponds to regular percolation and k=2 corresponds to biconnectivity. Image from Newman et al. (Phys. Rev. Lett. 100, 138701) 
</div>
<div class="img_row">
    <img class="col three left" src="{{ site.baseurl }}/assets/img/5.jpg" alt="" title="example image"/>
</div>
<div class="col three caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images. Say you wanted to write a little bit about your project before you posted the rest of the images. You describe how you toiled, sweated, *bled* for your project, and then.... you reveal it's glory in the next row of images.


<div class="img_row">
    <img class="col two left" src="{{ site.baseurl }}/assets/img/6.jpg" alt="" title="example image"/>
    <img class="col one left" src="{{ site.baseurl }}/assets/img/11.jpg" alt="" title="example image"/>
</div>
<div class="col three caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


<br/><br/>


The code is simple. Just add a col class to your image, and another class specifying the width: one, two, or three columns wide. Here's the code for the last row of images above:

<div class="img_row">
    <img class="col two left" src="/img/6.jpg"/>
    <img class="col one left" src="/img/11.jpg"/>
</div>
