---
layout: page
title: Information Visualization
description: Telling the story of ambient air pollution and health consequences
img: assets/img/infoviz/header_airpollution.png
importance: 1
category: Design
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/infoviz/header_viz.png" title="Header Info Viz" class="img-fluid rounded" %}
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

#### Our Process:
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/infoviz/process.png" title="Process" class="img-fluid rounded" %}
    </div>
</div>

#### My Role:
- **Literature reviews**: gain a strong foundation on the topic and find leads for data sources 

- **Drafting**: create a flow for the webpage and sketch data visualizations 

- **Implement**: program a few visualizations and program the front-end for the webpage  

- **Test**: draft and conduct user testing on the webpage 

- **Polish**: respond to user feedback and iterate on designs

<div>
<br>
</div>

#### Highlighting some of our visualizations:

<div>
<br>
</div>

`Representing PM 2.5 concentrations around the world`

<div class="row justify-content-sm-center mt-4">
    <div class="col-sm-4 mt-3 mt-md-0 text-center">
        {% include figure.html path="assets/img/infoviz/ogdesign1.png" title="" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
        Draft showing PM as air particles
        </div>
    </div>
    <div class="col-sm-8 mt-3 mt-md-0 text-center">
        <strong></strong>
        {% include figure.html path="assets/img/infoviz/brushing.png" title="example image" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
        Final visualization mapping PM 2.5 concentrations to the world map
        </div>
    </div>
</div>
<div class="row justify-content-sm-center mt-">
    <div class="col-sm-4 mt-3 mt-md-0">
        <p>❌ This a poor design because the size of the dots is not proportionate to the size of the particles in real life. <br> It does not represent the information honestly because of the distorted sizes. </p>
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        <p>✅ We used brushing and linking in this interaction. Viewers can brush over the scatterplot to see where in the world has different PM 2.5 concentrations </p> 

        {% include figure.html path="assets/img/infoviz/relativesize.png" title="example image" class="img-fluid rounded z-depth-1" %}

         <p>✅ Provide context to the viewer on the size of particulate matter. We built a zoom animation to show relative size. </p>
    </div>
</div>

<div>
<br>
</div>

`Improving the word cloud`

<div>
<br>
</div>

**TRADITIONAL WORD CLOUDS ARE INEFFECTIVE**

<div class="row justify-content-sm-center">
    <div class="col-sm-5 mt-3 mt-md-0">
         {% include figure.html path="assets/img/infoviz/wordcloud-butterfly.png" title="Butterfly Word Cloud" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-7 mt-3 mt-md-0">
        <p>❌ It is unclear what the word size variations mean. Could be frequency of the word or hand-picked by the designer to highlight particular words </p> 
         <p>❌ Inconsistent and sometimes unnecessary uses of color. No explanation of if colors are meant to group words </p>
    </div>
</div>

<div>
<br>
</div>

**OUR FINAL WORD VISUALIZATION**

<div class="row justify-content-sm-center mt-4">
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include figure.html path="assets/img/infoviz/word-map.png" title="Improved word map" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-5 mt-3 mt-md-0">
        <p>✅ Intentional use of semantic and visual grouping. I grouped the diseases with the primary part of the body that it affects. </p> 
         <p>✅ We added icons of the body parts to make the semantic groupings clear. Through user testing, we found that the groupings were not obvious because people might not be familar with all these diseases.</p>
    </div>
</div>

<div>
<br>
</div>

`Effective Communication with data`

<div>
<br>
</div>

I created these flat visualizations to show the air pollution's contribution to global disease deaths. In total, I discuss four different diseases and their relation to air pollution. I found that it was effective to keep each disease separate in order to focus the viewer on one point at a time. The repetition of the style of the visualizations created a smooth flow for understanding the effects of air pollution.


The pairing text with the visualization make it easier and faster to interpret. Rather than having the viewer try to calculate the significance in their brain, I provided the number directly above. Bolding the important text like the percent and specific disease makes it even quicker for the viewer to comprehend.

I also reduced variance in colors by using grey as my part-of-the-whole. Here the visualization becomes very simplistic eliminating clutter and allowing the viewer to focus on the only part with color. 

<div class="row justify-content-sm-center">
    <div class="col-sm-9 mt-3 mt-md-0">
        {% include figure.html path="assets/img/infoviz/stroke.png" title="Air pollution contributed to about 18.3% of global stroke deaths" class="img-fluid rounded" %}
        
        {% include figure.html path="assets/img/infoviz/copd.png" title="Air pollution contributed to about 19% of global COPD deaths" class="img-fluid rounded" %}

    </div>
</div>

<div class="row justify-content-sm-center text-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        <hr>
        <strong><a href="https://astoriah.github.io/info247-final-aap/index.html" target="_blank">See the rest of our visualizations: here</a></strong>
        <hr> 
    </div>
</div>

{% raw %}
```html
    
    Reflection: 

    I learned a lot from this project both about outdoor ambient air pollution
    and information visualization and organization. 
    
    We asked each user their main takeaway from each visualization to ensure
    the key insights were effectively communicated. The user testing we conducted 
    was crucial in catching unclear aspects of our visualizations.
    
    --

    "Terrific aesthetic design, terrific story, fantastic use of scientific references
     in an approachable way with proper attribution, excellent use of 
     innovative visualizations that really advance the story and illustrate 
     the data, and superb use of animation!"
    Feedback from Professor Marti Hearst

```
{% endraw %}

<!-- <div class="caption">
    This image can also have a caption. It's like magic.
</div> -->
