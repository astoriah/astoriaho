---
layout: page
title: Data Visualization
description: Telling the story of ambient air pollution and health consequences
img: assets/img/infoviz/header_airpollution.png
importance: 1
category: UC Berkeley
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/infoviz/header_viz.png" title="Header Info Viz" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<p class="h5 my-5 text-center">
This project is a narrative about outdoor ambient air pollution, its global health consquences, and how individuals' can protect themselves. 
</p>

    ---
    Final project for INFO 247: Information Visualization and Presentation 
    taught by Professor Marti Hearst.
    Timeline: 8 weeks
    Team: Myself, Clara Hu
    Tools Used: Observable, D3, HTML/CSS, Figma
    ---
<div>
<br>
</div>
#### View our live webpage here:
<p class="h4 py-3 text-center">
<a href="https://astoriah.github.io/info247-final-aap/index.html" target="_blank">https://astoriah.github.io/info247-final-aap/index.html</a>
</p>
<p class="h6 mb-5 text-center">
<a href="https://astoriah.github.io/info247-final-aap/AstoriaHoClaraHu_INFO247_FinalProject_Report.pdf" target="_blank">Report</a>  |  
<a href="https://github.com/astoriah/info247-final-aap" target="_blank">Github</a>
</p>



<!-- <div class="caption">
    This image can also have a caption. It's like magic.
</div> -->

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
