# Quantum MAXCUT Solver using QITE

This repository contains our team's (Quantum Novices) submission for the IonQ Challenge at iQuHack 2025, MIT's Quantum Computing Hackathon.

## Project Overview

We implemented a quantum computing approach for the MAXCUT problem using IonQ's Quantum Imaginary Time Evolution (QITE) algorithm. Our implementation focused on three main challenges:

1. Finding the optimal max cut
2. Equal sets of node distribution
3. Relationship between nodes (partially implemented)

## Repository Structure

- `notebooks/`: Contains our implementation notebooks
  - `IonQuHack2025-quantum-novices.ipynb`: Main implementation notebook
- `presentation/`: Project presentation materials
- `docs/`: Additional documentation
  - `challenge.md`: Original challenge description and requirements

## Results

Our implementation achieved the following scores for a graph:

- Base Score: 0.78876
- Balanced Score: 0.78606
- Connected Score: 0.00398

## Implementation Details

We used:
- Custom quantum circuits with Pauli-Z gates
- Hamiltonian optimization
- IonQ's QITE algorithm
- Graph analysis

The approach involved:
1. Building custom quantum circuits
2. Implementing Hamiltonian for different graph structures
3. Analyzing system energy convergence
4. Optimizing ansatz parameters

## Team Members

- Dhairya Patel
- Quinn Arbolante
- Marilu Zyanya Martinez
- Fatih Sultan Mehmet
- Ved Kaustubh Anumala


## Acknowledgments

Special thanks to:
- The iQuHack organizing team
- IonQ and qBraid team for providing the quantum computing resources

## Challenge Link

[https://github.com/iQuHACK/2025-IonQ]
