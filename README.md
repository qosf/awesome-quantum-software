# Open-Source Quantum Software Projects

Curated list of open-source developed quantum software projects.

*Please read the [contribution guidelines](CONTRIBUTING.md#readme) before contributing.*

## Contents
- [Quantum full-stack library](#quantum-full-stack-library)
- [Quantum simulators](#quantum-simulators)
- [Quantum annealing](#quantum-annealing)
- [Quantum games](#quantum-games)
- [Quantum algorithms](#quantum-algorithms)
- [Quantum compilers](#quantum-compilers)
- [Quantum assembly](#quantum-assembly)
- [Abandoned projects](#abandoned-projects)

## Quantum full-stack library

**Python**
- [QISKit](https://qiskit.org/) - IBM's quantum information software kit for simulating, compiling and executing quantum programs.
- [Strawberry Fields](https://github.com/xanaduai/strawberryfields) - [Xanadu](https://www.xanadu.ai)'s software library for photonic quantum computing.
- [Forest](https://github.com/rigetticomputing/pyquil) - [Rigetti](https://www.rigetti.com/)'s software library for writing, simulating, compiling and executing quantum programs.
- [ProjectQ](https://projectq.ch/) - Hardware-agnostic quantum software framework with compiler and simulator with emulation capabilities.

**Q#**
- [Q#](https://www.microsoft.com/en-us/quantum/development-kit) - Microsoft's quantum programming language with Visual Studio integration.

**C++**
- [XACC](https://github.com/ORNL-QCI/xacc) - [Extreme-scale programming model for quantum acceleration within high-performance computing](https://arxiv.org/abs/1710.01794).

## Quantum simulators

**Python**
- [Quantum Virtual Machine](https://github.com/rigetticomputing/reference-qvm) - Reference implementation of Rigetti's Quantum Virtual Machine.
- [QuTiP](http://qutip.org/) - User-friendly and efficient numerical simulations of a wide variety of Hamiltonians.
- [QTop](https://projectq.ch/) - Simulation and visualization of topological quantum computers.
- [PySimulator](https://github.com/BBN-Q/PySimulator) - Python with C++ backend simulator for superconducting circuits.

**C++**
- [Quantum++](https://github.com/QCT-IQC/qpp) - High-performance general purpose quantum simulator (can simulate d-dimensional qudits).
- [QCL](https://github.com/aviggiano/qcl) - High level, hardware-agnostic programming language for quantum computers (syntax like C or Pascal).

**Haskell**
- [Quipper](https://github.com/thephoeron/quipper-language) - Scalable functional programming language for quantum computing based on [Quantum Lambda Calculus](https://arxiv.org/abs/cs/0404056).

**F#**
- [Liqui|>](http://stationq.github.io/Liquid/) - Toolsuite for quantum simulation developed by [Microsoft QuArC](https://www.microsoft.com/en-us/research/group/quantum-architectures-and-computation-group-quarc/).

## Quantum annealing

**Python, C & Matlab**
- [Qbsolv](https://github.com/dwavesystems/qbsolv) - QUBO solver with [D-Wave](https://www.dwavesys.com) or classical tabu solver backend.

**Python**
- [NetworkX](https://github.com/dwavesystems/dwave_networkx) - Exploration and analysis of network graphs.
- [dimod](https://github.com/dwavesystems/dimod) - Shared API for Ising and QUBO problems.
- [sapi_dimod](https://github.com/dwavesystems/dwave_sapi_dimod) - [Dimod](https://github.com/dwavesystems/dimod) wrapper for D-Wave's Solver API (SAPI).
- [micro_client_sapi_dimod](https://github.com/dwavesystems/dwave_micro_client_dimod) - [Dimod](https://github.com/dwavesystems/dimod) wrapper for the D-Wave Micro Client.
- [minorminor](https://github.com/dwavesystems/minorminer) - Heuristic tool for minor graph embedding.
- [penaltymodel](https://github.com/dwavesystems/penaltymodel) - Utilities and interfaces for using penalty models.
- [penaltymodel_maxgap](https://github.com/dwavesystems/penaltymodel_maxgap) - Generates penalty models with smt solves. Factory & Cache for [penaltymodel](https://github.com/dwavesystems/penaltymodel).
- [embedding_utilities](https://github.com/dwavesystems/dwave_embedding_utilities) - Mapping samples between original and embedded graph.
- [dwave-system](https://github.com/dwavesystems/dwave-system) - Incorporating D-Wave quantum annealers as samplers in the D-Wave Ocean (?) software stack.
- [dwave-cloud-client](https://github.com/dwavesystems/dwave-cloud-client) - Min. implementation of the REST interface to communicate with D-Wave's Solver API.
- [chimera_embedding](https://github.com/dwavesystems/chimera-embedding) - Algorithms to generate native-structured embeddings for Chimera graphs.

**C++**
- [Virtual Hardware Embedding](https://github.com/ORNL-QCI/aqc-virtual-embedding) - Virtual Hardware Embedding Suite for adiabatic quantum computing.


## Quantum games

**Python**
- [Quantum Awesomeness](https://github.com/decodoku/A_Game_to_Benchmark_Quantum_Computers)	- [Simple puzzles to benchmark various quantum processor](https://medium.com/@decodoku/understanding-quantum-computers-through-a-simple-puzzle-game-a290dde89fb2).
- [Quantum Battleships](https://github.com/decodoku/Battleships_with_complementary_measurements) - [Playing battleships with quantum measurements](https://medium.com/@decodoku/how-to-program-a-quantum-computer-part-2-f0d3eee872fe).

## Quantum algorithms

**Python**
- [Grove](https://github.com/rigetticomputing/grove) - Quantum algorithms implemented using [Rigetti](https://www.rigetti.com/)'s [pyQuil](https://github.com/rigetticomputing/pyquil).
- [OpenFermion](https://github.com/quantumlib/OpenFermion) - Compiling and analyzing quantum algorithm for quantum chemistry simulations.
- [XACC Examples](https://github.com/ORNL-QCI/xacc-examples) - Example code using [XACC](https://github.com/ORNL-QCI/xacc) for quantum computing.
- [XACC QChem](https://github.com/ORNL-QCI/xacc-qchem-benchmarks) - QPU Benchmarks for Quantum Chemistry via [XACC](https://github.com/ORNL-QCI/xacc), [Psi4](http://www.psicode.org/) and [OpenFermion](https://github.com/quantumlib/OpenFermion).
- [Adapt](https://github.com/BBN-Q/Adapt) - Algorithms for adaptive refinement of measurements.

**Julia**
- [QuantumTomography.jl](https://github.com/BBN-Q/QuantumTomography.jl) - Julia package to perform quantum state and process tomography.

**C++**
- [XACC VQE](https://github.com/ORNL-QCI/xacc-vqe) - Distributed Variational Quantum Eigensolver built on [XACC](https://github.com/ORNL-QCI/xacc) for solving electronic structure problems.

## Quantum compilers

**C++**
- [Qubiter](http://www.ar-tiste.com/qubiter.html) - Quantum compiler using CS Decomposition to build a binary tree of matrices.
- [pQCS](https://qsoft.iqc.uwaterloo.ca/#software) - [Parallel quantum circuit synthesis](https://uwspace.uwaterloo.ca/handle/10012/9267) with optimal T-count.
- [ScaffCC](https://github.com/epiqc/ScaffCC) - Compilation, analysis and optimization framework for the Scaffold quantum programming language.

## Quantum assembly

- [OpenQASM](https://github.com/QISKit/openqasm) - IBM's open-source quantum assembly language.
- [QMASM](https://github.com/lanl/qmasm) - A quantum macro assembler for D-Wave's quantum annealers.

## Abandoned projects
*2+ years of inactivity. Feel free to reanimate & document some of this work!*
- [QACG](https://github.com/QCT-IQC/qacg) - Quantum Arithmetic Circuit Generator in Haskell.
- [QCViewer](https://github.com/QCT-IQC/QCViewer) - A visual quantum circuit design and simulation tool.


## Contributing
See the [contribution guidelines](CONTRIBUTING.md/#readme).

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Mark Fingerhuth has waived all copyright and related or neighboring rights to this work.