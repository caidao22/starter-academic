+++
title = "Vectorized Parallel Sparse Matrix-Vector Multiplication in PETSc Using AVX-512"
date = 2018-01-01
authors = ["Hong Zhang", "Richard T. Mills", "Karl Rupp", "Barry F. Smith"]
publication_types = ["1"]
abstract = "Emerging many-core CPU architectures with high degrees of single-instruction, multiple data (SIMD) parallelism promise to enable increasingly ambitious simulations based on partial differential equations (PDEs) via extreme-scale computing. However, such architectures present several challenges to their efficient use. Here, we explore the efficient implementation of sparse matrix-vector (SpMV) multiplications---a critical kernel for the workhorse iterative linear solvers used in most PDE-based simulations---on recent CPU architectures from Intel as well as the second-generation Knights Landing Intel Xeon Phi, which features many CPU cores, wide SIMD lanes, and on-package high-bandwidth memory. Traditional SpMV algorithms use compressed sparse row storage format, which is a hindrance to exploiting wide SIMD lanes. We study alternative matrix formats and present an efficient optimized SpMV kernel, based on a sliced ELLPACK representation, which we have implemented in the PETSc library. In addition, we demonstrate the benefit of using this representation to accelerate preconditioned iterative solvers in realistic PDE-based simulations in parallel."
abstract_short = " "
selected = true
publication = "*Proceedings of the 47th International Conference on Parallel Processing - ICPP 2018*"
tags = ["PETSc", "Xeon Phi", "many-core", "parallel SpMV", "vectorization"]
doi = "10.1145/3225058.3225100"
url_pdf = 'publication/zhang-2018/ICPP_KNL_final.pdf'
+++

