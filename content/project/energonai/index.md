---
title: EnergonAI
date: 2022-02-01
external_link: https://github.com/hpcaitech/EnergonAI
tags:
  - Larger Model Inference
  - High Performance Computing
---

A service framework for large-scale model inference, Energon-AI has the following characteristics:

Parallelism for Large-scale Models: With tensor parallel operations, pipeline parallel wrapper, distributed checkpoint loading, and customized CUDA kernel, EnergonAI can enable efficient parallel inference for larges-scale models.
Pre-built large models: There are pre-built implementation for popular models, such as OPT. It supports the cache technique for the generation task and distributed parameter loading.
Engine encapsulation： There has an abstraction layer called engine. It encapsulates the single instance multiple devices (SIMD) execution with the remote procedure call, making it acts as the single instance single device (SISD) execution.
An online service system: Based on FastAPI, users can launch a web service of the distributed infernce quickly. The online service makes special optimizations for the generation task. It adopts both left padding and bucket batching techniques for improving the efficiency.
For models trained by Colossal-AI, they can be easily transferred to Energon-AI. For single-device models, they require manual coding works to introduce tensor parallelism and pipeline parallelism.
<!--more-->
