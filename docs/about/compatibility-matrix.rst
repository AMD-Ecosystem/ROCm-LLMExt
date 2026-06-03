.. meta::
    :description: ROCm-LLMExt compatibility matrix
    :keywords: ROCm, LLM, AMD, Instinct, GPU, computer, graphics, python, toolkit, accelerated, verl, Stanford Megatron-LM, Megablocks, llama.cpp, ray, FlashInfer

.. _llmext-compat-matrix:

**************************************************************************************
ROCm-LLMExt compatibility matrix
**************************************************************************************

.. |docker-icon| raw:: html

   <i class="fab fa-docker"></i>

Use the following matrix to view the ROCm-LLMExt compatibility and system requirements across releases:

.. role:: version-start

.. table::
   :width: 65%
   :widths: 20 10 16 12 6 8 6 10
   :align: left
   :class: compat-matrix format-big-table

   +------------------------+----------------------------------------------------+------------------+--------------+--------+----------------------+----------------+--------------------------------------------+
   |  ROCm-LLMExt version   |                  Component                         | AMD Instinct GPU | ROCm version | Ubuntu |       PyTorch        |    Python      |             Docker Hub                     |
   +========================+====================================================+==================+==============+========+======================+================+============================================+
   | :version-start:`26.04` | `ComfyUI 0.18.2                                    | MI355X,          | 7.2.0,       | 24.04, | 2.10.0a0+git449b176  | 3.12.3         | |docker-icon| `rocm/comfyui                |
   |                        | <https://rocm.docs.amd.com/projects/               | MI325X,          | 7.1.0        | 22.04  |                      |                | <https://hub.docker.com/r/rocm/            |
   |                        | comfyui/en/docs-26.04/install/                     | MI300X           |              |        |                      |                | comfyui/tags?name=                         |
   |                        | comfyui-install.html>`__                           |                  |              |        |                      |                | comfyui-0.18.2.amd0>`__                    |
   +                        +----------------------------------------------------+------------------+--------------+--------+----------------------+----------------+--------------------------------------------+
   |                        | `ROCm-RAG 1.0.0                                    | MI300X           | 6.4.1        | 22.04  | N/A                  | N/A            | |docker-icon| `rocm/rocm-rag               |
   |                        | <https://rocm.docs.amd.com/projects/               |                  |              |        |                      |                | <https://hub.docker.com/r/rocm/            |
   |                        | rocm-rag/en/docs-26.04/install/                    |                  |              |        |                      |                | rocm-rag/tags?name=                        |
   |                        | configure-framework.html>`__                       |                  |              |        |                      |                | rocm-rag-1.0.0-rocm6.4.1>`__               |
   +------------------------+----------------------------------------------------+------------------+--------------+--------+----------------------+----------------+--------------------------------------------+
   | :version-start:`26.03` | `FlashInfer 0.5.3                                  | MI355X,          | 7.2.0,       | 24.04  | 2.9.1                | 3.12.9         | |docker-icon| `rocm/flashinfer             |
   |                        | <https://rocm.docs.amd.com/projects/               | MI325X,          | 7.0.2        |        |                      |                | <https://hub.docker.com/r/rocm/            |
   |                        | flashinfer/en/docs-26.03/install/                  | MI300X           |              |        |                      |                | flashinfer/tags?name=                      |
   |                        | flashinfer-install.html>`__                        |                  |              |        |                      |                | flashinfer-0.5.3.amd1>`__                  |
   +                        +----------------------------------------------------+------------------+--------------+--------+----------------------+----------------+--------------------------------------------+
   |                        | `Triton Inference Server 25.12                     | MI355X,          | 7.2.0        | 24.04  | N/A                  | 3.12.9         | |docker-icon| `rocm/tritoninferenceserver  |
   |                        | <https://rocm.docs.amd.com/projects/               | MI300X           |              |        |                      |                | <https://hub.docker.com/r/rocm/            |
   |                        | triton-inference-server/en/docs-26.03/install/     |                  |              |        |                      |                | tritoninferenceserver/tags?name=           |
   |                        | triton-inference-server-install.html>`__           |                  |              |        |                      |                | tritoninferenceserver-25.12.amd1>`__       |
   +------------------------+----------------------------------------------------+------------------+--------------+--------+----------------------+----------------+--------------------------------------------+
   | :version-start:`26.02` | `FlashInfer 0.2.5                                  | MI325X,          | 7.1.1        | 24.04  | 2.8.0                | 3.12.9         | |docker-icon| `rocm/flashinfer             |
   |                        | <https://rocm.docs.amd.com/projects/               | MI300X           |              |        |                      |                | <https://hub.docker.com/r/rocm/            |
   |                        | flashinfer/en/docs-26.02/install/                  |                  |              |        |                      |                | flashinfer/tags?name=                      |
   |                        | flashinfer-install.html>`__                        |                  |              |        |                      |                | flashinfer-0.2.5.amd2>`__                  |
   +                        +----------------------------------------------------+------------------+--------------+--------+----------------------+----------------+--------------------------------------------+
   |                        | `Ray 2.51.1                                        | MI300X           | 7.0.0        | 22.04  | 2.9.0a0+git1c57644   | 3.12.12        | |docker-icon| `rocm/ray                    |
   |                        | <https://rocm.docs.amd.com/projects/               |                  |              |        |                      |                | <https://hub.docker.com/r/rocm/            |
   |                        | ray/en/docs-26.02/install/                         |                  |              |        |                      |                | ray/tags?name=ray-2.51>`__                 |
   |                        | ray-install.html>`__                               |                  |              |        |                      |                |                                            |
   +                        +----------------------------------------------------+------------------+--------------+--------+----------------------+----------------+--------------------------------------------+
   |                        | `verl 0.6.0                                        | MI300X           | 7.0.0        | 22.04  | 2.9.0                | 3.12.11        | |docker-icon| `rocm/verl                   |
   |                        | <https://rocm.docs.amd.com/projects/               |                  |              |        |                      |                | <https://hub.docker.com/r/rocm/            |
   |                        | verl/en/docs-26.02/install/                        |                  |              |        |                      |                | verl/tags?name=                            |
   |                        | verl-install.html>`__                              |                  |              |        |                      |                | verl-0.6.0>`__                             |
   +                        +----------------------------------------------------+------------------+--------------+--------+----------------------+----------------+--------------------------------------------+
   |                        | `llama.cpp b6652                                   | MI325X,          | 7.0.0        | 24.04, | N/A                  | N/A            | |docker-icon| `rocm/llama.cpp              |
   |                        | <https://rocm.docs.amd.com/projects/               | MI300X,          |              | 22.04  |                      |                | <https://hub.docker.com/r/rocm/            |
   |                        | llama-cpp/en/docs-26.02/install/                   | MI210            |              |        |                      |                | llama.cpp/tags?name=                       |
   |                        | llama-cpp-install.html>`__                         |                  |              |        |                      |                | llama.cpp-b6652.amd0>`__                   |
   +------------------------+----------------------------------------------------+------------------+--------------+--------+----------------------+----------------+--------------------------------------------+
   | :version-start:`25.09` | `FlashInfer 0.2.5                                  | MI300X           | 6.4.1        | 24.04  | 2.7.1                | 3.12.9         | |docker-icon| `rocm/flashinfer             |
   |                        | <https://rocm.docs.amd.com/projects/               |                  |              |        |                      |                | <https://hub.docker.com/r/rocm/            |
   |                        | flashinfer/en/docs-25.09/install/                  |                  |              |        |                      |                | flashinfer/tags?name=                      |
   |                        | flashinfer-install.html>`__                        |                  |              |        |                      |                | flashinfer-0.2.5_rocm6>`__                 |
   +                        +----------------------------------------------------+------------------+--------------+--------+----------------------+----------------+--------------------------------------------+
   |                        | `llama.cpp b6356                                   | MI325X,          | 7.0.0,       | 24.04, | N/A                  | N/A            | |docker-icon| `rocm/llama.cpp              |
   |                        | <https://rocm.docs.amd.com/projects/               | MI300X,          | 6.4.3,       | 22.04  |                      |                | <https://hub.docker.com/r/rocm/            |
   |                        | llama-cpp/en/docs-25.09/install/                   | MI210            | 6.4.2,       |        |                      |                | llama.cpp/tags?name=                       |
   |                        | llama-cpp-install.html>`__                         |                  | 6.4.1        |        |                      |                | llama.cpp-b6356>`__                        |
   +------------------------+----------------------------------------------------+------------------+--------------+--------+----------------------+----------------+--------------------------------------------+
   | :version-start:`25.08` | `Ray 2.48.0.post0                                  | MI300X,          | 6.4.1        | 24.04  | 2.6.0+git684f6f2     | 3.12.10        | |docker-icon| `rocm/ray                    |
   |                        | <https://rocm.docs.amd.com/projects/               | MI210            |              |        |                      |                | <https://hub.docker.com/r/rocm/            |
   |                        | ray/en/docs-25.08/install/                         |                  |              |        |                      |                | ray/tags?name=ray-2.48>`__                 |
   |                        | ray-install.html>`__                               |                  |              |        |                      |                |                                            |
   +                        +----------------------------------------------------+------------------+--------------+--------+----------------------+----------------+--------------------------------------------+
   |                        | `llama.cpp b5997                                   | MI300X,          | 6.4.0        | 24.04  | N/A                  | N/A            | |docker-icon| `rocm/llama.cpp              |
   |                        | <https://rocm.docs.amd.com/projects/               | MI210            |              |        |                      |                | <https://hub.docker.com/r/rocm/            |
   |                        | llama-cpp/en/docs-25.08/install/                   |                  |              |        |                      |                | llama.cpp/tags?name=                       |
   |                        | llama-cpp-install.html>`__                         |                  |              |        |                      |                | llama.cpp-b5997>`__                        |
   +                        +----------------------------------------------------+------------------+--------------+--------+----------------------+----------------+--------------------------------------------+
   |                        | `verl 0.3.0.post0                                  | MI300X           | 6.2.0        | 20.04  | 2.5.0                | 3.9.19         | |docker-icon| `rocm/verl                   |
   |                        | <https://rocm.docs.amd.com/projects/               |                  |              |        |                      |                | <https://hub.docker.com/r/rocm/            |
   |                        | verl/en/docs-25.08/install/                        |                  |              |        |                      |                | verl/tags?name=                            |
   |                        | verl-install.html>`__                              |                  |              |        |                      |                | verl-0.3.0>`__                             |
   +------------------------+----------------------------------------------------+------------------+--------------+--------+----------------------+----------------+--------------------------------------------+
