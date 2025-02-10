---
layout: post
excerpt: "Adaptive Mesh Criteria for Parabolic PDEs and Data-Driven Identification in ODE Models" 
title: "Invited seminar talk at the Institute of Structural Mechanics and Dynamics in Aerospace Engineering, Universität Stuttgart, 05.02.2025. "
tags: [presentation]
category: presentation
---

<b>Abstract</b><br>
This talk addresses two topics: first, the challenges in formulating adaptive mesh criteria for parabolic differential equations with monotonic solutions, and second, a data-driven approach using physics-informed neural networks for identifying suitable mechanisms in ordinary differential equation models with sparse observations.

First, I report on an unsuccessful attempt to formulate an adoptive mesh criteria for parabolic differential equations focusing on the monotonicity of the solutions. For a finite element method with implicit time stepping, the requirement for monotone, non-oscillating solutions bounds the minimal time step for the heat equation by the spatial discretization size (Thomas & Zhou, 1997). Transferring this result to a linearization of the Richards’ equations for porous media leads to unfeasible spatial grid sizes. The proof by Thomas & Zhou (1997) does not use the solution values of the previous time step, leaving room for more efficient, adaptive criteria.

The second topic originates in modeling life science applications, where spatial-temporal data is scarce and the exact mechanisms in differential equation models are largely unknown. The temporal dynamics of the test cases can be divided into a dynamic and a quasi-static phase, and we mimic a rare data scenario by using data from the quasi-static phase only. A temporal domain decomposition approach for finite basic physics-informed neural networks (FBPINNs) shows better performance in identifying suitable mechanisms through a parameter estimation than classical vanilla PINNs. The improved performance is visible as well in energy plots, showing unphysical behavior of the learned solutions by classical PINNs.
