---
layout: page
title: Decoupled Reading
description: Letting demonstration-conditioned robot policies follow longer compositions
img: assets/img/publication_preview/DecoupledReading.png
importance: 3
category: research
---

Demonstration-conditioned policies learn to imitate a task from a prompt demonstration, but struggle when that demonstration chains together more sub-tasks than the compositions seen in training. We decouple _reading_ the demonstration from _acting_: a small reader (~0.4M parameters), trained only on short compositions with DTW-aligned pointer labels, tracks where the robot is in a long demonstration and feeds a frozen policy a moving read window — no policy updates required. Joint work with Cheng Yang and [Prof. Jiatao Gu](https://jiataogu.me/). Accepted to the CoRL 2026 Workshop on Compositional Generalization for Real-World Robot Learning.

{% include figure.liquid loading="eager" path="assets/img/publication_preview/DecoupledReading.png" title="Decoupled Reading overview" class="img-fluid rounded z-depth-1" %}
