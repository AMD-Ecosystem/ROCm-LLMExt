# AMD LLM Extension

AMD LLM Extension is an open-source software toolkit built on the ROCm platform for large language model (LLM) extensions, integrations, and performance enablement on AMD GPUs. The domain brings together training, post-training, inference, and orchestration components to make modern LLM stacks practical and reproducible on AMD hardware.

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

AMD LLM Extension provides reference integrations, build instructions, patches when required, benchmarks, and examples for the following projects:

- Verl: reinforcement learning and post-training workflows for LLMs
- Ray: distributed execution framework for training, inference, and serving
- FlashInfer: optimized inference operators such as attention and decoding kernels
- MegaBlocks: high-performance Mixture-of-Experts building blocks
- Stanford Megatron-LM: large-scale transformer training using Megatron-style parallelism
- Llama.cpp: lightweight and portable LLM inference for servers, desktops, edge devices and HPC environments

## Documentation

Refer to the individual component pages for documentation on system requirements, installation instructions and examples.

- [verl](https://github.com/AMD-Ecosystem/verl)
- [Ray](https://github.com/AMD-Ecosystem/ray)
- [llama.cpp](https://github.com/AMD-Ecosystem/llama.cpp)
- [FlashInfer](https://github.com/AMD-Ecosystem/flashinfer)
- [Triton Inference Server](https://github.com/AMD-Ecosystem/triton-inference-server-server)
 
