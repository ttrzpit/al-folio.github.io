---
layout: page
title: Kinetic Art Installation
description: Mechatronic system designed produced for artist Terry Berlier. 
img: assets/img/projects/TerBer_PulleyBoxInternal.jpg
importance: 2
category: Engineering Projects
related_publications: false
---

*August 2018*

I was fortunate enough to work with the brilliant Terry Berlier, an artist in residence at Stanford, who specializes in kinetic art and sculpture. She had an idea for a kinetic piece in which shoes would be raised up slowly by a clear fishing line, and then after a random interval, be released and drop into freefall. To quote Terry's website: 

*"Berlier’s installation uses a common American saying “waiting for the other shoe to drop” (referring to a sense of impending doom) as her departure point. Gestures between silence, waiting, and collapse suggest the tension between stasis and engagement. The illusion of progress which lulls us to complacency is interrupted by dissonance and a clearer call to action."*

I actuated the lift and release mechanisms using solenoids and stepper motors. When the motor needed to pull up the shoe, a solenoid would engage the pulley into the motor, engaging a gear. When it was time for freefall, the solenoid would withdraw, and the pull would spin freely, allowing the shoe to drop. I also built a control box for the system, allowing 5 shoes to be independently driven. 

The project was exhibited at the Contemporary Art and Spirits gallery in Osaka, Japan in November of 2018. More information about the project, including more photos and video, are available at Terry Berlier's website, linked here: [Tinkering Towards Utopia](https://www.terryberlier.com/tinkering-towards-utopia-2/).

    
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/TerBer_PulleyBoxInternalShort.jpg" title="Shoe lifter device." class="img-fluid rounded" %}
    </div>
</div>
<div class="caption">
    Internals of the "drop box". 
</div>


<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/TerBer_DropBoxes.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/TerBer_ControlBoxConnected.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    At left, a set of four dropboxes, clamped and ready for testing. At right, a control box with the electronics tucked safely inside.
</div>
   
   
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://player.vimeo.com/video/342512226?h=3b0a6aeb74" class="img-fluid rounded z-depth-1" controls=true autoplay=false %}
    </div>
</div>
<div class="caption">
    Video of the art installation (for a full-screen version, please follow the video to Vimeo).
</div>



