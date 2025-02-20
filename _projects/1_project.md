---
layout: page
title: NIMA
description: Neural Aesthetic Portrait Image Assessment
img: assets/img/CS231N_Poster.png
importance: 2
category: work
related_publications: false
---

Portraits form a significant portion of personal photo albums, making the development of neural aesthetic assessment specialized for portraits beneficial to everyone's everyday life. To improve upon a general aesthetic model to perform neural aesthetic assessment on portraits, we integrated facial embeddings from the VGG-Face model into the Neural Image Assessment (NIMA) framework. This proved effective, with the enhanced model achieving an accuracy of 0.8341, an LCC of 0.7786 and an SRCC of 0.7849, surpassing the baseline results. Additionally, we conducted interpretability experiments using gradient-weighted class activation mapping (Grad-CAM) and guided backpropagation to visualize the regions of images that contribute most to the model's predictions. These visualizations help validate the model's decision-making process and highlight its focus on relevant facial features.

[Project Report](https://houxiru.github.io/assets/pdf/CS231N_Project_Report.pdf)

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/CS231N_Poster.png" title="Project Poster" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Poster for our project.
</div>
