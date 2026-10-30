.. meta::
    :description: AMD LLM Extension compatibility matrix
    :keywords: ROCm, LLM, AMD, Instinct, GPU, computer, graphics, python, toolkit, accelerated, verl, ray, FlashInfer, Triton Inference Server, RAG

.. _llmext-compat-matrix:

**************************************************************************************
AMD LLM Extension compatibility matrix
**************************************************************************************

Use the following matrix to view the AMD LLM Extension compatibility and system requirements across releases:

.. role:: version-start

.. |flashinfer-0-6-18-26-10-src| raw:: html

   <a href="https://github.com/AMD-Ecosystem/flashinfer/blob/release/0.6.18+amd.1/docker/Dockerfile.rocm" aria-label="Dockerfile"><i class="fab fa-github"></i></a>

.. |ray-2-59-0-26-10-src| raw:: html

   <a href="https://github.com/AMD-Ecosystem/ray/blob/release/2.59.0.amd0/docker/Dockerfile.rocm" aria-label="Dockerfile"><i class="fab fa-github"></i></a>

.. |verl-0-9-0-26-09-src| raw:: html

   <a href="https://github.com/AMD-Ecosystem/verl/blob/release/0.9.0.amd0/docker/rocm/Dockerfile.rocm" aria-label="Dockerfile"><i class="fab fa-github"></i></a>

.. |ray-2-58-0-26-09-src| raw:: html

   <a href="https://github.com/AMD-Ecosystem/ray/blob/release/2.58.0/docker/Dockerfile.rocm" aria-label="Dockerfile"><i class="fab fa-github"></i></a>

.. |verl-0-7-1-26-06-src| raw:: html

   <a href="https://hub.docker.com/r/rocm/verl/tags?name=verl-0.7.1" aria-label="rocm/verl"><i class="fab fa-docker"></i></a>

.. |ray-2-55-1-26-06-src| raw:: html

   <a href="https://hub.docker.com/r/rocm/ray/tags?name=ray-2.55" aria-label="rocm/ray"><i class="fab fa-docker"></i></a>

.. |rocm-rag-1-0-0-26-04-src| raw:: html

   <a href="https://hub.docker.com/r/rocm/rocm-rag/tags?name=rocm-rag-1.0.0-rocm6.4.1" aria-label="rocm/rocm-rag"><i class="fab fa-docker"></i></a>

.. |flashinfer-0-5-3-26-03-src| raw:: html

   <a href="https://hub.docker.com/r/rocm/flashinfer/tags?name=flashinfer-0.5.3.amd1" aria-label="rocm/flashinfer"><i class="fab fa-docker"></i></a>

.. |triton-inference-server-25-12-26-03-src| raw:: html

   <a href="https://hub.docker.com/r/rocm/tritoninferenceserver/tags?name=tritoninferenceserver-25.12.amd1" aria-label="rocm/tritoninferenceserver"><i class="fab fa-docker"></i></a>

.. |flashinfer-0-2-5-26-02-src| raw:: html

   <a href="https://hub.docker.com/r/rocm/flashinfer/tags?name=flashinfer-0.2.5.amd2" aria-label="rocm/flashinfer"><i class="fab fa-docker"></i></a>

.. |ray-2-51-1-26-02-src| raw:: html

   <a href="https://hub.docker.com/r/rocm/ray/tags?name=ray-2.51" aria-label="rocm/ray"><i class="fab fa-docker"></i></a>

.. |verl-0-6-0-26-02-src| raw:: html

   <a href="https://hub.docker.com/r/rocm/verl/tags?name=verl-0.6.0" aria-label="rocm/verl"><i class="fab fa-docker"></i></a>

.. |flashinfer-0-2-5-25-09-src| raw:: html

   <a href="https://hub.docker.com/r/rocm/flashinfer/tags?name=flashinfer-0.2.5_rocm6" aria-label="rocm/flashinfer"><i class="fab fa-docker"></i></a>

.. |ray-2-48-0-post0-25-08-src| raw:: html

   <a href="https://hub.docker.com/r/rocm/ray/tags?name=ray-2.48" aria-label="rocm/ray"><i class="fab fa-docker"></i></a>

.. |verl-0-3-0-post0-25-08-src| raw:: html

   <a href="https://hub.docker.com/r/rocm/verl/tags?name=verl-0.3.0" aria-label="rocm/verl"><i class="fab fa-docker"></i></a>

.. table::
   :widths: 10 22 14 12 8 16 8 10
   :align: left
   :class: compat-matrix format-big-table

   +---------------------------+-------------------------------------------------------------------------+--------------------------------+--------------+--------+--------------------+--------+-------------------------------------------+
   | AMD LLM Extension version | Component                                                               | AMD Instinct GPU               | ROCm version | Ubuntu | PyTorch            | Python | Docker                                    |
   +===========================+=========================================================================+================================+==============+========+====================+========+===========================================+
   | :version-start:`26.10`    | `FlashInfer 0.6.18 <flashinfer-0-6-18-26-10_>`_                         | MI300X, MI325X, MI350X, MI355X | 10.1.0       | 24.04  | 2.12.0             | 3.12   | |flashinfer-0-6-18-26-10-src|             |
   +                           +-------------------------------------------------------------------------+--------------------------------+--------------+--------+--------------------+--------+-------------------------------------------+
   |                           | `Ray 2.59.0 <ray-2-59-0-26-10_>`_                                       | MI300X, MI325X, MI350X, MI355X | 10.1.0       | 24.04  | 2.13.0             | 3.14   | |ray-2-59-0-26-10-src|                    |
   +---------------------------+-------------------------------------------------------------------------+--------------------------------+--------------+--------+--------------------+--------+-------------------------------------------+
   | :version-start:`26.09`    | `verl 0.9.0 <verl-0-9-0-26-09_>`_                                       | MI300X, MI325X, MI350X, MI355X | 10.0.0       | 24.04  | 2.12.0             | 3.12   | |verl-0-9-0-26-09-src|                    |
   +                           +-------------------------------------------------------------------------+--------------------------------+--------------+--------+--------------------+--------+-------------------------------------------+
   |                           | `Ray 2.58.0 <ray-2-58-0-26-09_>`_                                       | MI300X, MI325X, MI350X, MI355X | 10.0.0       | 24.04  | 2.12.0             | 3.14   | |ray-2-58-0-26-09-src|                    |
   +---------------------------+-------------------------------------------------------------------------+--------------------------------+--------------+--------+--------------------+--------+-------------------------------------------+
   | :version-start:`26.06`    | `verl 0.7.1 <verl-0-7-1-26-06_>`_                                       | MI300X, MI325X, MI355X         | 7.0.2        | 22.04  | 2.9.1              | 3.12   | |verl-0-7-1-26-06-src|                    |
   +                           +-------------------------------------------------------------------------+--------------------------------+--------------+--------+--------------------+--------+-------------------------------------------+
   |                           | `Ray 2.55.1 <ray-2-55-1-26-06_>`_                                       | MI300X, MI325X, MI355X         | 7.2.1        | 22.04  | 2.10.0             | 3.12   | |ray-2-55-1-26-06-src|                    |
   +---------------------------+-------------------------------------------------------------------------+--------------------------------+--------------+--------+--------------------+--------+-------------------------------------------+
   | :version-start:`26.04`    | `ROCm-RAG 1.0.0 <rocm-rag-1-0-0-26-04_>`_                               | MI300X                         | 6.4.1        | 22.04  | N/A                | N/A    | |rocm-rag-1-0-0-26-04-src|                |
   +---------------------------+-------------------------------------------------------------------------+--------------------------------+--------------+--------+--------------------+--------+-------------------------------------------+
   | :version-start:`26.03`    | `FlashInfer 0.5.3 <flashinfer-0-5-3-26-03_>`_                           | MI355X, MI325X, MI300X         | 7.2.0, 7.0.2 | 24.04  | 2.9.1              | 3.12   | |flashinfer-0-5-3-26-03-src|              |
   +                           +-------------------------------------------------------------------------+--------------------------------+--------------+--------+--------------------+--------+-------------------------------------------+
   |                           | `Triton Inference Server 25.12 <triton-inference-server-25-12-26-03_>`_ | MI355X, MI300X                 | 7.2.0        | 24.04  | N/A                | 3.12   | |triton-inference-server-25-12-26-03-src| |
   +---------------------------+-------------------------------------------------------------------------+--------------------------------+--------------+--------+--------------------+--------+-------------------------------------------+
   | :version-start:`26.02`    | `FlashInfer 0.2.5 <flashinfer-0-2-5-26-02_>`_                           | MI325X, MI300X                 | 7.1.1        | 24.04  | 2.8.0              | 3.12   | |flashinfer-0-2-5-26-02-src|              |
   +                           +-------------------------------------------------------------------------+--------------------------------+--------------+--------+--------------------+--------+-------------------------------------------+
   |                           | `Ray 2.51.1 <ray-2-51-1-26-02_>`_                                       | MI300X                         | 7.0.0        | 22.04  | 2.9.0a0+git1c57644 | 3.12   | |ray-2-51-1-26-02-src|                    |
   +                           +-------------------------------------------------------------------------+--------------------------------+--------------+--------+--------------------+--------+-------------------------------------------+
   |                           | `verl 0.6.0 <verl-0-6-0-26-02_>`_                                       | MI300X                         | 7.0.0        | 22.04  | 2.9.0              | 3.12   | |verl-0-6-0-26-02-src|                    |
   +---------------------------+-------------------------------------------------------------------------+--------------------------------+--------------+--------+--------------------+--------+-------------------------------------------+
   | :version-start:`25.09`    | `FlashInfer 0.2.5 <flashinfer-0-2-5-25-09_>`_                           | MI300X                         | 6.4.1        | 24.04  | 2.7.1              | 3.12   | |flashinfer-0-2-5-25-09-src|              |
   +---------------------------+-------------------------------------------------------------------------+--------------------------------+--------------+--------+--------------------+--------+-------------------------------------------+
   | :version-start:`25.08`    | `Ray 2.48.0.post0 <ray-2-48-0-post0-25-08_>`_                           | MI300X, MI210                  | 6.4.1        | 24.04  | 2.6.0+git684f6f2   | 3.12   | |ray-2-48-0-post0-25-08-src|              |
   +                           +-------------------------------------------------------------------------+--------------------------------+--------------+--------+--------------------+--------+-------------------------------------------+
   |                           | `verl 0.3.0.post0 <verl-0-3-0-post0-25-08_>`_                           | MI300X                         | 6.2.0        | 20.04  | 2.5.0              | 3.9    | |verl-0-3-0-post0-25-08-src|              |
   +---------------------------+-------------------------------------------------------------------------+--------------------------------+--------------+--------+--------------------+--------+-------------------------------------------+

.. _flashinfer-0-6-18-26-10: https://rocm.docs.amd.com/projects/flashinfer/en/docs-26.10/install/flashinfer-install.html
.. _ray-2-59-0-26-10: https://rocm.docs.amd.com/projects/ray/en/docs-26.10/install/ray-install.html
.. _verl-0-9-0-26-09: https://rocm.docs.amd.com/projects/verl/en/docs-26.09/install/verl-install.html
.. _ray-2-58-0-26-09: https://rocm.docs.amd.com/projects/ray/en/docs-26.09/install/ray-install.html
.. _verl-0-7-1-26-06: https://rocm.docs.amd.com/projects/verl/en/docs-26.06/install/verl-install.html
.. _ray-2-55-1-26-06: https://rocm.docs.amd.com/projects/ray/en/docs-26.06/install/ray-install.html
.. _rocm-rag-1-0-0-26-04: https://rocm.docs.amd.com/projects/rocm-rag/en/docs-26.04/install/configure-framework.html
.. _flashinfer-0-5-3-26-03: https://rocm.docs.amd.com/projects/flashinfer/en/docs-26.03/install/flashinfer-install.html
.. _triton-inference-server-25-12-26-03: https://rocm.docs.amd.com/projects/triton-inference-server/en/docs-26.03/install/triton-inference-server-install.html
.. _flashinfer-0-2-5-26-02: https://rocm.docs.amd.com/projects/flashinfer/en/docs-26.02/install/flashinfer-install.html
.. _ray-2-51-1-26-02: https://rocm.docs.amd.com/projects/ray/en/docs-26.02/install/ray-install.html
.. _verl-0-6-0-26-02: https://rocm.docs.amd.com/projects/verl/en/docs-26.02/install/verl-install.html
.. _flashinfer-0-2-5-25-09: https://rocm.docs.amd.com/projects/flashinfer/en/docs-25.09/install/flashinfer-install.html
.. _ray-2-48-0-post0-25-08: https://rocm.docs.amd.com/projects/ray/en/docs-25.08/install/ray-install.html
.. _verl-0-3-0-post0-25-08: https://rocm.docs.amd.com/projects/verl/en/docs-25.08/install/verl-install.html
