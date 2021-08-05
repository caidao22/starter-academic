+++
title = "FATODE: a library for forward, adjoint, and tangent linear integration of ODEs"
date = 2014-10-01
authors = ["Hong Zhang", "Adrian Sandu"]
publication_types = ["2"]
abstract = "Fatode is a Fortran library for the integration of ordinary differential equations with direct and adjoint sensitivity analysis capabilities. The paper describes the capabilities, implementation, code organization, and usage of this package. Fatode implements four families of methods: explicit Runge--Kutta for nonstiff problems, fully implicit Runge--Kutta, singly diagonally implicit Runge--Kutta, and Rosenbrock for stiff problems. Each family contains several methods with different orders of accuracy; users can add new methods by simply providing their coefficients. For each family the forward, adjoint, and tangent linear models are implemented. General purpose solvers for dense and sparse linear algebra are used; users can easily incorporate problem-tailored linear algebra routines. The performance of the package is demonstrated on several test problems. To the best of our knowledge Fatode is the first publicly available general purpose package that offers forward and adjoint sensitivity analysis capabi..."
abstract_short = " "
selected = true
publication = "*SIAM Journal on Scientific Computing*"
tags = ["Runge--Kutta methods", "adjoint model", "sensitivity analysis", "tangent linear model"]
doi = "10.1137/130912335"
url_pdf = 'publication/zhang-2014/SISC_FATODE_final.pdf'
+++

