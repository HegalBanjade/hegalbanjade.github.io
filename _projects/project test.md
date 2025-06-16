---
layout: page
title: test
description: a project with a background image and giscus comments
importance: 2
category: graphic design
disqus_comments: true
images:
  slider: true
---

This is a test.

<div class="row">
    <div class="col-lg mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/1.jpg" title="idk" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-lg mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/3.jpg" title="idk" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-lg mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/2.jpg" title="idk" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    this is pretty cool.
</div>

<swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true">
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/projects/1.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/projects/3.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/projects/2.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
</swiper-container>

bello