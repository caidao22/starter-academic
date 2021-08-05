+++
title = "Lightweight and accurate silent data corruption detection in ordinary differential equation solvers"
date = 2016-01-01
authors = ["Pierre Louis Guhur", "Hong Zhang", "Tom Peterka", "Emil Constantinescu", "Franck Cappello"]
publication_types = ["1"]
abstract = "Silent data corruptions (SDCs) are errors that corrupt the system or falsify results while remaining unnoticed by firmware or oper- ating systems. In numerical integration solvers, SDCs that impact the accuracy of the solver are considered significant. Detecting SDCs in high-performance computing is necessary because results need to be trustworthy and the increase of the number and complexity of com- ponents in emerging large-scale architectures makes SDCs more likely to occur. Until recently, SDC detection methods consisted in replicat- ing the processes of the execution or in using checksums (for example algorithm-based fault tolerance). Recently, new detection methods have been proposed relying onmathematical properties of numerical kernels or performing data analysis of the results modified by the application. None of those methods, however, provide a lightweight solution guaranteeing that all significant SDCs are detected. We propose a new method called Hot Rod as a solution to this problem. It checks and potentially cor- rects the data produced by numerical integration solvers. Our theoretical model shows that all significant SDCs can be detected. We present two detectors and conduct experiments on streamline integration from the WRFmeteorology application. Compared with the algorithmic detection methods, the accuracy of our first detector is increased by 52% with a similar false detection rate. The second detector has a false detection rate one order of magnitude lower than these detection methods while improving the detection accuracy by 23 %. The computational overhead is lower than 5% in both cases. The model has been developed for an explicit Runge-Kutta method, although it can be generalized to other solvers."
selected = false
publication = "*Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics)*"
tags = ["Fault tolerance", "HPC", "Numerical integration solvers", "Resilience", "Runge-kutta", "SDC"]
doi = "10.1007/978-3-319-43659-3_47"
+++

