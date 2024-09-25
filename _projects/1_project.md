---
layout: page
title: Image reconstruction from neural activity patterns
description: 
img: assets/img/img_recon_workflow.png
importance: 1
category: work
related_publications: false
---

My first project when delving into computational neuroscience was to reconstruct seen or perceived images from neural activity patterns. I leveraged one of the generative models available at that time, and my algorithm could learn the overall shape, color, and some details of images. It was able to reconstruct the images from fMRI neural activity patterns in a zero-shot manner. Below are some of my results. The top row shows the real images, and the bottom row shows the reconstructed images.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/img_recon_results.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>



