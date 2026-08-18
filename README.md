# Jahnavi Yelamanchi

## Machine Learning & Software Engineer

**Foundation Models · ML Systems · GPU / Inference · Embodied AI · AI Infrastructure**

M.S. Computer Engineering, NYU Tandon · **May 2026 · 3.83 GPA**

[**View Portfolio**](https://jahnavi-yelamanchi.github.io/) · [LinkedIn](https://www.linkedin.com/) · [Repositories](https://github.com/jahnavi-yelamanchi?tab=repositories) · [Résumé](https://drive.google.com/file/d/1DQtKNTDu7e0UTFF04x4_nTMyEMBYZhdO/view) · [Email](mailto:jahnaviyelamanchi03@gmail.com)

## Recruiter Quick View

- Best aligned with early-career **Machine Learning Engineering, Foundation Models, ML Systems, GPU / Inference, AI Infrastructure, and Applied AI** roles.
- Graduate research at **NYU CILVR** focused on multimodal world models, visuo-tactile learning, cross-embodiment data, and model evaluation workflows.
- ML systems research at **NYU System & AI Lab** focused on Triton kernels, GPU profiling, and inference optimization on NVIDIA A100s.
- Core differentiator: connecting **model development, ML software, GPU-aware optimization, backend infrastructure, evaluation, and deployment** into measurable end-to-end systems.

## Selected Impact

<div align="center">

| <div align="center">**18.9× faster**<br>fused Triton attention</div> | <div align="center">**17% lower latency**<br>Efficient-VAR inference on A100</div> |
| :---: | :---: |
| <div align="center">**~33× less HBM traffic**<br>fused attention kernel</div> | <div align="center">**28% higher recall**<br>rare-class defect detection</div> |
| <div align="center">**1.83× faster**<br>end-to-end GPT-2 forward</div> | <div align="center">**40× scheduler capacity**<br>accelerator-aware control plane</div> |

</div>

## Experience

**Eminent Services Corporation** · Software Engineer · *Jul 2026 to Present*  
Tested and debugged backend workflows across six product areas, increasing regression coverage by **35%** and reducing recurring defects by **25%**.

**NYU CILVR** · Graduate Researcher · *Apr 2025 to Apr 2026*  
Built multimodal ML pipelines across video, tactile, and proprioceptive data, developed world-model training and evaluation workflows, and automated Linux/Singularity experiment infrastructure for cross-embodiment learning.

**NYU System & AI Lab** · ML Systems & Inference Researcher · *Oct 2024 to Apr 2025*  
Built Triton kernels and profiled GPU memory and execution paths for generative-model inference, reducing Efficient-VAR latency by **17%** on NVIDIA A100s.

**Tata Steel** · Machine Learning Intern · *Jan 2024 to May 2024*  
Built a Python defect-detection pipeline with GAN-generated rare classes, improving rare-class recall by **28%**, and automated training-to-inference delivery with Docker and GitHub Actions.

**Samsung R&D India** · Research Intern · *Jul 2023 to Dec 2023*  
Worked on model quantization, pruning, and multimodal ML for low-latency on-device inference across vision, audio, and sensor inputs.

**HPE** · Data Science Intern · *Dec 2022 to Jan 2023*  
Built multilingual text-classification and distributed ML workflows, combining feature engineering, model training, and cloud-based experimentation.

## Featured Engineering Work

### [Forge](https://github.com/jahnavi-yelamanchi/forge) · GPU-Optimized Attention

FlashAttention-style fused causal attention implemented in Triton and integrated into GPT-2.

`Triton` · `PyTorch` · `CUDA` · `A100` · `torch.profiler`

**Evidence:** up to **18.9× faster** than naive PyTorch attention, approximately **33× less HBM traffic**, and **1.83× faster** end-to-end GPT-2 forward inference while matching PyTorch SDPA within approximately 2%.

### [CacheTrace](https://github.com/jahnavi-yelamanchi/cachetrace) · LLM Prefix-Cache Analysis

Inference analysis tool for identifying prompt patterns that silently reduce prefix-cache efficiency.

`Python` · `vLLM` · `SGLang` · `Radix Trees` · `Tokenization`

**Evidence:** simulates block-based cache behavior over real request traces, attributes cache misses to specific prompt structure, estimates inference waste, and verifies generated fixes through replay.

### [MetalGrid](https://github.com/jahnavi-yelamanchi/metalgrid) · Accelerator-Aware Distributed Infrastructure

Distributed control plane for scheduling accelerator-backed workloads.

`Go` · `Kubernetes` · `NATS` · `gRPC`

**Evidence:** built for accelerator-aware scheduling and distributed workload coordination, with stress testing across **1,346 jobs**, approximately **120 ms p95**, and zero failures in the benchmark run.

### [RoboInfer](https://github.com/jahnavi-yelamanchi/roboinfer) · Multimodal Data Reliability

Preflight validation system for multimodal embodied-AI datasets.

`Python` · `Computer Vision` · `Multimodal Data` · `LeRobot`

**Evidence:** detects temporal misalignment and corruption across visual, action, and proprioceptive streams, with explicit abstention when available signals are unreliable.

### [ModelRouter](https://github.com/jahnavi-yelamanchi/modelrouter) · Adaptive LLM Routing

LLM gateway that routes requests between local and remote models based on estimated quality risk and cost.

`FastAPI` · `Ollama` · `Docker` · `SQLite`

**Evidence:** combines model selection, fallback logic, circuit breakers, cost accounting, paired quality evaluation, deterministic canary rollouts, and rollback guardrails.

### [ShadowEval](https://github.com/jahnavi-yelamanchi/shadoweval) · Production LLM Evaluation

Shadow-deployment service for detecting model or prompt regressions before promotion.

`FastAPI` · `Docker` · `SQLite` · `Statistical Testing`

**Evidence:** replays sampled production-shaped traffic against candidate models, collects blinded paired judgments, and applies predefined statistical regression gates before promotion.

[Explore public repositories →](https://github.com/jahnavi-yelamanchi?tab=repositories)

## Where My Experience Fits

| **Role family** | **Strongest evidence** |
| --- | --- |
| **Machine Learning Engineering** | multimodal world models, production ML pipelines, retrieval, evaluation, deployment |
| **Foundation Models / Applied ML** | visuo-tactile learning, cross-embodiment modeling, representation learning, multimodal data |
| **ML Systems / Inference** | Triton kernels, A100 profiling, vLLM, prefix caching, TensorRT, model serving |
| **GPU / Performance Engineering** | kernel fusion, memory-path profiling, quantization, HBM traffic analysis, benchmarking |
| **AI Infrastructure** | MetalGrid, ModelRouter, ShadowEval, FastAPI, Kubernetes, Docker, distributed services |
| **Software Engineering for ML** | Python, C++, Go, APIs, backend workflows, testing, CI/CD, Linux systems |

## Technical Toolkit

### Machine Learning

`PyTorch` · `Transformers` · `Hugging Face` · `Computer Vision` · `Reinforcement Learning` · `Multimodal Learning` · `Embeddings` · `Retrieval` · `Model Evaluation`

### GPU & Performance

`Triton` · `CUDA` · `NVIDIA A100` · `TensorRT` · `Profiling` · `Quantization` · `KV Caching` · `Continuous Batching`

### Software & Backend

`Python` · `C++` · `Go` · `SQL` · `FastAPI` · `REST APIs` · `PostgreSQL` · `SQLite` · `Linux`

### Distributed & ML Infrastructure

`Kubernetes` · `gRPC` · `NATS` · `Docker` · `Slurm` · `Singularity` · `Modal` · `GitHub Actions`

## How I Work

> Build the model. Measure the system. Fix the bottleneck.

- Treat model quality, latency, memory, and reliability as measurable engineering constraints.
- Move comfortably between model experimentation, ML software, backend systems, and GPU execution when the problem requires it.
- Make systems reproducible with benchmarks, tests, explicit assumptions, and documented trade-offs.

## Current Focus

I am currently focused on **foundation models, efficient training and inference, GPU-aware ML, multimodal learning, LLM serving, and production AI infrastructure**, and am open to early-career roles across **Machine Learning Engineering, Foundation Models, ML Systems, GPU / Inference, AI Infrastructure, and Applied AI**.

[**View the portfolio**](https://jahnavi-yelamanchi.github.io/) · [Explore repositories](https://github.com/jahnavi-yelamanchi?tab=repositories) · [View résumé](https://drive.google.com/file/d/1DQtKNTDu7e0UTFF04x4_nTMyEMBYZhdO/view) · [Connect on LinkedIn](https://www.linkedin.com/) · [Email me](mailto:jahnaviyelamanchi03@gmail.com)
