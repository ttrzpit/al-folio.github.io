---
layout: page
title: AlertWear & Toolbox Spotter
description: A wearable designed to keep construction sites safe. 
img: assets/img/projects/TooSpo_AlertWear.jpg
importance: 2
category: Engineering Projects
related_publications: false
---

*August 2017*

During an internship with the Engineering Excellence Group (Part of Laing O'Rourke, a multinational engineering and construction company), I was fortunate enough to have been part of the team that designed and developed the AlertWear (wearable haptic feedback device) and Toolbox Spotter (a portable computer-vision-based alert system), to keep people safe within construction sites. The device is now commercially available and won the 2019 Australasian Rail Industry’s Innovation and Technology Award. 

For my part, I designed and built the AlertWear device. This wearable would receive wireless network alerts in real time from the Toolbox Spotter, and used focused vibrotactile elements to warn the wearer of potential hazards to them or the equipment they are operating. Additionally, I designed and implemented the encrypted wireless network that utilized the XBee radio protocol to coordinate between sensors, processing nodes, and feedback devices with an outdoor range of one kilometer. We also tested the system *in situ* at the Royal Australian Air Force Base Amberley in Queensland, Australia, to ensure no cross-talk or interference with other radio systems.

More details on the Toolbox Spotter and its architecture are available in this paper: [Toolbox Spotter at arxiv](https://arxiv.org/pdf/2105.10842)

    
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/TooSpo_AlertWearShort.jpg" title="AlertWear device." class="img-fluid rounded" %}
    </div>
</div>
<div class="caption">
    The final AlertWear prototype. 
</div>


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/TooSpo_PrototypeExternal.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/TooSpo_PrototypeInternal.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The wearable prototype that I developed, along with the internals squeezed into this alpha version. 
</div>


