---
layout: page
title: Robustness Metrics for Networked Structures
description: How networks respond to loss of nodes/edges?
img: /assets/img/Grid.jpg
---

Percolation theory predicts a phase transition in the global connectivity of a networked system when the probability of nodes/edges being present in the network passes a certain threshold. This approach has been extensively used in the literature to study the robustness of various networks to failiures. However, this approach has two main shortcommings:
 1. Precolation theory studies the infinite limit behavior in networks and there are limited studies that deal with small networks using percolation theory. 
 2. General network connectivity is not robust enough for most of the technological and natural networks to ensure resilience to dynamics of the networks or failiures in network components. As an illustrative example, it is been observed that cellular networks need to have multiple pathways to maintain stability to perturbations during cellular metabolism.

To address this shortcommings, I am developping and studying novel robustness metrics to 




<div class="img_row">
    <img class="col one left" src="{{ site.baseurl }}/assets/img/1.jpg" alt="" title="example image"/>
    <img class="col one left" src="{{ site.baseurl }}/assets/img/2.jpg" alt="" title="example image"/>
    <img class="col one left" src="{{ site.baseurl }}/assets/img/3.jpg" alt="" title="example image"/>
</div>
<div class="col three caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
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
