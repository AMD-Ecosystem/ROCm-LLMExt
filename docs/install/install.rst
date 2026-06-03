.. meta::
    :description: ROCm-LLMExt installation
    :keywords: ROCm, LLM, AMD, Instinct, GPU, computer, graphics, python, toolkit, accelerated, verl, Stanford Megatron-LM, Megablocks, llama.cpp, ray, FlashInfer

.. _linux-install:

**************************************************************************************
Install ROCm-LLMExt
**************************************************************************************

This topic provides brief guidance and recommendations on setting up your 
environment for LLM workloads. This includes verifying prerequisites before
installing ROCm-LLMExt frameworks and libraries.

System requirements
======================================================================================

The ROCm-LLMExt components are all supported on AMD Instinct MI300X GPUs.
Individual components also support additional hardware configurations.

Before installing any ROCm-LLMExt component, verify that your system meets the hardware
and software prerequisites for each component, as outlined in the :ref:`llmext-compat-matrix` page.

Install ROCm-LLMExt components
======================================================================================

Each component has distinct prerequisite and environment requirements. To avoid dependency
conflicts and configuration errors, components must be installed individually rather than
through a unified installation process.

The installation instructions for each component on ROCm can be found as follows: 

* `ComfyUI <https://rocm.docs.amd.com/projects/comfyui/en/docs-26.04/install/comfyui-install.html>`__
* `FlashInfer on ROCm <https://rocm.docs.amd.com/projects/flashinfer/en/docs-26.03/install/flashinfer-install.html>`__
* `llama.cpp on ROCm <https://rocm.docs.amd.com/projects/llama-cpp/en/docs-26.02/install/llama-cpp-install.html>`__
* `Ray on ROCm <https://rocm.docs.amd.com/projects/ray/en/docs-26.02/install/ray-install.html>`__
* `ROCm-RAG <https://rocm.docs.amd.com/projects/rocm-rag/en/docs-26.04/install/configure-framework.html>`__
* `Triton Inference Server on ROCm <https://rocm.docs.amd.com/projects/triton-inference-server/en/docs-26.03/install/triton-inference-server-install.html>`__
* `verl on ROCm <https://rocm.docs.amd.com/projects/verl/en/docs-26.02/install/verl-install.html>`__
