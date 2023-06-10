---
layout: page
title: Object Detection on FPGA for Autonomous Rover
description: 2nd year final project
img: assets/img/vis1.jpg
importance: 3
category: Digital Hardware
---

The project involved creating an autonomous "Mars rover" that navigates and maps an arena with obstacles. Each person in the 6-person group was responsible for one of the 6 subsystems, namely Energy, Drive, Control, Command, Radar, and Vision. I was responsible for the Vision subsystem which involved implmenting an image processing and object detection system on a DE10-Lite FPGA board connected to a D8M camera. 

The object detection involved detecting and calcuating the distance to coloured balls and striped buildings in the arena. To do so, techniques like RGB-toHSV conversion, hue and saturation thresholding, and gradient edge detection were implemented in Verilog.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/vis1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/vis2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/vis3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The repository and code for the project can be found [here](https://github.com/krishagrawal112/Autonomous-Rover)