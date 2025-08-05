---
title: "PiPC-Net: A Physics-informed Piecewise Continuity Network for Solving the Non-linear Jerk Equation"
collection: publications
category: Under-Review
permalink: /publication/2025-01-01-pipc-net-physics-informed-piecewise-continuity-network/
date: 2025-01-01
venue: "Engineering"
paperurl: ""
citation: "Ahmed, N., Awlad, M., Babu, M. A., Ahmmed, M. M., Rahman, M. M., & Mahmud, M. (2025). PiPC-Net: A Physics-informed Piecewise Continuity Network for Solving the Non-linear Jerk Equation. Engineering. [Under Review]"
excerpt: "Under review at Engineering."
authors: "Ahmed, N., Awlad, M., Babu, M. A., Ahmmed, M. M., Rahman, M. M., & Mahmud, M."
thumbnail: "Jerk-GA (1).png"
abstract: "Jerk equations, which define the third derivative of position with respect to time, are key to modeling stiff nonlinear dynamical systems in chaotic oscillators, robotic trajectory optimization, vibration damping, and precision control. These high-order ordinary differential equations (ODEs) exhibit stiffness and sensitivity to initial conditions, challenging long-term stability in solvers like Physics-Informed Neural Networks (PINNs). PINNs, despite embedding physical laws, suffer from global errors, spectral bias, and vanishing gradients over extended horizons. This paper introduces the Physics-Informed Piecewise Continuity Network (PiPC-Net), a domain-decomposition method dividing the time domain into subdomains, each approximated by a physics-informed subnetwork. PiPC-Net ensures C² continuity at interfaces and inherits initial conditions to limit error buildup, enhancing gradient flow and optimization with LBFGS. Evaluated on an oscillatory jerk (B = 0.3, 0.5, 0.7) and a damped cubic jerk (η = 1.0, 1.5, 2.0) over t ∈ [0, 20] with 1,001 points, PiPC-Net outperforms PINNs. It achieves 2.3 to 2.6 times faster convergence, reducing residual losses by 4–6 orders to log L -12.00 to -13.80, with variance below 0.20. MAE reductions reach 72–87% globally, peaking at 421.6 times for η=1.5 at t=20. RMSEs range from 0.000437–0.0135 (PSNR 37.4 to 54.2 dB) for oscillatory and 0.000837–0.00634 (PSNR 44.0–61.5 dB) for damped cases, with errors under 2.5% amplitude and 0.06 rad phase lag. Error profiles show a sawtooth pattern, capping peaks at 0.0181–0.0399 with 68% lower variance than PINNs. Ablation studies confirm M=10 subdomains reduce late-time MAEs by 15–25%, while comparisons with classical methods yield 84–98% better L²-errors. PiPC-Net's scalability supports real-time robotics, chaos modeling, and adaptive control."
---

Full text coming soon.