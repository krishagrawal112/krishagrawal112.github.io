---
layout: page
title: Signal Processing for Synthesiser 
description: 1st coursework for 3rd year module ELEC60013 - Embedded Systems
img: assets/img/synth.png"
importance: 3
category: Software
---

The project was done in a group of 4. It involved programming a musical synthesiser. The keyboard controlled using a ST NUCLEO-L432KC microcontroller module that contains a STM32L432KCU6U processor, which has an Arm Cortex-M4 core. The aim was to provide users with common synthesiser feastures as well as the ability to combine multiple keyboards togeth with different octaves.

My contribution was in the signal processing/generation part where I implemented sound features like different waveform sounds, low-frequency osccilation (vibrato and tremolo) and ADSR. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/synth.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/adsr.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The repository and code can be found [here](https://github.com/rkhoury18/Embedded_CW2/tree/master/doc)