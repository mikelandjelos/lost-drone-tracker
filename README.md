# The "Lost Drone" Tracker (Monte Carlo Localization)

Real-time 2D state estimation and tracking system for a drone experiencing
physical process noise (wind gusts) and measurement noise (a noisy GPS sensor).

## Overview

- Kinematics-based prediction models for drone motion.
- Simulation-based sequential Bayesian updates (Monte Carlo localization).
- A particle filter managing a swarm of *N* particles to represent the position
  probability distribution.
- Real-time resampling to collapse tracking uncertainty.

## Planned tooling

- **C++** — Eigen, OpenMP, GTest, Google Benchmark
- **Python** — NumPy, Matplotlib, Quarto

## Status

🚧 Work in progress — repository scaffolding. Code and documentation to follow.
