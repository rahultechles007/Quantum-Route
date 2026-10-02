# Quantum-Inspired Intelligent Traffic Route Optimizer

A self-contained browser prototype for Problem Statement 26137.

## Run
Open `index.html` in a modern browser. Internet access is needed once to load Chart.js from jsDelivr.

## Features
- Graph-based simulated transportation network
- Multiple vehicles and customers
- Traffic scenarios
- QPSO-inspired discrete swarm search
- Multi-objective fitness (time, distance, congestion)
- Route visualization
- Convergence chart
- Dynamic traffic change and re-optimization
- No server or installation required

## Important research note
This is a prototype/educational QPSO-inspired optimizer, not a claim of quantum speedup. For a research-grade implementation, replace the heuristic with a formally specified QPSO update/discretization method and benchmark it against exact VRP solvers and established metaheuristics on standard datasets.
