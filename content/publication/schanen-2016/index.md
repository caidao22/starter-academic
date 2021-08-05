+++
title = "Asynchronous two-level checkpointing scheme for large-scale adjoints in the spectral-element solver Nek5000"
date = 2016-01-01
authors = ["Michel Schanen", "Oana Marin", "Hong Zhang", "Mihai Anitescu"]
publication_types = ["1"]
abstract = "Adjoints are an important computational tool for large-scale sensitivity evaluation, uncertainty quantification, and derivative-based optimization. An essential component of their performance is the storage/recomputation balance in which efficient adjoint checkpointing strategies play a key role. We introduce a novel asynchronous two-level adjoint checkpointing scheme for numerical time discretizations targeted at large-scale numerical simulations. The checkpointing scheme combines bandwidth-limited disk checkpointing and space-limited binomial memory checkpointing. Based on assumptions about the target petascale systems, which we later demonstrate to be realistic on the IBM Blue Gene/Q system Mira, we create a model of the predicted performance of the adjoint computation and validate it using the highly scalable Navier-Stokes spectral-element solver Nek5000 on small to moderate subsystems of the Mira supercomputer."
selected = false
publication = "*Procedia Computer Science*"
tags = ["Adjoints", "CFD", "Gradient", "Large scale", "Nek5000", "Two-level checkpointing"]
doi = "10.1016/j.procs.2016.05.444"
+++

