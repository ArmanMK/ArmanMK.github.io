---
layout: page
title: Graph Convolutional Neural Networks Using Discrete-time Quantum Walks
description: In collaboration with S. Dernbach, S. Pal and D. Towsley
img: /assets/img/usheat.png
---
<h4> Convolutional Neural Networks on Graphs</h4>
Convolutional neural networks have attracted lots of attention in past few years for tasks that range from imgae classification to signal processing. However, these approached are limited to grid-structured data. There is growing interest in applying ideas from convolutional neural networks to graph structured data. A subset of these graph deep learning architectures are based on classical random walks to extract and learn information from the graph.

Atwood et al. proposed Diffusion-Convolutional Neural Networks (<a href="https://papers.nips.cc/paper/6212-diffusion-convolutional-neural-networks" target="blank">DCNN</a>). DCNN is a spatial convolutional method which diffuses random walks on the graph and collects information from spatially close neighbors in the graph.

<h4> My Research Contribution: Quantum Diffusion as Convolution on Graphs</h4>
Quantum walks has been shown to be exponentially faster than classical algorithms in  some graph search problems. Quantum walks are the quantum parallel to their classical counterparts – While a classical walker is modeled by a probability distribution overpositions in a graph, a quantum walker is described by a superposition over position states. 




<div class="img">
    <img class="col" src="{{ site.baseurl }}/assets/img/qw.png" alt="" title="example image"/>

<div class="col three caption">
    The evolution of a quantum walk can be controlled using a so called Coin operator and it could be very different from the uniform evolution of a regular random walk. The top images correspond to a regular random walk, whereas the bottom images correspond to the evolution of a quantum walk.
</div>

<h3> Results</h3>
<h4> Molecular Graph Classification Task </h4>
IN order to test our proposed method against other graph convolution methods, we make use of three benchmark molecular datasets, namely, MUTAG, Enzymes, and NCI1. The table below describes the details of the mentioned datasets and shows the classification accuracy of state of the art models compared to our QWNN. (For more details, refere to the arxiv version of our paper at the bottom of the page.) 

<div class="img">
    <img class="col three left" src="{{ site.baseurl }}/assets/img/Mutag.png" alt="" title="example image"/>
</div>
<div class="col three caption">
    Description of graph classification datasets and the accuracies of our model compared to other models.
</div>

<h4> Graph Regression Task </h4>
In our graph regression task, we use the temperature time series data available in US weather stations and create a connected graph based on nearest neighbors. The task is then to predict the temperature of the next day given the history of tempereture on the graph. 
<div class="img_row">
	  
    <img class="row three left" src="{{ site.baseurl }}/assets/img/temp.png" alt=""
title="example image"/>
</div>
<div class="col three caption">
    Results for the graph regression task. QW corresponds to our quantum walk neural network architecture.
</div>


The Arxiv version of this research can be found here: <a href="https://arxiv.org/abs/1801.05417" target="blank">Quantum Walk Inspired Neural Networks for Graph-Structured Data</a> <br>


The latest version of our work is submitted to <a href="https://www.complexnetworks.org/" target="blank">Complex Networks 2018</a>.


