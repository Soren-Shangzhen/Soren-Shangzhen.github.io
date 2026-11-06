---
layout: post
title: "Video: How Much Softmax Do LLMs Need?"
date: 2026-10-15
description: A short video explainer of my two softmax papers, covering what pretrained LLMs need from softmax and what changes when you train with a coarse one.
tags: softmax attention llm video
categories: research
---

<div class="sz-video">
  <iframe
    src="https://www.youtube.com/embed/9vOJEx41qkk"
    title="How Much Softmax Do LLMs Need?"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    referrerpolicy="strict-origin-when-cross-origin"
    allowfullscreen
  ></iframe>
</div>

<p><a href="https://youtu.be/9vOJEx41qkk">Watch on YouTube</a></p>

This video walks through the two papers behind my [written explainer](/softmax/):

- [Approximating Softmax in Pretrained LLMs: Model Sensitivity and Kernel Acceleration](https://arxiv.org/abs/2609.33586): which parts of softmax a frozen pretrained LLM actually depends on, and how that turns into a faster attention kernel in FlashAttention-4.
- [Pretraining Transformers with Quantized Softmax in Attention](https://arxiv.org/abs/2609.33591): what changes when a transformer is trained with a coarse, quantized softmax from the start.

Prefer reading? The full written version with interactive figures is at [How Much Softmax Do You Need in LLMs?](/softmax/)
