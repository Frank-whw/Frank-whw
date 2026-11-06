# Hongwei Wang (Frank)

I’m a third-year undergraduate studying **Data Science and Big Data Technology** at **East China Normal University**. My work focuses on LLM serving and inference performance, especially how scheduling, caching, and parallelism affect latency and throughput.

[Personal website](https://frank-whw.com/) · [Technical blog](https://frank-whw.com/blog)

## Experience

**AI Systems Software Intern, SysLab · Shanghai Innovation Institute** (May 2026–present)  
Benchmark SGLang deployments on multi-GPU systems and use workload replay, ablation studies, and profiling to investigate performance bottlenecks.

**AIGC R&D Intern · Tezign** (Feb–May 2026)  
Contributed to multi-agent workflows and structured LLM outputs for AI products.

## Selected work

- Compared tensor-parallel configurations for DeepSeek-V4-Flash and traced a latency spike to DeepGEMM JIT compilation. [Performance write-up](https://frank-whw.com/blog/articles/deepseek-v4-flash-inference-optimization)
- Proposed using a prefill execution-time budget to limit interruptions to active decoding. [SGLang RFC #45415](https://github.com/sgl-project/sglang/issues/45415)
- Reproduced a CUDA IPC weight-cache loading failure for a model with MXFP4 expert weights. [SGLang issue #39762](https://github.com/sgl-project/sglang/issues/39762)
