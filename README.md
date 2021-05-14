<p align="center"><img src="hopf_fibration.png" alt="bDialog" height="300px"></p>

# Open-Source Quantum Software Projects

[![Twitter Follow](https://img.shields.io/twitter/follow/qosfoundation?style=social)](https://twitter.com/qosfoundation)

Curated list of open-source developed quantum software projects.

*Please read the [contribution guidelines](CONTRIBUTING.md#readme) before contributing.*

Also please check out the [Unitary Fund](http://unitary.fund/)'s 4k$ grant project for quantum OSS!

## Contents
- [Quantum full-stack libraries](#quantum-full-stack-libraries)
- [Quantum simulators](#quantum-simulators)
- [Quantum annealing](#quantum-annealing)
- [Quantum algorithms](#quantum-algorithms)
- [Quantum compilers](#quantum-compilers)
- [Quantum assembly](#quantum-assembly)
- [Quantum control](#quantum-control)
- [Quantum error correction](#quantum-error-correction)
- [Quantum and post-quantum cryptography](#quantum-and-post-quantum-cryptography)
- [Experimental quantum computing](#experimental-quantum-computing)
- [Quantum fun](#quantum-fun)
- [Quantum tools](#quantum-tools)
- [Abandoned projects](#abandoned-projects)

For a curated list of learning resources please check out [desireevl's repo](https://github.com/desireevl/awesome-quantum-computing).

## Quantum full-stack libraries

**C++**
- [staq](https://github.com/softwareqinc/staq) - [Full stack quantum processing toolkit](https://arxiv.org/abs/1912.06070).
- [XACC](https://github.com/ORNL-QCI/xacc) - [Extreme-scale programming model for quantum acceleration within high-performance computing](https://arxiv.org/abs/1710.01794).

**Python**
- [blueqat](https://github.com/Blueqat/Blueqat) - A quantum computing SDK.
- [Braket](https://github.com/aws/amazon-braket-sdk-python) - [Amazon's](https://aws.amazon.com/braket/) fully managed quantum computing service for building quantum algorithms.
- [Cirq](https://github.com/quantumlib/Cirq) - Framework for creating, editing, and invoking Noisy Intermediate Scale Quantum (NISQ) circuits.
- [Forest](https://github.com/rigetticomputing/pyquil) - [Rigetti](https://www.rigetti.com/)'s software library for writing, simulating, compiling and executing quantum programs.
- [Ocean](https://github.com/dwavesystems/dwave-ocean-sdk) - [D-Wave System](https://www.dwavesys.com/home)'s suite of tools for solving hard problems with quantum computers.
- [OpenQL](https://github.com/QE-Lab/OpenQL) - Compiler framework with algorithm libraries, optimizer, scheduler, QEC, mapping, micro-code generator.
- [ProjectQ](https://github.com/ProjectQ-Framework/ProjectQ) - Hardware-agnostic framework with compiler and simulator with emulation capabilities.
- [Qiskit](https://qiskit.org/) - Framework for noisy quantum computers at the level of pulses, circuits, and algorithms (supported by IBM).
- [Strawberry Fields](https://github.com/xanaduai/strawberryfields) - [Xanadu](https://www.xanadu.ai)'s software library for photonic quantum computing.
- [Tequila](https://github.com/aspuru-guzik-group/tequila) - An Extensible Quantum Information and Learning Architecture developed by Alan Aspuru-Guzik's group (UofT).

**Q#**
- [Q#](https://www.microsoft.com/en-us/quantum/development-kit) - Microsoft's quantum programming language with Visual Studio integration.

**Silq**
- [Silq](https://silq.ethz.ch/) - Silq is a high-level quantum programming language with safe uncomputation and intuitive semantics.

## Quantum simulators

**C**
- [QuaC](https://github.com/0tt3r/QuaC) - Parallel time-dependent open quantum systems solver.
- [QuEST](https://github.com/aniabrown/QuEST) -  Quantum Exact Simulation Toolkit is a high performance multicore simulator of universal quantum circuits.
- [TNQVM](https://github.com/ornl-qci/tnqvm) - Tensor Network QPU Simulator for Eclipse [XACC](https://github.com/ORNL-QCI/xacc).

**Common Lisp**
- [QVM](https://github.com/rigetti/qvm) - Rigetti's high-performance quantum virtual machine.

**Coq**
- [QWIRE](https://github.com/jpaykin/QWIRE) - A quantum circuit language and formal verification tool [described in this paper](https://dl.acm.org/citation.cfm?id=3009894).

**C++**
- [Huawei HiQsimulator](https://github.com/Huawei-HiQ/HiQsimulator) - Single-amplitude, Full-amplitude and Error-correction circuit simulation engine.
- [Intel Quantum Simulator](https://github.com/intel/intel-qs) - Distributed qubit register quantum simulator using OpenMP and MPI.
- [JKQ-DDSIM](https://github.com/iic-jku/ddsim) - Error-free quantum simulator using decision diagrams as underlying data structure. ([arXiv](https://arxiv.org/abs/1707.00865) / [IEEE](https://ieeexplore.ieee.org/document/8355954))
- [qFlex](https://github.com/ngnrsaa/qflex) - Flexible high-performance simulator for verifying and benchmarking quantum circuits implemented on real hardware.
- [Qiskit Aer](https://github.com/Qiskit/qiskit-aer) - High performance simulator for quantum circuits that includes noise models (supported by IBM).
- [QCEAD](https://github.com/llens/QuantumComputingEvolutionaryAlgorithmDesign) - C++ program to both simulate a quantum computer and use parallel evolutionary techniques to design algorithms.
- [Qrack](https://github.com/vm6502q/qrack) - Comprehensive qubit and gate implementation for developing universal virtual quantum processors.
- [qSim](https://github.com/haykkh/qSim) - High level, elementary simulation library.
- [QSim](https://github.com/quantumlib/qsim) - Schrödinger and Schrödinger-Feynman simulators for quantum circuits.
- [Quantum++](https://github.com/softwareqinc/qpp) - [High-performance general purpose quantum simulator (can simulate d-dimensional qudits)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0208073).
- [tweedledum](https://github.com/boschmitt/tweedledum) - Library for synthesis, compilation, and optimization of quantum circuits.


**F#**
- [Liqui|>](http://stationq.github.io/Liquid/) - Toolsuite for quantum simulation developed by [Microsoft QuArC](https://www.microsoft.com/en-us/research/group/quantum-architectures-and-computation-group-quarc/).

**GoLang**
- [Q](https://github.com/itsubaki/q) - Quantum Computation Simulator written purely in GoLang.

**Java**
- [Strange](https://github.com/redfx-quantum/strange) - Java API that can be used to create Quantum Programs.

**JavaScript**
- [jsquil](https://github.com/mapmeld/jsquil) - JavaScript interface for writing [Quil](https://en.wikipedia.org/wiki/Quil_(instruction_set_architecture)) programs.
- [Quantum Circuit Simulator](https://github.com/perak/quantum-circuit) - Smoothly runs 20+ qubit simulations in browser or on node.js server.
- [Quirk](https://github.com/Strilanc/Quirk) - Drag-and-drop quantum circuit simulator in your browser.
- [Quantum JavaScript (Q.js)](https://quantumjavascript.app/) - Drag-and-drop circuit editor, simulator, documented API, text-as-circuit DSL, concept primers.
- [Quantum-computing-playground](https://github.com/gwroblew/Quantum-Computing-Playground) - Browser-based simple IDE interface to run, visualize and debug quantum programs.
- [Quantum tensors](https://github.com/Quantum-Game/quantum-tensors) - JavaScript / TypeScript package for sparse tensor operations on complex numbers for quantum computing.

**Julia**
- [Cliffords.jl](https://github.com/BBN-Q/Cliffords.jl) - Efficient calculation of Clifford circuits in Julia.
- [IonSim.jl](https://github.com/HaeffnerLab/IonSim.jl) - Simulate the dynamics of a configuration of trapped ions interacting with laser light.
- [QSimulator.jl](https://github.com/BBN-Q/QSimulator.jl) - Unitary and Lindbladian evolution in Julia.
- [QuantumInfo.jl](https://github.com/BBN-Q/QuantumInfo.jl) - Julia library for quantum information related calculations.
- [QuantumOptics.jl](https://qojulia.org/) - Numerical framework to simulate various kinds of open quantum systems in Julia.
- [RandomQuantum.jl](https://github.com/BBN-Q/RandomQuantum.jl) - Package for generating random quantum states and processes.
- [Yao.jl](https://github.com/QuantumBFS/Yao.jl) - Extensible, Efficient Quantum Algorithm Design for Humans.

**Python**
- [MISTIQS](https://github.com/USCCACS/MISTIQS) - Generating/compiling/executing quantum circuits for simulating quantum many-body dynamics of systems.
- [PIQS](https://github.com/nathanshammah/piqs) - Efficient simulation of open quantum dynamics of identical qubits.
- [QCircuits](https://github.com/grey-area/qcircuits) - User-friendly quantum circuit simulator designed for students and newcomers to quantum computing.
- [QCompute](https://github.com/baidu/QCompute) - [Baidu](http://research.baidu.com/Research_Areas/index-view?id=75)'s software development kit for designing quantum circuits and simulating on a high-performance simulator.
- [Qibo](https://github.com/Quantum-TII/qibo) - Framework for quantum simulation with hardware acceleration, including multi-GPU support.
- [QTop](https://github.com/jacobmarks/QTop) - Simulation and visualization of topological quantum computers.
- [quantum-computing](https://github.com/QuantumSystems/quantum-computing) - Functionally complete simulator for universal quantum computing in Python
- [quimb](https://github.com/jcmgray/quimb) - Easy but fast python library for quantum information and many-body calculations, including with tensor networks.
- [Quintuple](https://github.com/corbett/QuantumComputing) - Simulating the 5-qubit processor of the [IBM Quantum Experience](https://quantumexperience.ng.bluemix.net/qx/experience).
- [QuPy](https://github.com/ken-nakanishi/qupy) - Quantum circuit simulator for both CPU and GPU.
- [QuSpin](https://github.com/weinbe58/QuSpin) - Exact diagonalization and dynamics of arbitrary boson, fermion and spin many-body systems.
- [QuTiP](http://qutip.org/) - User-friendly and efficient numerical simulations of a wide variety of open quantum systems.
- [SeQuencing](https://github.com/sequencing-dev/sequencing) - Construct and simulate realistic quantum control sequences using QuTiP.
- [SimulaQron](https://github.com/StephanieWehner/SimulaQron) - Application level simulator of a quantum network.
- [Stim](https://github.com/quantumlib/Stim) - A fast stabilizer circuit simulator.
- [SQUANCH](https://github.com/att-innovate/squanch) - A distributed simulation framework for quantum networks and channels.
- [QuNetSim](https://github.com/tqsd/QuNetSim)- A quantum network simulation framework.
- [The Walrus](https://github.com/xanaduAI/thewalrus)- [Xanadu](https://www.xanadu.ai)'s library for simulating Gaussian Boson Sampling.

**Rust**
- [QCGPU](https://github.com/QCGPU/qcgpu-rust) - High-performance GPU-accelerated quantum computer simulation outlined in this [arXiv paper](https://arxiv.org/pdf/1805.00988.pdf).
- [RustQIP](https://github.com/Renmusxd/RustQIP) - Rust Quantum Computing library leveraging graph building to build efficient quantum circuit simulations.

**Swift**
- [SwiftQuantumComputing](https://github.com/indisoluble/SwiftQuantumComputing) - Quantum circuit simulator with a bit of genetic programming.

## Quantum annealing

**C++**
- [C-to-D-Wave](https://github.com/lanl/c2dwave) - Compile a very small subset of C to a D-Wave Hamiltonian function

**Go**
- [edif2qmasm](https://github.com/lanl/edif2qmasm/) - Compile [Verilog](https://en.wikipedia.org/wiki/Verilog), [VHDL](https://en.wikipedia.org/wiki/VHDL), and other hardware-description languages to a D-Wave Hamiltonian function
- [QA Prolog](https://github.com/lanl/QA-Prolog) - Compile a subset of [Prolog](https://en.wikipedia.org/wiki/Prolog) to a D-Wave Hamiltonian function

**Python**
- [chimera_embedding](https://github.com/dwavesystems/chimera-embedding) - Algorithms to generate native-structured embeddings for Chimera graphs.
- [dimod](https://github.com/dwavesystems/dimod) - Shared API for Ising and QUBO problems.
- [dwavebinarycsp](https://github.com/dwavesystems/dwavebinarycsp) - Map constraint satisfaction problems with binary variables to binary quadratic models.
- [dwave-cloud-client](https://github.com/dwavesystems/dwave-cloud-client) - Min. implementation of the REST interface to communicate with D-Wave's Solver API.
- [dwave_neal](https://github.com/dwavesystems/dwave-neal) - An implementation of a simulated annealing sampler.
- [dwave_networkx](https://github.com/dwavesystems/dwave_networkx) - Exploration and analysis of network graphs.
- [dwave-system](https://github.com/dwavesystems/dwave-system) - API for easily incorporating D-Wave quantum annealers as samplers in the [Ocean](https://ocean.dwavesys.com/) software stack.
- [embedding_utilities](https://github.com/dwavesystems/dwave_embedding_utilities) - Mapping samples between original and embedded graph.
- [micro_client_sapi_dimod](https://github.com/dwavesystems/dwave_micro_client_dimod) - [Dimod](https://github.com/dwavesystems/dimod) wrapper for the D-Wave Micro Client.
- [minorminer](https://github.com/dwavesystems/minorminer) - Heuristic tool for minor graph embedding.
- [penaltymodel](https://github.com/dwavesystems/penaltymodel) - Utilities and interfaces for using penalty models.
- [QMASM](https://github.com/lanl/qmasm/) - Quantum macro assembler for D-Wave systems

**Python, C & Matlab**
- [Qbsolv](https://github.com/dwavesystems/qbsolv) - QUBO solver with [D-Wave](https://www.dwavesys.com) or classical tabu solver backend.

## Quantum algorithms

**C++**
- [XACC VQE](https://github.com/ornl-qci/xacc-vqe) - Variational quantum eigensolver built on [XACC](https://github.com/ORNL-QCI/xacc) for distributed, and shared memory systems.

**Julia**
- [QuantumTomography.jl](https://github.com/BBN-Q/QuantumTomography.jl) - Julia package to perform quantum state and process tomography.

**Python**
- [Adapt](https://github.com/BBN-Q/Adapt) - Algorithms for adaptive refinement of measurements.
- [Arline Quantum](https://github.com/ArlineQ/arline_quantum) - Library with implementation of quantum gates and hardware, a part of [Arline Benchmarks](https://github.com/ArlineQ/arline_benchmarks) project.
- [FermiLib](https://github.com/ProjectQ-Framework/FermiLib) - Software for analyzing fermionic quantum simulation algorithms with [ProjectQ](https://github.com/ProjectQ-Framework/ProjectQ).
- [Grove](https://github.com/rigetticomputing/grove) - Quantum algorithms implemented using [Rigetti](https://www.rigetti.com/)'s [pyQuil](https://github.com/rigetticomputing/pyquil).
- [OpenFermion](https://github.com/quantumlib/OpenFermion) - Compiling and analyzing quantum algorithm for quantum chemistry simulations.
- [Paddle Quantum](https://github.com/PaddlePaddle/Quantum) - Quantum machine learning platform to construct & train quantum neural networks, developed by Baidu.
- [PennyLane](https://github.com/XanaduAI/pennylane) - Library for quantum ML, automatic differentiation and optimization of hybrid computations.
- [PyZFS](https://github.com/hema-ted/pyzfs) - Package to compute zero-field-splitting tensors for molecules and spin quantum bits in semiconductors.
- [QFog](https://github.com/artiste-qb-net/quantum-fog) - Framework for analyzing both classical and quantum Bayesian Networks.
- [QGrad](https://github.com/qgrad/qgrad) - Library to integrate automatic differentiation tools such as JAX with QuTiP and related quantum software packages.
- [Qiskit Aqua](https://github.com/Qiskit/qiskit-aqua) - Library of various quantum algorithm implemented with [Qiskit](https://github.com/Qiskit/qiskit).
- [Qiskit Nature](https://github.com/Qiskit/qiskit-nature) - Quantum Chemistry including ground state, excited states and dipole moment calculations.
- [QPanda](https://github.com/OriginQ/QPanda-2) - QPanda is a quantum computing framework that can be used to build, run, and optimize quantum algorithms.
- [Qiskit Tutorial](https://github.com/QISKit/qiskit-tutorial) - Jupyter notebook filled with tutorials for [Qiskit](https://github.com/QISKit/qiskit).
- [Quantum_Edward](https://github.com/artiste-qb-net/Quantum_Edward) - Python tools for supervised learning by Quantum Neural Networks
- [QuantumFlow](https://github.com/rigetti/quantumflow) - Quantum Algorithms Development Toolkit e.g. allowing for backpropagation with QAOA.
- [Quantum TSP](https://github.com/mstechly/quantum_tsp_tutorials) - Tutorials on solving Travelling Salesman Problem using quantum computing (QAOA).
- [Tensorflow Quantum](https://www.tensorflow.org/quantum) - Library for hybrid quantum-classical machine learning.
- [VQF](https://github.com/mstechly/vqf) - Implementation of Variational Quantum Factoring algorithm (in pyQuil)
- [WebMark](https://github.com/ohtu2021-kvantti/WebMark) - Web platform for benchmarking quantum computing algorithms.
- [XACC Examples](https://github.com/ORNL-QCI/xacc-examples) - Example code using [XACC](https://github.com/ORNL-QCI/xacc) for quantum computing.
- [XACC QChem](https://github.com/ORNL-QCI/xacc-qchem-benchmarks) - QPU Benchmarks for Quantum Chemistry via [XACC](https://github.com/ORNL-QCI/xacc), [Psi4](http://www.psicode.org/) and [OpenFermion](https://github.com/quantumlib/OpenFermion).

**Q#**
- [Quantum Katas](https://github.com/Microsoft/QuantumKatas) -  Programming exercises for learning Q# and quantum computing.

## Quantum compilers

**C++**
- [QCOR](https://github.com/ORNL-QCI/qcor) - C++ language extension and associated compiler implementation for hybrid quantum-classical programming.
- [ScaffCC](https://github.com/epiqc/ScaffCC) - Compilation, analysis and optimization framework for the Scaffold quantum programming language.
- [tweedledum](https://github.com/boschmitt/tweedledum) - C++17 library for analysis, compilation/synthesis, and optimization of quantum circuits.

**Mathematica**
- [UniversalQCompiler](https://github.com/Q-Compiler/UniversalQCompiler) - Synthesis of isometries (including unitaries and state preparation), channels and POVMs.

**Python**
- [Arline Benchmarks](https://github.com/ArlineQ/arline_benchmarks) - Automated benchmarking platform for quantum compilers, quantum hardware and quantum algorithms.
- [BQSKit](https://github.com/BQSKit) - Berkeley Quantum Synthesis Toolkit is an optimizing quantum compiler and related tool-set.
- [Mitiq](https://github.com/unitaryfund/mitiq) - Cross-platform, error-mitigating quantum compiler from [Unitary Fund](https://unitary.fund/).
- [PyZX](https://github.com/Quantomatic/pyzx) - Python library for quantum circuit rewriting and optimisation using the ZX-calculus.
- [QEDA](https://github.com/Spooky-Manufacturing/QEDA) - Quantum electronic design automation software for optical circuits using QASM.
- [QGL2 Compiler](https://github.com/BBN-Q/pyqgl2) - Language compiler for imperative Quantum Gate Language ([QGL](https://github.com/BBN-Q/QGL)).
- [Qiskit Terra](https://github.com/Qiskit/qiskit-terra) - Python library for quantum circuit rewriting and optimization (supported by IBM).
- [Qubiter](https://github.com/artiste-qb-net/qubiter) - Quantum compiler with Python wrapper for [LAPACK's CS Decomposition](http://www.netlib.org/lapack/README-CSD.html) to build a binary tree of matrices.

**Common Lisp**
- [quilc](https://github.com/rigetti/quilc) - Rigetti's optimizing Quil compiler.

## Quantum assembly

- [Blackbird](https://github.com/XanaduAI/blackbird) - Open-source quantum instruction language currently used for Xanadu's photonic hardware.
- [OpenQASM](https://github.com/QISKit/openqasm) - Open-source quantum assembly language.
- [QMASM](https://github.com/lanl/qmasm) - A quantum macro assembler for D-Wave's quantum annealers.
- [Quil](https://arxiv.org/abs/1608.03355) - An open hybrid quantum/classical instruction set currently used by Rigetti. [Parser](https://github.com/rigetticomputing/pyquil/tree/master/pyquil/_parser)

## Quantum control

**Python**
- [C3](https://github.com/q-optimize/c3) - Open-loop, closed-loop and automated Control, Calibration and Characterization of quantum devices.
- [Krotov](https://github.com/qucontrol/krotov) - Python implementation of Krotov's method for quantum optimal control.

## Quantum error correction

**Python**
- [PyMatching](https://github.com/oscarhiggott/PyMatching) - Python package for decoding quantum error correcting codes with minimum-weight perfect matching.
- [qecsim](https://github.com/qecsim/qecsim) - Python package for simulating quantum error correction using stabilizer codes.
- [Qsurface](https://github.com/watermarkhu/qsurface) - Python package for simulation and visualization of quantum error-correction on surface codes.

## Quantum and post-quantum cryptography

**C**
- [liboqs](https://github.com/open-quantum-safe/liboqs) - C library for quantum-resistant cryptographic algorithms.
- [openssh](https://github.com/open-quantum-safe/openssh-portable) - OpenSSH with quantum-safe key exchange algorithms.
- [openssl](https://github.com/open-quantum-safe/openssl) - OpenSSL with quantum-safe cryptographic algorithms.
- [PQClean](https://github.com/PQClean/PQClean) - Clean, portable, tested implementations of post-quantum cryptography.

**Python**
- [QRL](https://github.com/theQRL/QRL/) - [Quantum Resistant Ledger](https://theqrl.org/) utilizing hash-based one-time merkle tree signature scheme instead of ECDSA.

## Experimental quantum computing

**Julia**
- [Qlab.jl](https://github.com/BBN-Q/Qlab.jl) - Generic lab tools in Julia.

**Matlab**
- [Qlab](https://github.com/BBN-Q/Qlab) - Measurement and control software for superconducting qubits.

**Python**
- [ARTIQ](https://github.com/m-labs/artiq) - Next-generation control system for quantum information experiments.
- [OLSQ](https://github.com/tbcdebug/OLSQ) - OpenQASM package to perform optimal layout synthesis for quantum computing.
- [pyEPR](https://github.com/zlatko-minev/pyEPR) - Automated Python module for the design and quantization of Josephson quantum circuits.
- [PyRPL](https://github.com/lneuhaus/pyrpl) - Turn your RedPitaya into a powerful DSP device, suitable as a digital lockbox and measurement device in quantum optics.
- [QCoDeS](https://github.com/QCoDeS/Qcodes) - Python-based data acquisition framework for quantum experiments.
- [QFlow-lite](https://github.com/jpzwolak/QFlow-lite) - Machine Learning tools for autotuning quantum dot experiments.
- [QGL](https://github.com/BBN-Q/QGL) -  Domain-specific language embedded in Python for specifying pulse sequences.
- [Qiskit Metal](https://github.com/Qiskit/qiskit-metal) - Quantum hardware design and analysis.
- [QTT](https://github.com/QuTech-Delft/qtt) - Quantum Technology Toolbox is a framework for the tuning and calibration of quantum dots and spin qubits.
- [Quantify](https://gitlab.com/quantify-os/quantify-core) -  Data acquisition platform focused on Quantum Computing and solid-state physics experiments.
- [qupulse](https://github.com/qutech/qupulse) - Quantum computing pulse parametrization and sequencing framework (formerly qc-toolkit).
- [scqubits](https://github.com/scqubits/scqubits) - Simulating superconducting qubits, obtaining energy spectra, plotting energy levels and more.

## Quantum fun

**Board games**
- [Entanglion](https://github.com/Entanglion/entanglion) - The world’s first open source quantum computing board game. For 2 players.

**F#**
- [Quantum Puzzle Generator](https://github.com/mrdimosthenis/QuantumPuzzleGenerator) - An educational puzzle game for Android and iOS.

**Python**
- [bloqit](https://github.com/kelzheng/bloqit) - A tiny qubit duel for your smart phone.
- [QiskitBlocks](https://github.com/JavaFXpert/QiskitBlocks) - Game that teaches quantum computing using Qiskit in a Minetest block world. 
- [Quantum Awesomeness](https://github.com/decodoku/A_Game_to_Benchmark_Quantum_Computers)  - [Simple puzzles to benchmark various quantum processor](https://medium.com/@decodoku/understanding-quantum-computers-through-a-simple-puzzle-game-a290dde89fb2).
- [Quantum Battleships](https://github.com/decodoku/Battleships_with_complementary_measurements) - [Playing battleships with quantum measurements](https://medium.com/@decodoku/how-to-program-a-quantum-computer-part-2-f0d3eee872fe).
- [Quantum Catsweeper](https://github.com/desireevl/quantum-catsweeper) - Quantum game loosely based on Minesweeper Flag.
- [SudoQ](https://github.com/subwayHareArmy/SudoQ) - Sudoku solver that leverages a D-Wave Quantum Annealer.

**Python & JavaScript**
- [Quantum Music Composer for IBM Q](https://github.com/JavaFXpert/quantum-toy-piano-ibmq) - Compose and perform quantum music with IBM Q.
- [Quantum Music Composer for Rigetti](https://github.com/JavaFXpert/quantum-toy-piano) - Compose and perform quantum music with Rigetti's Forest.

**JavaScript**
- [Quantum Game with Photons](https://github.com/stared/quantum-game) - Puzzle game in browser, with polarization, superposition, and measurement.

**Scala**
- [feyn](https://mrdimosthenis.github.io/feyn) - Puzzle game for the browser in which you need to find the combination of gates that the qubits need to pass.

## Quantum tools

**Mathematica**
- [Quantum](http://homepage.cem.itesm.mx/lgomez/quantum/) - A free Mathematica add-on for Dirac Bra-Ket Notation, Quantum Algebra, Quantum Computing and the QHD approximation to the Heisenberg Equations of Motion.
- [QI](https://github.com/rogercolbeck/QI) - Toolkit for common quantum information functions.

**Python**
- [IBM Q bot](https://github.com/RQC-QApp/QuantumComputingBot) - Bot for Slack and Telegram to monitor the load of IBM Q quantum computers.
- [pulsemaker](https://github.com/adgt/pulsemaker) - A Python widget library for designing pulses and pulse schedules for quantum computing hardware. 
- [pyQuirk](https://github.com/adgt/pyQuirk) - A Python widget for Quirk to be used in Jupyter notebooks, JupyterLab, and the IPython kernel.
- [qonduit](https://github.com/adgt/qonduit) - A Python library with visualization tools and workflows for quantum computing that utilize the best of what’s available.
- [qprof](https://gitlab.com/qcomputing/qprof/qprof) - `gprof`-compatible profiler for quantum programs.
- [QRAND](https://github.com/pedrorrivero/qrand) - A multiplatform and multiprotocol quantum random number generator for arbitrary probability distributions.
- [QuantumGraphs](https://github.com/ziofil/QuantumGraphs) - Grow and study random graphs by a continuous, randomly collapsing quantum walk.
- [toqito](https://github.com/vprusso/toqito) - Framework to study problems pertaining to entanglement theory, nonlocal games, and other aspects of quantum information.

**Others**
- [Quil syntax highlighter](https://github.com/JavaFXpert/quil-syntax-highlighter) - Syntax highlighter for PyCharm.

## Abandoned projects
*2+ years of inactivity. Feel free to reanimate, document and contribute to some of this work!*
- [BLACK-STONE](https://github.com/thephoeron/black-stone) - Specification and implementation of quantum common lisp, for gate-model quantum computers.
- [libquantum](http://libquantum.de) - C library for quantum computing and quantum simulation.
- [libQuantumJava](https://github.com/gbanegas/libQuantumJava) - Crude translation from the C implementation of `libquantum` to a Java version.
- [jquil](https://github.com/QCHackers/jquil) - Java library for quantum programming using [Quil](https://en.wikipedia.org/wiki/Quil_(instruction_set_architecture)).
- [pQCS](https://qsoft.iqc.uwaterloo.ca/#software) - [Parallel quantum circuit synthesis](https://uwspace.uwaterloo.ca/handle/10012/9267) with optimal T-count.
- [PyQLab](https://github.com/BBN-Q/PyQLab) - Library for instrument control and superconducting QIP experiments.
- [PySimulator](https://github.com/BBN-Q/PySimulator) - Python with C++ backend simulator for superconducting circuits.
- [QACG](https://github.com/QCT-IQC/qacg) - Quantum Arithmetic Circuit Generator in Haskell.
- [QCL](https://github.com/aviggiano/qcl) - High level, hardware-agnostic programming language for quantum computers (syntax like C or Pascal).
- [QCViewer](https://github.com/QCT-IQC/QCViewer) - Visual quantum circuit design and simulation tool.
- [QGL.jl](https://github.com/BBN-Q/QGL.jl) - Performance orientated [QGL](https://github.com/BBN-Q/QGL) compiler.
- [Qlmp](https://github.com/wintershammer/QImp) -  Interpreter for the functional quantum programming language Qumin.
- [Qiskit-JS](https://github.com/Qiskit/qiskit-js) - [Quantum information software kit](https://qiskit.org/) for JavaScript (supported by IBM).
- [QOCS](https://github.com/dillanchang/QOCS) - Quantum OCaml Circuit Simulator is a functional approach to simulating quantum gates.
- [QuantumUtils](https://github.com/QuantumUtils/quantum-utils-mathematica) - Tools for quantum control, simulation, channel representation conversion, and perturbations.
- [Quantum Virtual Machine](https://github.com/rigetticomputing/reference-qvm) - Reference implementation of Rigetti's Quantum Virtual Machine.
- [Quince](https://github.com/BBN-Q/Quince) - Node-based GUI that allows for graphical configuration of qubit experiments in Auspex.
- [Quipper](https://github.com/thephoeron/quipper-language) - Scalable functional programming language for quantum computing based on [Quantum Lambda Calculus](https://arxiv.org/abs/cs/0404056).
- [QuSim](https://github.com/adamisntdead/QuSimPy) - Ideal noise-free multi-qubit simulator written in 150 lines of code.
- [QSEL](https://github.com/dabacon/qsel) -  Quantum programming language putting entanglement and superposition front and center.
- [sapi_dimod](https://github.com/dwavesystems/dwave_sapi_dimod) - [Dimod](https://github.com/dwavesystems/dimod) wrapper for D-Wave's Solver API (SAPI).
- [Squankum](https://github.com/jeffwass/Squankum) - Visual Java quantum simulator.

## Contributing
See the [contribution guidelines](CONTRIBUTING.md/#readme).

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the Quantum Open Source Foundation has waived all copyright and related or neighboring rights to this work.
