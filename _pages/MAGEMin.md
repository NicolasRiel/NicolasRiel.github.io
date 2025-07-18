---
permalink: /MAGEMin/
title: "MAGEMin"
---

## Stable phase equilibrium modeling

[MAGEMin](https://github.com/ComputationalThermodynamics/MAGEMin) is a Gibbs energy minimization solver, which computes the thermodynamically most stable assemblage for a given thermodynamic database and a set of bulk-rock composition, pressure and temperature conditions. It returns the fraction of the stable minerals, their compositions and all thermodynamically-derived parameters such as density, thermal expansivity, heat capacity etc.

MAGEMin backend is written as a parallel C library and uses a combination of linear programming, the extended Partitioning Gibbs free Energy approach and gradient-based local minimization to compute the most stable mineral assemblage. In this, it differs from existing approaches which makes it particularly suitable to utilize modern multicore processors.

While MAGEMin is the engine for the prediction of the stable phases, it is best used wih the Julia interface [MAGEMin_C](https://github.com/ComputationalThermodynamics/MAGEMin_C.jl) and/or the web-browser julia [MAGEMinApp](https://github.com/ComputationalThermodynamics/MAGEMinApp.jl):

![MAGEMinApp](/files/MAGEMinApp_overview.png)

Try out MAGEMin!

* Computational Thermodynamics [GitHub](https://github.com/ComputationalThermodynamics)
* MAGEMin [GitHub](https://github.com/ComputationalThermodynamics/MAGEMin)
* MAGEMin_C [GitHub](https://github.com/ComputationalThermodynamics/MAGEMin_C.jl)
* MAGEMinApp [GitHub](https://github.com/ComputationalThermodynamics/MAGEMinApp.jl)
* MAGEMin [documentation](https://computationalthermodynamics.github.io/MAGEMin_C.jl/dev/)

