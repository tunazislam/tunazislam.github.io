---
title: "A Machine Learning Approach for Efficient Parallel Simulation of Beam Dynamics on GPUs"
collection: publications
permalink: /publications/PLsimulation_ML_GPU
venue: "ICPP 2017"
citation: 'Kamesh Arumugam, Desh Ranjan, Mohammad Zubair, Balsa Terzic, Alexander Godunov, <b>Tunazzina Islam</b>. <i>46th International Conference on Parallel Processing (ICPP) 2017, pp. 462-471.</i>'
---  
[[Paper link]](https://ieeexplore.ieee.org/abstract/document/8025320/)

## Abstract
Parallel computing architectures like GPUs have traditionally been used to accelerate applications with dense and highly-structured workloads; however, many important applications in science and engineering are irregular and dynamic in nature, making their effective  parallel implementation a daunting task. Numerical simulation of charged particle beam dynamics is one such application where the  distribution of work and data in the accurate computation of collective effects at each time step is irregular and exhibits control-flow and memory access patterns that are not readily amenable to GPU's architecture. Algorithms with these properties tend to present both significant branch and memory divergence on GPUs which leads to severe performance bottlenecks. We present a novel cache-aware algorithm that uses machine learning to address this problem. The algorithm presented here uses supervised learning to adaptively model and track irregular access patterns in the computation of collective effects at each time step of the simulation to anticipate the future control-flow and data access patterns. Access pattern forecast are then used to formulate runtime decisions that minimize branch and memory divergence on GPUs, thereby improving the performance of collective effects computation at a future time step based on the observations from earlier time steps. Experimental results on NVIDIA Tesla K40 GPU shows that our approach is effective in maximizing data reuse, ensuring workload balance among parallel threads, and in minimizing both branch and memory divergence. Further, the parallel implementation delivers up to 485 Gflops of double precision performance, which translates to a speedup of up to 2.5X compared to the fastest known GPU implementation.

