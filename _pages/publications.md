---
layout: page
permalink: /research/
title: research
description: publications and talks by categories in reversed chronological order.
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>

<div class="talks">

\NewEntry{Oct. 2023}{
\Description{
 I. R. Ivanov, O. Zinenko, J. Domke, T. Endo, and W. S. Moses.
Optimization of CUDA GPU Kernels and Translation to AMDGPU in Polygeist/MLIR. 2023 LLVM Developers' Meeting. Student Talk
}
}

\NewEntry{Oct. 2023}{
\Description{
 I. R. Ivanov, O. Zinenko, J. Domke, T. Endo, J. Doerfert, and W. S. Moses.
GPU Kernel Compilation in Polygeist/MLIR. 2023 LLVM Developers' Meeting GPU Offloading Workshop. Lightning Talk
}
}

\NewEntry{Nov. 2022}{
\Description{
 W. S. Moses, I. R. Ivanov, J. Domke, T. Endo, J. Doerfert, and O. Zinenko.
High-Performance GPU-to-CPU Transpilation and Optimization via High-Level Parallel Constructs in Polygeist/MLIR. 2022 LLVM Developers' Meeting. Lightning Talk
}
}

\NewEntry{Feb. 2022}{
\Description{
I. R. Ivanov, J. Domke, and T. Endo. Automatic translation
  of CUDA code into high performance CPU code using LLVM IR transformations. The
  4th R-CCS Internation Symposium. Lightning Talk
}
}

\NewEntry{Feb. 2021}{
\Description{
  I. R. Ivanov, J. Domke, A. Nomura and T. Endo.
  Improved failover for HPC interconnects through localised routing
  restoration The 3rd R-CCS Internation Symposium. Lightning Talk
}
}

</div>

<div class="talks">

\NewEntry{May. 2023}{
\Description{
Ryan Barton, Mohamed Wahib, Jens Domke, Ivan R. Ivanov, Toshio Endo, Satoshi Matsuoka.
BITFLEX - An HPC User-Driven Automatic Toolchain for Precision Manipulation and Approximate Computing, ISC High Performance 2023
}
}

\NewEntry{Feb. 2023}{
  \Description{
Ivan R. Ivanov, William S. Moses, Jens Domke, Toshio Endo. Parallel Optimizations and Transformations of GPU Kernels Using a High-Level representation in MLIR/Polygeist. IEEE/ACM International Symposium on Code Generation and Optimization (CGO)
}
}
{% bibliography -f {{ site.scholar.bibliography }} %}

</div>
