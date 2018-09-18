---
layout: page
title: Graph Convolutional Neural Networks Using Discrete-time Quantum Walks
description: In collaboration with S. Dernbach, S. Pal and D. Towsley
img: /assets/img/usheat.png
---

Convolutional neural networks have attracted lots of attention in past few years for tasks that range from imgae classification to signal processing. However, these approached are limited to grid-structured data. There is growing interest in applying ideas from convolutional neural networks to graph structured data. A subset of these graph deep learning architectures are based on classical random walks to extract and learn information from the graph.

Atwood et al. proposed Diffusion-Convolutional Neural Networks (DCNN). DCNN is a spational convoltional method which diffuses random walks on the graph and collects information from spatially close neighbors in the graph.

Quantum walks are the quantum parallel to their classical counterparts – While a classical walker is modeled by a probability distribution overpositions in a graph, a quantum walker is described by a superposition over position states.




<div class="img">
    <img class="col one" src="{{ site.baseurl }}/assets/img/usheat.png" alt="" title="example image"/>

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
