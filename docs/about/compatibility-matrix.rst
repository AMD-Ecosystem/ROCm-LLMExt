.. meta::
    :description: AMD LLM Extension compatibility matrix
    :keywords: ROCm, LLM, AMD, Instinct, GPU, computer, graphics, python, toolkit, accelerated, verl, Stanford Megatron-LM, Megablocks, llama.cpp, ray, FlashInfer

.. _llmext-compat-matrix:

**************************************************************************************
AMD LLM Extension compatibility matrix
**************************************************************************************

.. |docker-icon| raw:: html

   <i class="fab fa-docker"></i>

Use the following matrix to view the AMD LLM Extension compatibility and system requirements across releases:

.. role:: version-start

.. table::
   :width: 65%
   :widths: 20 10 16 12 6 8 6 10
   :align: left
   :class: compat-matrix format-big-table

   +------------------------------+----------------------------------------------+------------------+--------------+--------+--------------------+----------------+------------------------------------+
   |  AMD LLM Extension version   |                  Component                   | AMD Instinct GPU | ROCm version | Ubuntu |      PyTorch       |    Python      |             Docker Hub             |
   +==============================+==============================================+==================+==============+========+====================+================+====================================+
   | :version-start:`25.08`       | `Ray 2.48.0.post0                            | MI300X,          | 6.4.1        | 24.04  | 2.6.0+git684f6f2   | 3.12.10        | |docker-icon| `rocm/ray            |
   |                              | <https://rocm.docs.amd.com/projects/         | MI210            |              |        |                    |                | <https://hub.docker.com/r/rocm/    |
   |                              | ray/en/docs-25.08/install/                   |                  |              |        |                    |                | ray/tags?name=ray-2.48>`__         |
   |                              | ray-install.html>`__                         |                  |              |        |                    |                |                                    |
   +                              +----------------------------------------------+------------------+--------------+--------+--------------------+----------------+------------------------------------+
   |                              | `llama.cpp b5997                             | MI300X,          | 6.4.0        | 24.04  | N/A                | N/A            | |docker-icon| `rocm/llama.cpp      |
   |                              | <https://rocm.docs.amd.com/projects/         | MI210            |              |        |                    |                | <https://hub.docker.com/r/rocm/    |
   |                              | llama-cpp/en/docs-25.08/install/             |                  |              |        |                    |                | llama.cpp/tags?name=               |
   |                              | llama-cpp-install.html>`__                   |                  |              |        |                    |                | llama.cpp-b5997>`__                |
   +                              +----------------------------------------------+------------------+--------------+--------+--------------------+----------------+------------------------------------+
   |                              | `Megablocks 0.7.0                            | MI300X           | 6.3.0        | 24.04  | 2.4.0              | 3.12.9         | |docker-icon| `rocm/megablocks     |
   |                              | <https://rocm.docs.amd.com/projects/         |                  |              |        |                    |                | <https://hub.docker.com/r/rocm/    |
   |                              | megablocks/en/docs-25.08/install/            |                  |              |        |                    |                | megablocks/tags?name=              |
   |                              | megablocks-install.html>`__                  |                  |              |        |                    |                | megablocks-0.7.0>`__               |
   +                              +----------------------------------------------+------------------+--------------+--------+--------------------+----------------+------------------------------------+
   |                              | `Stanford Megatron-LM 85f95ae                | MI300X           | 6.3.0        | 24.04  | 2.4.0              | 3.12.9         | |docker-icon| `rocm/stanford-      |
   |                              | <https://rocm.docs.amd.com/projects/         |                  |              |        |                    |                | megatron-lm                        |
   |                              | stanford-megatron-lm/en/docs-25.08/install/  |                  |              |        |                    |                | <https://hub.docker.com/r/rocm/    |
   |                              | stanford-megatron-lm-install.html>`__        |                  |              |        |                    |                | stanford-megatron-lm/tags?name=    |
   |                              |                                              |                  |              |        |                    |                | stanford-megatron-lm85f95ae>`__    |
   +                              +----------------------------------------------+------------------+--------------+--------+--------------------+----------------+------------------------------------+
   |                              | `verl 0.3.0.post0                            | MI300X           | 6.2.0        | 20.04  | 2.5.0              | 3.9.19         | |docker-icon| `rocm/verl           |
   |                              | <https://rocm.docs.amd.com/projects/         |                  |              |        |                    |                | <https://hub.docker.com/r/rocm/    |
   |                              | verl/en/docs-25.08/install/                  |                  |              |        |                    |                | verl/tags?name=                    |
   |                              | verl-install.html>`__                        |                  |              |        |                    |                | verl-0.3.0>`__                     |
   +------------------------------+----------------------------------------------+------------------+--------------+--------+--------------------+----------------+------------------------------------+