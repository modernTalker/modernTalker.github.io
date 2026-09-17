---
layout: about
title: About
permalink: /
subtitle: PhD Student in Computer Science at Columbia University

profile:
  align: right
  image: photo1_crop.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>DAP Lab, Columbia University</p>
    <p>New York, NY</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

# announcements:
#   enabled: true # includes a list of news items
#   scrollable: true # adds a vertical scroll bar if there are more than 3 news items
#   limit: 5 # leave blank to include all the news in the `_news` folder

# latest_posts:
#   enabled: true
#   scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
#   limit: 3 # leave blank to include all the blog posts
---

<!-- I am a Machine Learning Researcher at **Yandex Research** (ML Residency under Artem Babenko), working at the intersection of **efficient deep learning**, **theoretical optimization**, and **large-scale distributed systems**.

My research centers on **efficiency in all embodiments**: memory, time, communication, and theoretical guarantees. It began with foundational work on **stochastic variational inequalities** and **zero-order (gradient-free) optimization**, inspired by the pioneering framework of Alexander Beznosikov. This led to practical innovations like **memory-efficient LLM fine-tuning via zero-order methods**, reducing memory footprint by 50%—culminating in the development of **ZO-Library**, an open-source toolkit for zero-order optimization.

Parallel to this, I became fascinated by the **learning dynamics of Transformers**. In collaboration with Andrey Grabovoy, we are closing the theoretical gap in understanding how these models evolve during training, connecting empirical scaling laws to rigorous dynamical systems analysis. Ideas like **orthogonalization** and **Muon-style updates** emerge naturally in this pursuit.

My engineering experience at **Yandex (Personalization R&D)**—where I accelerated data pipelines 20× and improved ranking metrics—grounds my research in real-world constraints.

Today, these threads converge in my work on **asynchronous pipeline parallelism** and **multi-cluster learning**, where theoretical insight and systems engineering must co-evolve to scale AI responsibly.

<a href="/publications/">Publications</a> • <a href="/projects/">Projects</a> • <a href="https://github.com/modernTalker/zero-order-optimization/tree/dev">ZO-Library</a> -->

I work on **efficient large-scale LLM training**, pretraining and post-training, with a focus on **parallelism**, **optimization**, and **scaling laws**.

My research began under the supervision of [Alexander Beznosikov](https://scholar.google.com/citations?user=hVVJR-sAAAAJ&hl), where I developed algorithms for **variational inequalities** and **parameter-free optimization**, then shifted to **memory-efficient and zeroth-order (ZO) methods**. These contributions led to the development of [**ZO-Library**](https://github.com/modernTalker/zero-order-optimization/tree/dev), a PyTorch-style open-source framework for ZO optimization in fine-tuning.

My bachelor thesis, supervised by [Andrey Grabovoy](https://scholar.google.com/citations?user=ZtI9pgsAAAAJ&hl), provides the first complete analytical Hessian for **LayerNorm** and **feedforward sublayers**, completing the second-order characterization of the **full Transformer block**.

At [Yandex Research](https://research.yandex.com/) under [Artem Babenko](https://scholar.google.com/citations?user=2Kv3JP0AAAAJ&hl), and in collaboration with [Samuel Horváth](https://scholar.google.com/citations?user=k252J7kAAAAJ&hl), I worked on **asynchronous pipeline parallelism** for large-scale LLM pretraining. I am now extending this line towards **hyperparameter transfer and scaling laws** for asynchronous pretraining.

Currently, I am a PhD student at **Columbia University**, in the [DAP Lab](https://daplab.cs.columbia.edu/), advised by [Eugene Wu](https://scholar.google.com/citations?user=X53rkecAAAAJ) and [Kostis Kaffes](https://scholar.google.com/citations?user=swf47vcAAAAJ). I work on **post-training efficiency**: the **optimization dynamics of RL post-training (RLVR)**, and **staleness mitigation for asynchronous post-training** with parallel rollout generation.
