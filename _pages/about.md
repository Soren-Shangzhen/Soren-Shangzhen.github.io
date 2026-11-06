---
layout: about
title: About
permalink: /
subtitle: PhD student, <a href='https://illinois.edu/'>University of Illinois Urbana-Champaign</a>

# Home page hero (layout: _layouts/about.liquid)
hero:
  eyebrow: PhD student · University of Illinois Urbana-Champaign
  lead: >-
    I study <strong>how much numerical precision softmax attention in LLMs actually needs</strong>, and what that means for faster
    attention kernels and for pretraining.
  buttons:
    - label: Read the explainer →
      url: /softmax/
    - label: Watch the video
      url: "#recent-videos"
    - label: Publications
      url: /publications/
  chips:
    - LLM efficiency
    - GPU kernels
    - AI infrastructure
    - Scientific computing

# Profile panel next to the hero
profile:
  image: prof_pic.png
  role: PhD student, UIUC
  facts:
    - label: Advisor
      value: <a href="https://arts.npre.illinois.edu/">Prof. Tomasz Kozlowski</a>
    - label: Contact
      value: <a href="mailto:szhu48@illinois.edu">szhu48@illinois.edu</a>
    - label: Previously
      value: Tsinghua University · Southeast University
    - label: Code
      value: <a href="https://github.com/Soren-Shangzhen">github.com/Soren-Shangzhen</a>

# Grid next to the About text
focus:
  - title: Softmax sensitivity
    text: Which parts of softmax a frozen pretrained LLM actually depends on.
  - title: Attention kernels
    text: Turning that tolerance into a faster attention kernel inside FlashAttention-4.
  - title: Quantized-softmax pretraining
    text: What changes when a transformer is trained with a coarse softmax from the start.
  - title: Scientific computing
    text: PDE inverse problems, Monte Carlo radiation transport, and 3D field reconstruction.

# Recent Videos section (newest first)
videos:
  - id: 9vOJEx41qkk
    title: How Much Softmax Do LLMs Need?
    date: 2026-10-15
    post: /blog/2026/how-much-softmax-video/

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

latest_posts:
  enabled: true
  limit: 3 # number of posts shown on the home page
---

I am a PhD student at the University of Illinois Urbana-Champaign, advised by [Prof. Tomasz Kozlowski](https://arts.npre.illinois.edu/).

My current research asks how much numerical precision softmax attention actually needs. I study which parts of softmax a pretrained LLM depends on, how to turn that into faster attention kernels (for example, a calibration-free variant inside FlashAttention-4), and what changes when a transformer is pretrained with a coarse, quantized softmax from the start. I am broadly interested in LLM efficiency, GPU kernels, and AI infrastructure.

Before moving to machine learning, I worked on PDE-based inverse problems, Monte Carlo radiation transport (FLUKA, MCNP, Serpent), and 3D radiation-field reconstruction from sparse measurements. I received my master's degree from Tsinghua University and my bachelor's degree from Southeast University.
