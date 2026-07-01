<h1 align="center">hi, i'm jahnavi 👋</h1>

<p align="center">
  <b>ML Systems · Inference Infrastructure · Applied AI</b><br/>
  MS Computer Engineering @ NYU · CILVR / GRAIL Lab
</p>

<p align="center">
  <img src="https://img.shields.io/badge/NYU%20MS%20Computer%20Engineering-57068c?style=flat-square" />
  <img src="https://img.shields.io/badge/ML%20%2F%20AI%20Engineer-4f46e5?style=flat-square" />
  <img src="https://img.shields.io/badge/Open%20to%20Work-16a34a?style=flat-square" />
  <a href="https://linkedin.com/in/jahnavi-yelamanchi"><img src="https://img.shields.io/badge/LinkedIn-0a66c2?style=flat-square&logo=linkedin&logoColor=white" /></a>
</p>

---

I work across the ML stack — GPU kernels, inference serving infra, and LLM-powered products. Most recently a Graduate Researcher at **NYU CILVR (GRAIL Lab)** under Prof. Lerrel Pinto on visuo-tactile world models for robot perception. Prior research at NUS (multilingual representation learning) and IIT Bombay E-Yantra (robotics control).

Currently targeting **MLE / AI Engineer** roles.

---

### ✦ Projects

**[forge](https://github.com/jahnavi-yelamanchi/forge)** — FlashAttention-style fused causal attention kernel in Triton for GPT-2. Up to **18.9× faster** than naive PyTorch, ~33× less HBM traffic, matching PyTorch SDPA within ~2% end-to-end. Includes fused backward, MLP/GELU epilogue, autotuning, and profiling on A100.
`Triton` `CUDA` `PyTorch` `Modal A100`

**[surge](https://github.com/jahnavi-yelamanchi/surge)** — Reproducible benchmarking harness for vLLM serving on Llama-3-8B. Tunes PagedAttention, continuous batching, and KV-cache eviction knobs against a fixed tail-latency SLO. Custom async load generator with Poisson/bursty traffic. Runs serverless on Modal.
`vLLM` `PyTorch` `Modal` `Python`

**[cutdown](https://github.com/jahnavi-yelamanchi/cutdown)** — Full-stack ML system that ranks short clips from long-form video. Compares a transcript-only baseline against a multimodal scorer (frozen video embeddings + lightweight trainable ranker head). FastAPI backend, Next.js frontend, evaluated with precision@k.
`FastAPI` `Next.js` `TypeScript` `Python`

**[askmydb](https://github.com/jahnavi-yelamanchi/askmydb)** — Natural-language → SQL analytics copilot. Schema-aware prompting + OpenAI function calling forces structured SQL output; validated read-only before hitting Postgres. Auto-renders bar/line charts from results. **93% execution accuracy** on a 15-case NL→SQL eval suite. Live demo.
`FastAPI` `PostgreSQL` `React` `Docker` `OpenAI`

---

### ✦ Stack

<p>
  <img src="https://skillicons.dev/icons?i=python,cpp,pytorch,docker,react,ts,postgres,linux&perline=8" />
</p>

<p>
  <img src="https://img.shields.io/badge/Triton-EE4C2C?style=flat-square" />
  <img src="https://img.shields.io/badge/CUDA-76b900?style=flat-square&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorRT-76b900?style=flat-square&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/vLLM-1a1a2e?style=flat-square" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white" />
</p>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=jahnavi-yelamanchi&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&rank_icon=github" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jahnavi-yelamanchi&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" height="160" />
</p>
