---
layout: page
title: Arithmetic Accelerator on FPGA
description: Coursework for 3rd year module ELEC60011-Digital Systems Design
img: assets/img/de1.png
importance: 1
category: Digital Hardware
---

The computation of the following arithmetic function was accelerated on a DE1-SoC FPGA board:
$$ f(x) = \sum_{i=1}^{N} 0.5 \times x_i + x_i^2 \cos(\frac{x_i - 128}{128})$$

This involved designing a CORDIC block in SystemVerilog and interfacing it with a NIOSII softcore processor via a custom instruction. Alongside this main task, numerous other hardware and software optimisations were explored 

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/de1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/cordic.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The respository with the code can be found [here](https://github.com/krishagrawal112/Arithmetic-Accelerator-FPGA).