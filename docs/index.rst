.. meta::
  :description: Learn about the features and capabilities of LLM Extension
  :keywords: ROCm, simulation, AMD, Instinct, GPU, physics, numerical, solvers, Taichi, GSplat, Gaussian, Splatting, PyTorch, HIP, multi, scaling, high, performance, computing, HPC, real-time, rendering, volumetric, fluid, dynamics, rigid, body, particle, sparse, voxel, grids, differentiable, 3D, vision, computer, graphics, robotics, scientific, toolkit, accelerated

.. rocmds-index:

********************************************************************
AMD LLM Extension documentation
********************************************************************

AMD LLM Extension is an open-source software toolkit built
on the ROCm platform for large language model (LLM) extensions,
integrations, and performance enablement on AMD GPUs. The domain
brings together training, post-training, inference, and orchestration
components to make modern LLM stacks practical and reproducible on
AMD hardware.

.. list-table::
   :header-rows: 1
   :widths: 30 70

   * - LLM Task
     - Features
   * - Training
     - - Large-scale transformer training
       - Distributed parallelism (data, tensor, and pipeline)
       - Mixed precision and performance tuning
       - Mixture-of-Experts (MoE) enablement
   * - Post-training and alignment
     - - Reinforcement learning and post-training workflows
       - Scalable experimentation
       - Reproducible configurations
   * - Inference and serving
     - - High-throughput decoding and low-latency serving
       - Optimized attention and inference operators
       - Lightweight and edge-friendly inference paths
   * - Distributed execution
     - - Multi-node orchestration
       - Cluster bring-up and scheduling
       - Batch and online inference pipelines

The AMD LLM Extension source code is hosted on GitHub at `https://github.com/AMD-Ecosystem/ROCm-LLMExt <https://github.com/AMD-Ecosystem/ROCm-LLMExt>`__.

.. note::

   AMD LLM Extension 26.02 includes targeted updates to four components (verl, Ray, llama.cpp, and FlashInfer);
   two components remain unchanged (Stanford Megatron-LM and Megablocks).

AMD LLM Extension documentation is organized into the following categories:

.. grid:: 2
  :gutter: 3

  .. grid-item-card:: Install

    * :ref:`linux-install`

  .. grid-item-card:: Components

    * `FlashInfer <https://rocm.docs.amd.com/projects/flashinfer/en/docs-26.02/>`__
    * `llama.cpp <https://rocm.docs.amd.com/projects/llama-cpp/en/docs-26.02/>`__
    * `Megablocks <https://rocm.docs.amd.com/projects/megablocks/en/docs-25.08/>`__
    * `Ray <https://rocm.docs.amd.com/projects/ray/en/docs-26.02/>`__
    * `Stanford Megatron-LM <https://rocm.docs.amd.com/projects/stanford-megatron-lm/en/docs-25.08/>`__
    * `verl <https://rocm.docs.amd.com/projects/verl/en/docs-26.02/>`__

  .. grid-item-card:: Resources

    * `FlashInfer on ROCm blog <https://rocm.blogs.amd.com/artificial-intelligence/flashinfer/README.html>`__
    * `llama.cpp on ROCm blog <https://rocm.blogs.amd.com/ecosystems-and-partners/llama-cpp-oct2025/README.html>`__
    * `Ray on ROCm blog <https://rocm.blogs.amd.com/ecosystems-and-partners/ray-rocm7/README.html>`__
    * `Stanford Megatron-LM and Megablocks on ROCm blog <https://rocm.blogs.amd.com/artificial-intelligence/megablocks/README.html>`__
    * `verl on ROCm blog <https://rocm.blogs.amd.com/artificial-intelligence/verl-large-scale-rocm7/README.html>`__

To contribute to the documentation, see `Contributing to ROCm  <https://rocm.docs.amd.com/en/latest/contribute/contributing.html>`__.

You can find licensing information on the :doc:`Licensing <about/license>` page.
