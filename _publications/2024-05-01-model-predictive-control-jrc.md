---
title: "Model predictive control design under stochastic parametric uncertainties based on polynomial chaos expansions for f-16 aircraft"
collection: publications
category: manuscripts
permalink: /publication/2024-05-01-model-predictive-control-jrc
excerpt: 'This paper presents a novel approach to stochastic model predictive control (SMPC) by employing the polynomial chaos expansion (PCE) method called PCE-based model predictive control (PCE-MPC).'
date: 2024-05-01
venue: 'Journal of Robotics and Control (JRC)'
paperurl: 'https://journal.umy.ac.id/index.php/jrc/article/view/21366/9108'
citation: 'H. Purnawan, T. Asfihani, S. Kim, and S. Subchan. (2024). &quot;Model predictive control design under stochastic parametric uncertainties based on polynomial chaos expansions for f-16 aircraft.&quot; <i>Journal of Robotics and Control (JRC)</i>. 5(3).'
---

Parametric uncertainty in a dynamical system has the potential to undermine the performance of a closed-loop controller designed through classical techniques. This paper presents a novel approach to stochastic model predictive control (SMPC) by employing the polynomial chaos expansion (PCE) method called PCE-based model predictive control (PCE-MPC). This method offers a more robust and efficient solution to tackle parameter uncertainties in dynamic systems. The PCE method is utilized to propagate uncertainties through orthogonal polynomials, and the Galerkin projection approach is employed to compute PCE coefficients via intrusive spectral projection (ISP). In Galerkin projection, the inner product involves an integration term, and the integration values are approximated using the Gauss-Legendre quadrature. This quadrature method precisely integrates the p-th order polynomial using 2p-1 points. The numerical case study focuses on the short-period mode of the F-16 aircraft model. Simulation results demonstrate the robust performance of the proposed method in the presence of parameter uncertainties, with system states converging to the original points for each parameter realization under various initial conditions. Comparison results indicate negligible differences between MPC and PCE-MPC, showcasing nearly identical performance. However, further investigation is warranted in other cases and more complex systems involving parameter uncertainties.
