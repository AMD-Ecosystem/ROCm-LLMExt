# AMD ROCm™ LLMExt

AMD ROCm™ LLMExt (ROCm-LLMExt) is an open-source software toolkit built on the ROCm platform for large language model (LLM) extensions, integrations, and performance enablement on AMD GPUs. The domain brings together training, post-training, inference, and orchestration components to make modern LLM stacks practical and reproducible on AMD hardware.

## Training

- Large-scale transformer training
- Distributed parallelism (data, tensor, pipeline)
- Mixed precision and performance tuning
- Mixture-of-Experts (MoE) enablement

## Post-training and alignment

- Reinforcement learning and post-training workflows
- Scalable experimentation
- Reproducible configurations

## Inference and serving

- High-throughput decoding and low-latency serving
- Optimized attention and inference operators
- Lightweight and edge-friendly inference paths

## Distributed execution

- Multi-node orchestration
- Cluster bring-up and scheduling
- Batch and online inference pipelines

## Reference integrations and projects

ROCm-LLMExt provides reference integrations, build instructions, patches when required, benchmarks, and examples for the following projects:

- ComfyUI: node-based interface for building and running image generation workflows with diffusion models
- FlashInfer: optimized inference operators such as attention and decoding kernels
- Llama.cpp: lightweight and portable LLM inference for servers, desktops, edge devices and HPC environments
- Ray: distributed execution framework for training, inference, and serving
- ROCm-RAG: retrieval-augmented generation workflows for LLMs
- Triton Inference Server: a high-performance model server for general machine learning inference
- Verl: reinforcement learning and post-training workflows for LLMs

## Documentation

Refer to the individual component pages for documentation on system requirements, installation instructions and examples.

- [ComfyUI](https://github.com/ROCm/ComfyUI)
- [FlashInfer](https://github.com/ROCm/flashinfer)
- [llama.cpp](https://github.com/ROCm/llama.cpp)
- [Ray](https://github.com/ROCm/ray)
- [ROCm-RAG](https://github.com/ROCm/rocm-rag)
- [Triton Inference Server](https://github.com/ROCm/triton-inference-server-server)
- [verl](https://github.com/ROCm/verl)
 
