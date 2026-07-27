.. meta::
    :description: AMD LLM Extension installation
    :keywords: ROCm, LLM, AMD, Instinct, GPU, computer, graphics, python, toolkit, accelerated, verl, Stanford Megatron-LM, Megablocks, llama.cpp, ray, FlashInfer

.. _linux-install:

**************************************************************************************
Install AMD LLM Extension
**************************************************************************************

This topic provides brief guidance and recommendations on setting up your 
environment for LLM workloads. This includes verifying prerequisites before
installing AMD LLM Extension frameworks and libraries.

System requirements
======================================================================================

The AMD LLM Extension components are all supported on AMD Instinct MI300X GPUs.
Individual components also support additional hardware configurations.

Before installing any AMD LLM Extension component, verify that your system meets the hardware
and software prerequisites for each component, as outlined in the :ref:`llmext-compat-matrix` page.

Install AMD LLM Extension components
======================================================================================

Each component has distinct prerequisite and environment requirements. To avoid dependency
conflicts and configuration errors, components must be installed individually rather than
through a unified installation process.

The installation instructions for each component, on ROCm can be found as follows: 

* `FlashInfer on ROCm <https://rocm.docs.amd.com/projects/flashinfer/en/docs-26.02/install/flashinfer-install.html>`__
* `llama.cpp on ROCm <https://rocm.docs.amd.com/projects/llama-cpp/en/docs-26.02/install/llama-cpp-install.html>`__
* `Megablocks on ROCm <https://rocm.docs.amd.com/projects/megablocks/en/docs-25.08/install/megablocks-install.html>`__
* `Ray on ROCm <https://rocm.docs.amd.com/projects/ray/en/docs-26.02/install/ray-install.html>`__
* `Stanford Megatron-LM on ROCm <https://rocm.docs.amd.com/projects/stanford-megatron-lm/en/docs-25.08/install/stanford-megatron-lm-install.html>`__
* `verl on ROCm <https://rocm.docs.amd.com/projects/verl/en/docs-26.02/install/verl-install.html>`__