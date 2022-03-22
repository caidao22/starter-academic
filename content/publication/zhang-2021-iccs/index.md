+++
title = "Revolve-based adjoint checkpointing for multistage time integration"
date = 2021-03-01
authors = ["Hong Zhang", "Emil Constantinescu"]
publication_types = ["1"]
abstract = "We consider adjoint checkpointing strategies that minimize the number of recomputations needed when using multistage timestepping. We demonstrate that we can improve on the seminal work based on the Revolve algorithm. The new approach provides better performance for a small number of time steps or checkpointing storage. Numerical results illustrate that the proposed algorithm can deliver up to two times speedup compared with that of Revolve and avoid recomputation completely when there is sufficient memory for checkpointing. Moreover, we discuss a tailored implementation that is arguably better suited for mature scientific computing libraries by avoiding central control assumed in the original checkpointing strategy. The proposed algorithm has been included in the PETSc library."
abstract_short = " "
selected = true
publication = "International Conference on Computational Science"
tags = ["Adjoint checkpointing", "Multistage timestepping", "Revolve"]
doi = ""
+++

