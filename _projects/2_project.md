---
layout: page
title: SLOTH
description: Semantic Learning Optimization and Tuning Heuristics for Enhanced NLP with minBERT
img: assets/img/CS224N_Poster.png
importance: 3
category: work
giscus_comments: false
---

Advancements in Natural Language Processing (NLP) through models like BERT have significantly propelled the field, yet challenges persist in tasks such as sentiment analysis, paraphrase detection, and semantic textual similarity due to the nuanced nature of human language. This paper presents an innovative approach to these tasks by enhancing the BERT model with Multiple Negatives Ranking Loss (MNRL) and regularized optimization techniques, specifically aimed at improving semantic understanding and model generalization. We introduced fine-tuning strategies that leverage task-specific head variations and pre-concatenation of sentence pairs, offering a deeper contextual analysis. Our experimental results exhibit notable enhancements across all tasks, with our methods achieving leading scores on benchmark leaderboards. The implementation of MNRL demonstrated a refined ability to discriminate between closely related texts, whereas the regularization methods effectively mitigated the overfitting problem prevalent in deep learning models. This study highlights the critical aspects of model tuning and loss function selection in achieving superior NLP task performance.

[Project Report](https://web.stanford.edu/class/cs224n/final-reports/256904367.pdf)

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/CS224N_Poster.png" title="Project Poster" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Poster for our project.
</div>
