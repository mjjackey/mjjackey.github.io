---
title: "Overlap‑Aware Soft‑InfoNCE for Fine‑Grained Emotion Classification"
collection: publications
category: conferences
permalink: /publication/Ov_Soft
excerpt: 'Fine-grained emotion classification (FEC), the task of distinguishing subtle distinctions among emotion categories, poses a challenging problem. Previous studies have introduced various supervised contrastive learning (SCL) methods, which can be classified into three main approaches: reweighting, cluster-guided pairs, and hard-pair set mining to optimise ambiguous boundaries. In this paper, we propose Overlap-Aware Soft-Information Noise-Contrastive Estimation (OASI1), a contrastive loss that incorporates the annotation distribution to softly weight positive pairs and leverages the overlap of the raw label-set Jaccard to suppress false-negative signals in the contrastive denominator. SCL treats samples with ambiguous annotations in the GoEmotions dataset as hard negatives, while such pairs introduce potential false-negative signals and impair representation quality. Our approach mitigates this issue by utilising the dataset’s raw annotation statistics as auxiliary supervisory signals, and therefore complementing extra column information to the native dataset. Finally, we evaluate our method on GoEmotions, achieving state-of-the-art (SOTA) performance.'
date: 2026-10-20
venue: 'ICAID 2027'
# paperurl: 'https://mjjackey.github.io/files/paper3.pdf'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

<!-- Using [MathJax](https://www.mathjax.org/) in the description is supported - $$E=mc^2$$ - however, the use must be mindful that the default delimiters are `$$...$$` and `\\[...\\]` which differs from the `$...$` that is typically expected. -->
A manuscript based on this work has been submitted to ICAID 2027 and is currently under review