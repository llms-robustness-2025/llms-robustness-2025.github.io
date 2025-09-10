---
title: ACML 2025 Towards Robust and Trustworthy Large Language Models - Issues and Mitigation Strategies 
layout: page
permalink: /
---

## Overview

Recent advancements in large language models (LLMs) have achieved superhuman performance across various domains and tasks, unlocking their potential in real-world applications.
However, robustness and trustworthiness issues hinder their reliable deployment.
Robustness issues refer to inconsistent model behaviors under equivalent conditions, such as sensitivity to minor prompt variations.
Trustworthiness encompasses issues like hallucinations--situations where LLMs produce factually incorrect or input-conflicting outputs--and fairness issues, including biases toward certain races, genders, value systems, or languages.
Addressing these is crucial for building reliable applications with these powerful yet vulnerable models.

We will conclude the tutorial by outlining future research directions in this area.

# Speakers

<div class="col-md-4">
    <div class="profile height150">
        <div><a href="https://brian-ckwu.github.io/"><img class="avatar-img" width=150 src="images/ckwu.jpg"> </a></div>
        <div style="margin-bottom:40px"><center><b> Cheng-Kuang Wu</b> <br> Appier </center></div>
    </div>
</div>
<div class="col-md-4">
    <div class="profile height150">
        <div><a href="https://theblackcat102.github.io/"><img class="avatar-img" width=150 src="images/zhiruitam.jpeg"></a></div>
        <div style="margin-bottom:40px"><center><b>Zhi Rui Tam</b><br> NTU</center></div>
    </div>
</div>

<div class="col-md-4">
    <div class="profile height150">
        <div><a href="https://khhuang.me/"><img class="avatar-img" width=150 src="images/kuanhaohuang.jpg"></a></div>
        <div style="margin-bottom:40px"><center><b>Kuan-Hao Huang</b><br> Texas A&M University</center></div>
    </div>
</div>

## Outline


### Introduction
Definitions, importance, and taxonomy of robustness and trustworthiness issues

### Adversarial attacks and jailbreaking
Intentional disruptions in model behavior ([Zou et al., 2023](https://arxiv.org/abs/2307.15043), [Chao et al., 2025](https://doi.org/10.1109/SaTML59370.2025.00008)).

### Prompt variations
Effects of semantically equivalent prompt changes on model performance ([Sclar et al., 2024](https://openreview.net/forum?id=RIu5lyNXjT)).

### Position bias
Bias toward information based on input position ([Wang et al., 2025](https://openreview.net/forum?id=8lBhNdE2wb)); impact on tasks like pairwise response evaluation ([Zheng et al., 2023](https://arxiv.org/abs/2306.05685)), multi-choice questions ([Zheng et al., 2024](https://openreview.net/forum?id=shr9PXz7T0)), and retrieval-augmented generation (RAG) ([Liu et al., 2024](https://doi.org/10.1162/tacl_a_00638)).

### Hallucinations
When the LLM's generation is factually incorrect, contradicts with its own generation, or conflicts with the provided input context ([Huang et al., 2025](https://doi.org/10.1145/3703155)).

### Fairness and social biases
Biases in ethnicity, gender, value systems, or languages.

### Reasoning models
Specific issues introduced by LLMs trained to generate reasoning tokens before providing the final answer ([Kumar et al., 2025](https://arxiv.org/abs/2502.02542)).

### Multimodal models
Issues introduced by models that process multimodal inputs ([Tong et al., 2024](https://openaccess.thecvf.com/content/CVPR2024/html/Tong_Eyes_Wide_Shut_Exploring_the_Visual_Shortcomings_of_Multimodal_LLMs_CVPR_2024_paper.html)).

### Conclusion and open challenges
Summary of best practices for developing robust and trustworthy LLMs, open research questions, and future directions.
