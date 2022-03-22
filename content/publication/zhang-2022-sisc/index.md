+++
title = "PETSc TSAdjoint: a discrete adjoint ODE solver for first-order and second-order sensitivity analysis"
date = 2019-01-01
authors = ["Hong Zhang", "Emil M. Constantinescu", "Barry F. Smith"]
publication_types = ["2"]
abstract = "We present a new software system PETSc TSAdjoint for first-order and second-order adjoint sensitivity analysis of time-dependent nonlinear differential equations. The derivative calculation in PETSc TSAdjoint is essentially a high-level algorithmic differentiation process. The adjoint models are derived by differentiating the timestepping algorithms and implemented based on the parallel infrastructure in PETSc. Full differentiation of the library code including MPI routines thus is avoided, and users do not need to derive their own adjoint models for their specific applications. PETSc TSAdjoint can compute the first-order derivative, that is, the gradient of a scalar functional, and the Hessian-vector product that carries second-order derivative information, while requiring minimal input (a few callbacks) from the users. Optimal checkpointing schemes are employed by the adjoint model in a manner that is transparent to users. Usability, efficiency, and scalability are demonstrated through examples from a variety of applications."
abstract_short = " "
selected = true
publication = "SIAM Journal on Scientific Computing"
tags = ["sensitivity analysis", "adjoint", "PETSc", "second-order adjoint"]
doi = ""
url_pdf = 'publication/zhang-2022-sisc/SISC_TSAdjoint_arxiv.pdf'
+++

