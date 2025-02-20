---
layout: page
title: Can STAGE Handle the Pressure?
description: Testing Its Generalizability Across Graph Models
img: assets/img/stage.jpeg
importance: 1
category: work
giscus_comments: false
---

Imagine you’re in an e-commerce store browsing for shoes. You’re checking out high-tops, clicking on ankle boots, and maybe even sneakily adding some sneakers to your cart. On the flip side, in the smartphone section, there’s someone comparing camera specs, screen sizes, and RAM. Now, here’s the real question: can a machine learning model trained on shoe shoppers understand the buying behavior of smartphone enthusiasts? We can imagine most people answering “no” to this question.

That’s the challenge of zero-shot generalization, that is, transferring knowledge across graphs with different node attributes. Existing models often struggle with cross-graph generalization tasks. Our protagonist, STAGE, claims to have the chops to do it.

So, does STAGE live up to its claims? Can it take on different architectures and still deliver? Let’s dive into our experiment and find out.

Continue reading in my full [Medium article](https://medium.com/stanford-cs224w/can-stage-handle-the-pressure-testing-its-generalizability-across-graph-models-66292eba0021).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/stage.jpeg" title="STAGE Overview" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    STAGE transforms a customer-product graph into a STAGE-edge-graph for attribute generalization.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/stage_results.jpeg" title="Results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Result for the three methods based on different evaluation metrics.
</div>