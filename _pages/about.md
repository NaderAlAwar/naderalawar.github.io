---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a senior software engineer at NVIDIA, where I work on the [CCCL](https://github.com/NVIDIA/cccl/) team,
with a focus on [CUB](https://nvidia.github.io/cccl/cub/) and [cuda.compute](https://nvidia.github.io/cccl/python/compute.html).
I earned my PhD in Electrical and Computer Engineering from The University of Texas at Austin, where I was advised by
by [Prof. Milos Gligoric](http://users.ece.utexas.edu/~gligoric/).

I was the lead developer of [PyKokkos](https://github.com/kokkos/pykokkos), a Python framework for writing performance-portable kernels.
Using PyKokkos, I developed high-performance software entirely in Python, including a Python port of
[ExaMiniMD](https://github.com/kokkos/pykokkos/tree/main/examples/ExaMiniMD/standalone), a [molecular dynamics mini-application](https://github.com/ECP-copa/ExaMiniMD);
a [particle-in-cell (PIC) solver](https://ieeexplore.ieee.org/document/9980962) for the electron Boltzmann equation;
and several [machine learning](https://github.com/kokkos/pykokkos/tree/main/examples/NaiveBayes) [algorithms](https://github.com/kokkos/pykokkos/tree/main/examples/LogisticRegression).
I also worked on [lazy evaluation and kernel fusion](https://dl.acm.org/doi/pdf/10.1145/3728959) in PyKokkos.

My other work includes [Tempo](https://dl.acm.org/doi/10.1145/3485543), a CUDA framework
for writing test generation programs, [WayOut](https://github.com/EngineeringSoftware/wayout)
a framework for automatic generation of Python language bindings for C++ code, and [Yalla](https://dl.acm.org/doi/pdf/10.1145/3696443.3708942),
a tool to improve incremental compilation speed of C++ code.

### Publications

*High-Performance CUDA Ops in Python: JIT-Compiling CUB With cuda.compute*\
Nader Al Awar\
PyTorch Conference\
(PTC 2025), Poster Presentations: Edge & Hardware Acceleration, October 22-23, 2025, San Francisco, USA

*Dynamically Fusing Python HPC Kernels*\
**Nader Al Awar**, Muhammad Hannan Naeem, James Almgren-Bell, George Biros, and Milos Gligoric\
International Symposium on Software Testing and Analysis\
(ISSTA 2025), pages 1865-1886, June 25-28, 2025, Trondheim, Norway

*Speeding up the Local C++ Development Cycle with Header Substitution*\
**Nader Al Awar**, Zijian Yi, George Biros, and Milos Gligoric\
International Symposium on Code Generation and Optimization\
(CGO 2025), pages 704-717, March 1-5, 2025, Las Vegas, USA
 
*A Multi-GPU Python Solver for Low-Temperature Non-Equilibrium Plasmas*\
James Almgren-Bell, **Nader Al Awar**, Dilip Geethakrishnan, Milos Gligoric, and George Biros\
International Symposium on Computer Architecture and High Performance Computing\
(SBACPAD 2022), pages 140-149, November 2-4, Bordeaux, France

[*PyKokkos: Performance Portable Kernels in Python*](https://naderalawar.github.io/files/AlAwarETAL22PyKokkosTool.pdf)\
**Nader Al Awar**, Neil Mehta, Steven Zhu, George Biros, and Milos Gligoric\
International Conference on Software Engineering, Tool Demonstrations Track\
(ICSE Demo 2022), pages 164-167, May 21-29, Pittsburgh, USA

*Programming and Execution Models for Parallel Bounded Exhaustive Testing*\
**Nader Al Awar**, Kush Jain, Christopher J. Rossbach, and Milos Gligoric\
Conference on Object-Oriented Programming, Systems, Languages, and Applications\
(OOPSLA 2021), pages 1-28, October 17-22, 2021, Chicago, USA

*Dynamic Generation of Python Bindings for HPC Kernels*\
Steven Zhu, **Nader Al Awar**, Mattan Erez, and Milos Gligoric\
International Conference on Automated Software Engineering\
(ASE 2021), pages 92-103, Virtual, November 2021.

*The Kokkos EcoSystem: Comprehensive Performance Portability For High Performance Computing*\
Christian Trott, Luc Berger-Vergiat, David Poliakoff, Sivasankaran Rajamanickam, Damien Lebrun-Grandie, Jonathan Madsen, **Nader Al Awar**, Milos Gligoric, Galen Shipman, and Geoff Womeldorff\
Computing in Science and Engineering\
(CISESI 2021), pages 1-9, November 2021.

[*A Performance Portability Framework for Python*](https://naderalawar.github.io/files/AlAwarETAL21PyKokkos.pdf)\
**Nader Al Awar**, Steven Zhu, George Biros, and Milos Gligoric\
International Conference on Supercomputing\
(ICS ’21), June 14–17, 2021, Virtual Event, USA\
(This paper was **nominated for the Best Paper Award**.)

*How Effective are Existing Java API Specifications for Finding Bugs during Runtime Verification?*\
Owolabi Legunsen, **Nader Al Awar**, Xinyue Xu, Wajih Ul Hassan, Grigore Roşu, Darko Marinov\
Automated Software Engineering Journal\
(JASE 2019), 26(4): 795-837, December 2019
