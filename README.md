# ANR MRSEI ECODD
Visiting Prof at TU Delft

******************
SEMINARS
******************

## Talk 1 @ 3ME on the 9th of May 2022
Title: On some recent developments in topology optimization of aerostructures {Stiffer, Lighter, Greener}
Prof. Joseph Morlier, ISAE-SUPAEO/ICA {Visiting prof Kunal Masania at TU Delft May 2022}

The goal of this presentation is to present two innovative numerical methods for designing ultralightweight structures.
This presentation attempts to demonstrate the contribution of reproducible research with two recent attempts of Prof Morlier’s group untitled GGP [1] and EMTO [2]. The first method standardizes the existing methods in explicit topological optimization. The second offers a multiscale topological optimization environment. The common point: Two pioneering work on SIMP published with the associated Matlab code top99 and top88 (initiative of the DTU). The comparison of these methods will be applied to an airplane wing rib (2D). We highlight here their complementarity, one giving a crystal clear structural concept, the other one giving a micro-architectural design whose manufacture must be automated (using 3D printer). A panorama of more advanced results in Pylon design [3] and ALM [4] will be highlighted for GGP. Finally, a brief introduction to Ecodesign with SIMP topology optimization will also be presented [5].

[Slides](https://github.com/mid2SUPAERO/ECODD/blob/main/3ME.pdf)

[1] Coniglio, S., Morlier, J., Gogu, C., & Amargier, R. (2019). Generalized Geometry Projection: A Unified Approach for Geometric Feature Based Topology Optimization. Archives of Computational Methods in Engineering, 1-38.
[2] Duriez, E., Morlier, J., Charlotte, M., & Azzaro-Pantel, C. (2021). A well connected, locally-oriented and efficient multi-scale topology optimization (EMTO) strategy. Structural and Multidisciplinary Optimization, 1-24.
[3] Coniglio, S., Gogu, C., Amargier, R., & Morlier, J. (2019). Engine pylon topology optimization framework based on performance and stress criteria. AIAA Journal, 57(12), 5514-5526.
[4] Bhat, K. V., Capasso, G., Coniglio, S., Morlier, J., & Gogu, C. (2022). On some applications of Generalized Geometric Projection to optimal 3D printing. Computers & Graphics, 199-212.
[5] Duriez, E., Morlier, J., Charlotte, M., & Azzaro-Pantel, C. (2022). Ecodesign with topology optimization. Procedia CIRP.

https://github.com/topggp/blog for Crystal clear and preliminary ALM

https://github.com/mid2SUPAERO/EMTO for Redesigning structures for ALM



## Talk 2 @ AE on the 13th of May 2022

A 3-ingredient recipe for Accelerating Aerospace Engineering Design: MDO, Surrogate and Ecodesign
This presentation attempts to demonstrate the contribution of reproducible research with 3 recent attempts of Prof Morlier’s group untitled SMT [1] (with ONERA and Umich), GGP [2] and EMTO [3].
During the last few decades, surrogate modeling has gained in popularity, especially in engineering fields, where they are often used in design analysis and optimization to replace expensive numerical simulations. Coupled to Multidisciplinary Design Optimization (MDO) this process lead to an engineering design acceleration through AI.
The first part of the talk will present the Surrogate Modeling Toolbox (SMT). SMT is a Python package that contains a collection of surrogate modeling methods (also known as Gaussian Processes in Machine Learning community), sampling techniques and benchmarks. SMT is different from existing surrogate modeling libraries because of its emphasis on derivatives that can be used directly in MDO process. It also includes surrogate model that is not available elsewhere: KPLS (Kriging with Partial Least Square) for automatic inputs dimension reduction, mixture of experts (with automatic clustering) for simulation codes that include singularities (such as buckling in structural mechanics) and mixed variable design space (continuous, discrete, and categorical). The 2022 version currently available propose new applications such as multi-fidelity approach, Bayesian unconstrained optimization (EGO), fully inter-operable and automated. Some MDO applications in Aerospace Design will be highlighted, including CRM wing [4] and EcoHALE [5] design.
The second part of the talk will show some progress in design methodology for obtaining more sustainable aerostructures. We will first demonstrate the capability of explicit (GGP) and multiscale approach (EMTO) in TopOpt for the wing rib test case (2D) then we will briefly establish a new path toward Ecodesign of aerostructures by combining Ashby’s index with SIMP topology optimization [6].

[Slides](https://github.com/mid2SUPAERO/ECODD/blob/main/AE.pdf)

[1] Bouhlel, M. A., Hwang, J. T., Bartoli, N., Lafage, R., Morlier, J., & Martins, J. R. (2019). A Python surrogate modeling framework with derivatives. Advances in Engineering Software, 135, 102662.
[2] Coniglio, S., Morlier, J., Gogu, C., & Amargier, R. (2019). Generalized Geometry Projection: A Unified Approach for Geometric Feature Based Topology Optimization. Archives of Computational Methods in Engineering, 1-38.
[3] Duriez, E., Morlier, J., Charlotte, M., & Azzaro-Pantel, C. (2021). A well connected, locally-oriented and efficient multi-scale topology optimization (EMTO) strategy. Structural and Multidisciplinary Optimization, 1-24.
[4] Mas Colomer, J., Bartoli, N., Lefebvre, T., Martins, J. R., & Morlier, J. (2021). An MDO-based methodology for static aeroelastic scaling of wings under non-similar flow. Structural and Multidisciplinary Optimization, 63(3), 1045-1061.
[5] Duriez, E., Guadano Martin, Morlier, J. (2022). HALE multidisciplinary ecodesign optimization with material selection, under review
[6] Duriez, E., Morlier, J., Charlotte, M., & Azzaro-Pantel, C. (2022). Ecodesign with topology optimization. Procedia CIRP.

https://github.com/topggp/blog for Crystal clear and preliminary ALM

https://github.com/mid2SUPAERO/EMTO for Redesigning structures for ALM

https://smt.readthedocs.io/en/latest/ for Design Acceleration

[Play online with SMT](https://colab.research.google.com/drive/1_7L6fNq8F-HBhm9hDno5rwTXfHKXLGCh?usp=sharing)


******************
POPULARIZATION
******************

[Linkedin on MDO](https://www.linkedin.com/pulse/optimization-mdo-connecting-people-joseph-morlier/)

[Linkedin on TopOpt](https://www.linkedin.com/pulse/possible-build-aircraft-wing-lego-joseph-morlier/)


******************
COURSE
******************

[MDO Course @ SUPAERO](https://github.com/jomorlier/mdocourse/)








