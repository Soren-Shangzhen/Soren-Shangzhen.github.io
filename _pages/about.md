---
layout: about
title: about
permalink: /
subtitle: PhD student, <a href='https://illinois.edu/'>University of Illinois Urbana-Champaign</a>

profile:
  align: right
  image: prof_pic.png
  image_circular: true # crops the image to make it circular
  more_info: >
    <p><a href="mailto:szhu48@illinois.edu">szhu48@illinois.edu</a></p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a PhD student at the University of Illinois Urbana-Champaign, advised by [Prof. Tomasz Kozlowski](https://arts.npre.illinois.edu/).

My current research asks how much numerical precision softmax attention actually needs. I study which parts of softmax a pretrained LLM depends on, how to turn that into faster attention kernels (for example, a calibration-free variant inside FlashAttention-4), and what changes when a transformer is pretrained with a coarse, quantized softmax from the start. I am broadly interested in LLM efficiency, GPU kernels, and AI infrastructure.

Before moving to machine learning, I worked on PDE-based inverse problems, Monte Carlo radiation transport (FLUKA, MCNP, Serpent), and 3D radiation-field reconstruction from sparse measurements. I received my master's degree from Tsinghua University and my bachelor's degree from Southeast University.

A short explainer of my recent work: [How Much Softmax Do You Need in LLMs?](/softmax/)
