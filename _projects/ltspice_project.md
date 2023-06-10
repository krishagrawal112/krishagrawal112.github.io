---
layout: page
title: Analog Circuit Simulator
description: 1st year final project
img: assets/img/sim.jpg
importance: 2
category: Software
---


The project was done in a group of 3. We programed a circuit simulator in C++ similar to industry-available LTSpice that takes as input a netlist describing an electrical circuit and outputs the voltage and current flowing through each node. The program makes use of Modified Nodal Analysis for DC analysis and uses Newton's method with small-signal analysis to approximate the AC behaviour of non-linear components.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/sim.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/sim2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The respository with the code can be found [here](https://github.com/krishagrawal112/Circuit-Simulator).