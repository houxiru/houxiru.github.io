---
layout: page
title: Bluff and Learn
description: Comparing CFR and NFSP in Liar Bar
img: assets/img/CS224R_Poster.png
importance: 1
category: work
giscus_comments: false
---

We present the first systematic AI framework for playing Liar Bar, a challenging multi-player bluffing game with imperfect information, sequential deception, and stochastic penalties. By implementing and comparing Counterfactual Regret Minimization (CFR) and Neural Fictitious Self-Play (NFSP) across both two- and four-player game modes, we highlight the critical trade-offs between tabular and neural approaches to equilibrium learning. Our results show that while CFR performs well in simplified settings, NFSP—enhanced with Double DQN and dense per-round rewards—achieves superior generalization, faster convergence, and near-zero exploitability in complex scenarios. This work not only introduces the first AI agents for Liar Bar but also provides a robust benchmark for future research on scalable, strategy-aware learning in high-risk, imperfect-information environments.

<!-- [Project Report](https://web.stanford.edu/class/cs224n/final-reports/256904367.pdf) -->

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/CS224R_Poster.png" title="Project Poster" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Poster for our project.
</div>
