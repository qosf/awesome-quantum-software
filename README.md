<p align="center"><img src="hopf_fibration.png" alt="bDialog" height="300px"></p>

# Open-Source Quantum Software Projects

[![Twitter Follow](https://img.shields.io/twitter/follow/qosfoundation?style=social)](https://twitter.com/qosfoundation)

Curated list of open-source developed quantum software projects.

*Please read the [contribution guidelines](CONTRIBUTING.md#readme) before contributing.*

Also please check out the [Unitary Fund](http://unitary.fund/)'s 4k$ grant project for quantum OSS!

Clone this repository into your qBraid account:

[<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com?gitHubUrl=https://github.com/qosf/awesome-quantum-software.git)

## Contents
- [Quantum full-stack libraries](#quantum-full-stack-libraries)
- [Quantum simulators](#quantum-simulators)
- [Quantum analog Hamiltonian](#quantum-analog-hamiltonian)
- [Quantum annealing](#quantum-annealing)
- [Quantum algorithms](#quantum-algorithms)
- [Quantum compilers](#quantum-compilers)
- [Quantum converters](#quantum-converters)
- [Quantum assembly](#quantum-assembly)
- [Quantum control](#quantum-control)
- [Quantum interoperability](#quantum-interoperability)
- [Quantum error correction](#quantum-error-correction)
- [Quantum and post-quantum cryptography](#quantum-and-post-quantum-cryptography)
- [Experimental quantum computing](#experimental-quantum-computing)
- [Quantum fun](#quantum-fun)
- [Quantum tools](#quantum-tools)
- [Quantum data](#quantum-data)
- [Abandoned projects](#abandoned-projects)
- [Contributing](#contributing)
- [License](#license)

For a curated list of learning resources please check out [desireevl's repo](https://github.com/desireevl/awesome-quantum-computing).

## Quantum full-stack libraries

**C++**
- [avaloni](https://github.com/avalon-lang/avaloni) - Programming language (interpreter) for classical-quantum hybrid computers.
- [CUDA-Q](https://github.com/NVIDIA/cuda-quantum) - Platform for accelerated quantum-classical applications on GPUs, CPUs and QPUs.
- [qpp](https://github.com/softwareQinc/qpp) - Quantum++ is a modern C++ general purpose quantum computing library, composed solely of template header files.
- [Qristal](https://github.com/qbrilliance/qristal) - Quantum Brilliance's hybrid quantum-classical C++/Python development platform ([docs](https://qristal.readthedocs.io); [core module](https://github.com/qbrilliance/qristal-core)).
- [staq](https://github.com/softwareqinc/staq) - Full stack quantum processing toolkit ([arXiv paper](https://arxiv.org/abs/1912.06070)).
- [XACC](https://github.com/ORNL-QCI/xacc) - Extreme-scale programming model for quantum acceleration within high-performance computing ([arXiv paper](https://arxiv.org/abs/1710.01794)).

**Python**
- [blueqat](https://github.com/Blueqat/Blueqat) - Quantum computing SDK.
- [bosonic-qiskit](https://github.com/C2QA/bosonic-qiskit) - Simulate hybrid boson-qubit systems within Qiskit, implemented as a part of the Co-design Center for Quantum Advantage (C2QA) of the National Quantum Initiative.
- [Braket](https://github.com/amazon-braket/amazon-braket-sdk-python) - [Amazon's](https://aws.amazon.com/braket/) fully managed quantum computing service for building quantum algorithms.
- [Cirq](https://github.com/quantumlib/Cirq) - Framework for creating, editing, and invoking Noisy Intermediate Scale Quantum (NISQ) circuits.
- [CUDA-Q](https://github.com/NVIDIA/cuda-quantum) - Platform for accelerated quantum-classical applications on GPUs, CPUs and QPUs.
- [Forest](https://github.com/rigetticomputing/pyquil) - [Rigetti](https://www.rigetti.com/)'s software library for writing, simulating, compiling and executing quantum programs.
- [Ket](https://quantumket.org) - Embedded programming language that introduces the ease of Python to quantum programming.
- [Ocean](https://github.com/dwavesystems/dwave-ocean-sdk) - [D-Wave System](https://www.dwavesys.com/home)'s suite of tools for solving hard problems with quantum computers.
- [OpenQL](https://github.com/QE-Lab/OpenQL) - Compiler framework with algorithm libraries, optimizer, scheduler, QEC, mapping, micro-code generator.
- [PennyLane](https://pennylane.ai) - Cross-platform Python library for differentiable programming of quantum computers.
- [Perceval](https://github.com/Quandela/Perceval) - [Quandela](https://www.quandela.com)'s software library for programming realistic photonic quantum computers.
- [ProjectQ](https://github.com/ProjectQ-Framework/ProjectQ) - Hardware-agnostic framework with compiler and simulator with emulation capabilities.
- [PyQudit](https://github.com/Ordoptimus/pyqudit) - Python package for generalized and universal versions of quantum gates in N-dimensions.
- [pytket](https://docs.quantinuum.com/tket/) - Quantum computing toolkit for building, compiling, and executing quantum circuits (developed by Quantinuum).
- [Qadence](https://github.com/pasqal-io/qadence) - [Pasqal](https://www.pasqal.com)'s package for building differentiable digital and digital-analog quantum programs realizable on neutral atom devices.
- [quantumcat](https://github.com/artificial-brain/quantumcat/) - Cross-platform open-source high-level quantum computing library focused on building applications.
- [Qibo](https://github.com/qiboteam/qibo) - An open-source framework for quantum simulation, self-hosted quantum hardware control and calibration.
- [Qiskit](https://qiskit.org/) - Framework for noisy quantum computers at the level of pulses, circuits, and algorithms (supported by IBM).
- [Qrisp](https://qrisp.eu/) - A high-level programming language and framework for creating and compiling quantum algorithms ([GitHub](https://github.com/eclipse-qrisp/Qrisp)).
- [Qristal](https://github.com/qbrilliance/qristal) - Quantum Brilliance's hybrid quantum-classical C++/Python development platform ([docs](https://qristal.readthedocs.io); [core module](https://github.com/qbrilliance/qristal-core)).
- [quantum-os](https://github.com/quantumos-org/quantum-os) - Operating system based on Linux kernel for quantum computing.
- [Strawberry Fields](https://github.com/xanaduai/strawberryfields) - [Xanadu](https://www.xanadu.ai)'s software library for photonic quantum computing.
- [Tangelo](https://github.com/goodchemistryco/Tangelo) and [Tangelo-Examples](https://github.com/goodchemistryco/Tangelo-Examples/) - Toolkit for quantum chemistry simulation workflows on quantum computers, maintained by [SandboxAQ](https://www.sandboxaq.com/).
- [TensorCircuit](https://github.com/tencent-quantum-lab/tensorcircuit) - Tensor network based quantum software framework for the NISQ era.
- [Tequila](https://github.com/aspuru-guzik-group/tequila) - Extensible Quantum Information and Learning Architecture developed by Alan Aspuru-Guzik's group (UofT).

**Q#**
- [Q#](https://www.microsoft.com/en-us/quantum/development-kit) - Microsoft's quantum programming language with Visual Studio integration.

**Silq**
- [Silq](https://silq.ethz.ch/) - Silq is a high-level quantum programming language with safe uncomputation and intuitive semantics.

## Quantum simulators

**Assembly**
- [Quplexity](https://github.com/MrGilli/Quplexity) - Modular toolkit for QC simulators. Quplexity offers essential mathematical functions and logic relative to quantum computer simulation. Quplexity is written in ARM(64) and x86 Assembly, which results in improved performance and "weight" benefits.

**C**
- [QuaC](https://github.com/0tt3r/QuaC) - Parallel time-dependent open quantum systems solver.
- [QuEST](https://github.com/aniabrown/QuEST) -  Quantum Exact Simulation Toolkit is a high performance multicore simulator of universal quantum circuits.
- [TNQVM](https://github.com/ornl-qci/tnqvm) - Tensor Network QPU Simulator for Eclipse [XACC](https://github.com/ORNL-QCI/xacc).

**Common Lisp**
- [QVM](https://github.com/rigetti/qvm) - Rigetti's high-performance quantum virtual machine.

**Coq**
- [QWIRE](https://github.com/jpaykin/QWIRE) - Quantum circuit language and formal verification tool [described in this paper](https://dl.acm.org/citation.cfm?id=3009894).

**C++**
- [Huawei HiQsimulator](https://github.com/Huawei-HiQ/HiQsimulator) - Single-amplitude, Full-amplitude and Error-correction circuit simulation engine.
- [Intel Quantum Simulator](https://github.com/intel/intel-qs) - Distributed qubit register quantum simulator using OpenMP and MPI.
- [MQT DDSIM](https://github.com/cda-tum/mqt-ddsim) - Quantum circuit simulator using decision diagrams as a datastructure. Python interface and Qiskit backend via the [`mqt.ddsim`](https://pypi.org/p/mqt.ddsim) Python package.
- [PennyLane Lightning](https://github.com/PennyLaneAI/pennylane-lightning) - Fast state-vector simulator written in C++. GPU support. Python interface via [PennyLane](https://pennylane.ai).
- [qFlex](https://github.com/ngnrsaa/qflex) - Flexible high-performance simulator for verifying and benchmarking quantum circuits implemented on real hardware.
- [Qiskit Aer](https://github.com/Qiskit/qiskit-aer) - High performance simulator for quantum circuits that includes noise models (supported by IBM).
- [QCEAD](https://github.com/llens/QuantumComputingEvolutionaryAlgorithmDesign) - C++ program to both simulate a quantum computer and use parallel evolutionary techniques to design algorithms.
- [QCSim](https://github.com/aromanro/QCSim) - Quantum computing simulator with many algorithms as examples and tests ([blog post](https://compphys.go.ro/quantum-computing-simulator/)).
- [QPlayer](https://github.com/eQuantumOS/QPlayer) - Light-weight, scalable and fast quantum Schrödinger simulator ([paper](https://onlinelibrary.wiley.com/doi/full/10.4218/etrij.2021-0442)).
- [Qrack](https://github.com/vm6502q/qrack) - Comprehensive qubit and gate implementation for developing universal virtual quantum processors.
- [qSim](https://github.com/haykkh/qSim) - High level, elementary simulation library.
- [QSim](https://github.com/quantumlib/qsim) - Schrödinger and Schrödinger-Feynman simulators for quantum circuits.
- [Quantum++](https://github.com/softwareqinc/qpp) - High-performance general purpose quantum simulator (can simulate d-dimensional qudits) ([paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0208073)).
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
- [BosonSampling.jl](https://github.com/benoitseron/BosonSampling.jl) - Efficient simulation of multiphoton interference.
- [Cliffords.jl](https://github.com/BBN-Q/Cliffords.jl) - Efficient calculation of Clifford circuits in Julia.
- [IonSim.jl](https://github.com/HaeffnerLab/IonSim.jl) - Simulate the dynamics of a configuration of trapped ions interacting with laser light.
- [KadanoffBaym.jl](https://github.com/NonequilibriumDynamics/KadanoffBaym.jl) - Adaptive many-body time evolution of non-equilibrium Green functions.
- [PauliStrings.jl](https://github.com/nicolasloizeau/PauliStrings.jl) - Many-body simulations in the Pauli strings representation.
- [QSimulator.jl](https://github.com/BBN-Q/QSimulator.jl) - Unitary and Lindbladian evolution in Julia.
- [QuantumInfo.jl](https://github.com/BBN-Q/QuantumInfo.jl) - Julia library for quantum information related calculations.
- [QuantumOptics.jl](https://qojulia.org/) - Numerical framework to simulate various kinds of open quantum systems in Julia.
- [RandomQuantum.jl](https://github.com/BBN-Q/RandomQuantum.jl) - Package for generating random quantum states and processes.
- [Yao.jl](https://github.com/QuantumBFS/Yao.jl) - Extensible, Efficient Quantum Algorithm Design for Humans.

**Python**
- [Dynamiqs](https://www.dynamiqs.org/) - High-performance quantum systems simulation with JAX (GPU-accelerated & differentiable).
- [Graphix](https://github.com/TeamGraphix/graphix) - Measurement-Based Quantum Computing (MBQC) compiler, simulator and QPU interface.
- [Horqrux](https://github.com/pasqal-io/horqrux) - Jax-based quantum state vector simulator tailored for quantum machine learning from [Pasqal](https://www.pasqal.com).
- [Interlin-q](https://github.com/Interlin-q/Interlin-q) - Quantum network simulator imitating distributed quantum systems with interconnect communication between nodes.
- [MentPy](https://github.com/BestQuark/mentpy) - Python package for creating and simulating Measurement-based Quantum Computating (MBQC) programs.
- [MISTIQS](https://github.com/USCCACS/MISTIQS) - Generating/compiling/executing quantum circuits for simulating quantum many-body dynamics of systems.
- [Piquasso](https://github.com/Budapest-Quantum-Computing-Group/piquasso) - A photonic quantum computing simulator library written in Python/C++.
- [PIQS](https://github.com/nathanshammah/piqs) - Efficient simulation of open quantum dynamics of identical qubits.
- [PyQTorch](https://github.com/pasqal-io/pyqtorch) - PyTorch-based state vector simulator designed for quantum machine learning from [Pasqal](https://www.pasqal.com).
- [QCircuits](https://github.com/grey-area/qcircuits) - User-friendly quantum circuit simulator designed for students and newcomers to quantum computing.
- [QCompute](https://github.com/baidu/QCompute) - [Baidu](http://research.baidu.com/Research_Areas/index-view?id=75)'s software development kit for designing quantum circuits and simulating on a high-performance simulator.
- [Qibo](https://github.com/qiboteam/qibo) - Framework for quantum simulation with hardware acceleration using just-in-time compilation.
- [QTop](https://github.com/jacobmarks/QTop) - Simulation and visualization of topological quantum computers.
- [quantum-computing](https://github.com/QuantumSystems/quantum-computing) - Functionally complete simulator for universal quantum computing in Python
- [Quditto](https://github.com/Networks-it-uc3m/Quditto) - QKD Network emulator that automatically deploys distributed, ETSI GS QKD 014–compliant QKD networks.
- [QuForge](https://github.com/tiago939/QuForge) - Python package for qudit simulation.
- [quimb](https://github.com/jcmgray/quimb) - Easy but fast python library for quantum information and many-body calculations, including with tensor networks.
- [Quintuple](https://github.com/corbett/QuantumComputing) - Simulating the 5-qubit processor of the [IBM Quantum Experience](https://quantumexperience.ng.bluemix.net/qx/experience).
- [QuPy](https://github.com/ken-nakanishi/qupy) - Quantum circuit simulator for both CPU and GPU.
- [QuSpin](https://github.com/weinbe58/QuSpin) - Exact diagonalization and dynamics of arbitrary boson, fermion and spin many-body systems.
- [QuTiP](http://qutip.org/) - User-friendly and efficient numerical simulations of a wide variety of open quantum systems.
- [SeQuencing](https://github.com/sequencing-dev/sequencing) - Construct and simulate realistic quantum control sequences using QuTiP.
- [SimulaQron](https://github.com/StephanieWehner/SimulaQron) - Application level simulator of a quantum network.
- [SOQCS](https://github.com/SOQCSAdmin/SOQCS) - Library to define, simulate, and study non-ideal quantum optical circuits (API provided both in Python and C++).
- [Stim](https://github.com/quantumlib/Stim) - Fast stabilizer circuit simulator.
- [SQUANCH](https://github.com/att-innovate/squanch) - Distributed simulation framework for quantum networks and channels.
- [QuNetSim](https://github.com/tqsd/QuNetSim) - Quantum network simulation framework.
- [The Walrus](https://github.com/xanaduAI/thewalrus) - [Xanadu](https://www.xanadu.ai)'s library for simulating Gaussian Boson Sampling.
- [gdsfactory](https://gdsfactory.github.io/gdsfactory/) and [plugins](https://gdsfactory.github.io/gplugins) - Open Source Python library designed for crafting chips (Photonics, Analog, Quantum, MEMs, and more), 3D printed objects, and PCBs. Plugins for Simulating Analog, RF, and Photonics circuits.

**Rust**
- [QCGPU](https://github.com/QCGPU/qcgpu-rust) - High-performance GPU-accelerated quantum computer simulation outlined in this [arXiv paper](https://arxiv.org/pdf/1805.00988.pdf).
- [Quriust](https://github.com/ScipioneParmigiano/quriust) - A blazing fast Rust library for simulating quantum circuits. Only for quriust ones.
- [RustQIP](https://github.com/Renmusxd/RustQIP) - Rust Quantum Computing library leveraging graph building to build efficient quantum circuit simulations.

**Swift**
- [SwiftQuantumComputing](https://github.com/indisoluble/SwiftQuantumComputing) - Quantum circuit simulator with a bit of genetic programming.

## Quantum Analog Hamiltonian

- [Bloqade](https://github.com/QuEraComputing/Bloqade.jl) - Package for the quantum computation and quantum simulation based on the neutral-atom architecture.
- [Pulser](https://github.com/pasqal-io/Pulser) - Python library for pulse-level/analog control of neutral atom devices.

## Quantum annealing

**C++**
- [C-to-D-Wave](https://github.com/lanl/c2dwave) - Compile a very small subset of C to a D-Wave Hamiltonian function

**Go**
- [edif2qmasm](https://github.com/lanl/edif2qmasm/) - Compile [Verilog](https://en.wikipedia.org/wiki/Verilog), [VHDL](https://en.wikipedia.org/wiki/VHDL), and other hardware-description languages to a D-Wave Hamiltonian function
- [QA Prolog](https://github.com/lanl/QA-Prolog) - Compile a subset of [Prolog](https://en.wikipedia.org/wiki/Prolog) to a D-Wave Hamiltonian function

**Julia**
- [QAOA.jl](https://github.com/FZJ-PGI-12/QAOA.jl) - Simulate quantum annealing and mean-field quantum annealing in Julia.

**Python**
- [chimera_embedding](https://github.com/dwavesystems/chimera-embedding) - Algorithms to generate native-structured embeddings for Chimera graphs.
- [dimod](https://github.com/dwavesystems/dimod) - Shared API for Ising and QUBO problems.
- [dwavebinarycsp](https://github.com/dwavesystems/dwavebinarycsp) - Map constraint satisfaction problems with binary variables to binary quadratic models.
- [dwave-cloud-client](https://github.com/dwavesystems/dwave-cloud-client) - Min. implementation of the REST interface to communicate with D-Wave's Solver API.
- [dwave_neal](https://github.com/dwavesystems/dwave-neal) - Implementation of a simulated annealing sampler.
- [dwave_networkx](https://github.com/dwavesystems/dwave_networkx) - Exploration and analysis of network graphs.
- [dwave-system](https://github.com/dwavesystems/dwave-system) - API for easily incorporating D-Wave quantum annealers as samplers in the [Ocean](https://ocean.dwavesys.com/) software stack.
- [embedding_utilities](https://github.com/dwavesystems/dwave_embedding_utilities) - Mapping samples between original and embedded graph.
- [micro_client_sapi_dimod](https://github.com/dwavesystems/dwave_micro_client_dimod) - [Dimod](https://github.com/dwavesystems/dimod) wrapper for the D-Wave Micro Client.
- [minorminer](https://github.com/dwavesystems/minorminer) - Heuristic tool for minor graph embedding.
- [penaltymodel](https://github.com/dwavesystems/penaltymodel) - Utilities and interfaces for using penalty models.
- [QMASM](https://github.com/lanl/qmasm/) - Quantum macro assembler for D-Wave systems
- [qubo-nn](https://github.com/instance01/qubo-nn/) - Classifying, auto-encoding and reverse-engineering QUBO matrices. Also includes 20 problem formulations.
- [qubovert](https://github.com/jtiosue/qubovert) - Formulating and simulated annealing of Ising, QUBO, and higher order problems with constraints.

**Python, C & Matlab**
- [Qbsolv](https://github.com/dwavesystems/qbsolv) - QUBO solver with [D-Wave](https://www.dwavesys.com) or classical tabu solver backend.

## Quantum algorithms

**C++**
- [XACC VQE](https://github.com/ornl-qci/xacc-vqe) - Variational quantum eigensolver built on [XACC](https://github.com/ORNL-QCI/xacc) for distributed, and shared memory systems.

**HTML**
- [myQShor](https://github.com/Michaelvll/myQShor) - Quantum implementation of Shor's algorithm.

**Julia**
- [QAOA.jl](https://github.com/FZJ-PGI-12/QAOA.jl) - Implementation the Quantum Approximate Optimization Algorithm (QAOA) in Julia.
- [QuantumTomography.jl](https://github.com/BBN-Q/QuantumTomography.jl) - Julia package to perform quantum state and process tomography.

**Python**
- [Adapt](https://github.com/BBN-Q/Adapt) - Algorithms for adaptive refinement of measurements.
- [Arline Quantum](https://github.com/ArlineQ/arline_quantum) - Library with implementation of quantum gates and hardware, a part of [Arline Benchmarks](https://github.com/ArlineQ/arline_benchmarks) project.
- [Boson Sampling](https://github.com/IffTech/Boson-Sampling) - Library to calculate interferometer output probabilities given Fock state inputs to help better understand [Aaronson-Arkhipov Boson Sampling arXiv:1011.3245 [quant-ph]](https://arxiv.org/abs/1011.3245)
- [FermiLib](https://github.com/ProjectQ-Framework/FermiLib) - Software for analyzing fermionic quantum simulation algorithms with [ProjectQ](https://github.com/ProjectQ-Framework/ProjectQ).
- [Grove](https://github.com/rigetticomputing/grove) - Quantum algorithms implemented using [Rigetti](https://www.rigetti.com/)'s [pyQuil](https://github.com/rigetticomputing/pyquil).
- [G/SG Morph](https://github.com/IffTech/GSG-Morph) - Quantum annealing algorithms for Graph/Subgraph Isomorphism based on [Calude et al.'s paper "QUBO formulations for the graph isomorphism problem and related problems" 10.1016/j.tcs.2017.04.016](https://doi.org/10.1016/j.tcs.2017.04.016)
- [MQT QAO](https://github.com/cda-tum/mqt-qao) - Automatic Framework for Solving Optimization Problems with Quantum Computers available via the [`mqt.qao`](https://pypi.org/p/mqt.qao) Python package.
- [MQT QUBOMaker](https://github.com/cda-tum/mqt-qubomaker) - Automated QUBO formulation for optimization and pathfinding problems offering multiple encodings. Available via the [`mqt.qubomaker`](https://pypi.org/p/mqt.qubomaker) Python package.
- [OpenFermion](https://github.com/quantumlib/OpenFermion) - Compiling and analyzing quantum algorithm for quantum chemistry simulations.
- [OpenQAOA](https://github.com/entropicalabs/openqaoa) - Multi-backend SDK to create, customise and execute QAOA on NISQ devices and simulators.
- [Paddle Quantum](https://github.com/PaddlePaddle/Quantum) - Quantum machine learning platform to construct & train quantum neural networks, developed by Baidu.
- [PyZFS](https://github.com/hema-ted/pyzfs) - Package to compute zero-field-splitting tensors for molecules and spin quantum bits in semiconductors.
- [QFog](https://github.com/artiste-qb-net/quantum-fog) - Framework for analyzing both classical and quantum Bayesian Networks.
- [QGrad](https://github.com/qgrad/qgrad) - Library to integrate automatic differentiation tools such as JAX with QuTiP and related quantum software packages.
- [Qiskit Nature](https://github.com/Qiskit/qiskit-nature) - Quantum Chemistry including ground state, excited states and dipole moment calculations.
- [QPanda](https://github.com/OriginQ/QPanda-2) - QPanda is a quantum computing framework that can be used to build, run, and optimize quantum algorithms.
- [Qualtran](https://qualtran.readthedocs.io/en/latest/) - A library for expressing and analyzing Fault Tolerant Quantum algorithms.
- [Quantum_Edward](https://github.com/artiste-qb-net/Quantum_Edward) - Python tools for supervised learning by Quantum Neural Networks
- [QuantumFlow](https://github.com/rigetti/quantumflow) - Quantum Algorithms Development Toolkit e.g. allowing for backpropagation with QAOA.
- [Quantum TSP](https://github.com/mstechly/quantum_tsp_tutorials) - Tutorials on solving Travelling Salesman Problem using quantum computing (QAOA).
- [Qudit Team](https://github.com/q-inho/QuditsTeam-1) - Repository to extend Qiskit versatility to higher dimensional quantum states.
- [spin_qudit_tomography](https://github.com/perlinm/spin_qudit_tomography) - Code used in spin tomography using qudits.
- [Tensorflow Quantum](https://www.tensorflow.org/quantum) - Library for hybrid quantum-classical machine learning.
- [pyRiemann-qiskit](https://github.com/pyRiemann/pyRiemann-qiskit) - Library for machine learning and quantum programming based on pyRiemann and Qiskit projects.
- [VQF](https://github.com/mstechly/vqf) - Implementation of Variational Quantum Factoring algorithm (in pyQuil)
- [WebMark](https://github.com/ohtu2021-kvantti/WebMark) - Web platform for benchmarking quantum computing algorithms.
- [XACC Examples](https://github.com/ORNL-QCI/xacc-examples) - Example code using [XACC](https://github.com/ORNL-QCI/xacc) for quantum computing.
- [XACC QChem](https://github.com/ORNL-QCI/xacc-qchem-benchmarks) - QPU Benchmarks for Quantum Chemistry via [XACC](https://github.com/ORNL-QCI/xacc), [Psi4](http://www.psicode.org/) and [OpenFermion](https://github.com/quantumlib/OpenFermion).

**Q#**
- [Quantum Katas](https://github.com/Microsoft/QuantumKatas) -  Programming exercises for learning Q# and quantum computing.

## Quantum compilers

**C++**
- [Catalyst](https://github.com/PennyLaneAI/catalyst) - AOT/JIT compiler for hybrid quantum computing beyond NISQ. Written in MLIR. Python frontend via [PennyLane](https://pennylane.ai).
- [MQT QMAP](https://github.com/cda-tum/mqt-qmap) - Quantum circuit mapping. Clifford synthesis. Compilation for neutral atom architectures. Compatible with Qiskit through the [`mqt.qmap`](https://pypi.org/p/mqt.qmap) Python package.
- [MQT SyReC](https://github.com/cda-tum/mqt-syrec) - HDL-based synthesis of reversible circuits for optimized circuit designs.
- [QCOR](https://github.com/ORNL-QCI/qcor) - C++ language extension and associated compiler implementation for hybrid quantum-classical programming.
- [ScaffCC](https://github.com/epiqc/ScaffCC) - Compilation, analysis and optimization framework for the Scaffold quantum programming language.
- [TKET](https://github.com/CQCL/tket) - C++ library for placement, routing, and optimization of quantum circuits (developed by Quantinuum).
- [tweedledum](https://github.com/boschmitt/tweedledum) - C++17 library for analysis, compilation/synthesis, and optimization of quantum circuits.

**Mathematica**
- [UniversalQCompiler](https://github.com/Q-Compiler/UniversalQCompiler) - Synthesis of isometries (including unitaries and state preparation), channels and POVMs.

**Julia**
- [QuantumCircuitOpt.jl](https://github.com/harshangrjn/QuantumCircuitOpt.jl) - Julia package for provably optimal decompositions and compilations of quantum circuits

**Python**
- [Arline Benchmarks](https://github.com/ArlineQ/arline_benchmarks) - Automated benchmarking platform for quantum compilers, quantum hardware and quantum algorithms.
- [BQSKit](https://github.com/BQSKit) - Berkeley Quantum Synthesis Toolkit is an optimizing quantum compiler and related tool-set.
- [Mitiq](https://github.com/unitaryfund/mitiq) - Cross-platform, error-mitigating quantum compiler from [Unitary Fund](https://unitary.fund/).
- [MQT IonShuttler](https://github.com/cda-tum/mqt-ion-shuttler) - Exact and heuristic scheduling to manage ion movement within trapped-ion hardware.
- [MQT Predictor](https://github.com/cda-tum/mqt-predictor) - RL-based compiler optimization. ML-based device selection. Available via the [`mqt.predictor`](https://pypi.org/p/mqt.predictor) Python package.
- [NchooseK](https://github.com/lanl/NchooseK) - Constraint-programming system that compiles to both circuit-model quantum computers and quantum annealers.
- [PyZX](https://github.com/Quantomatic/pyzx) - Python library for quantum circuit rewriting and optimisation using the ZX-calculus.
- [QEDA](https://github.com/Spooky-Manufacturing/QEDA) - Quantum electronic design automation software for optical circuits using QASM.
- [QGL2 Compiler](https://github.com/BBN-Q/pyqgl2) - Language compiler for imperative Quantum Gate Language ([QGL](https://github.com/BBN-Q/QGL)).
- [Qiskit Terra](https://github.com/Qiskit/qiskit-terra) - Python library for quantum circuit rewriting and optimization (supported by IBM).
- [Qiskit ZX transpiler](https://github.com/dlyongemallo/qiskit-zx-transpiler) - Transpiler pass for Qiskit which uses ZX-calculus for circuit optimization.
- [Qlasskit](https://github.com/dakk/qlasskit) - Compiler from Python language to quantum circuits and binary quadratic models.
- [Qubiter](https://github.com/artiste-qb-net/qubiter) - Quantum compiler with Python wrapper for [LAPACK's CS Decomposition](http://www.netlib.org/lapack/README-CSD.html) to build a binary tree of matrices.
- [SAT Circuits Engine](https://github.com/ohadlev77/sat-circuits-engine) - Qiskit-based high-level quantum circuits synthesis engine for n-SAT problems.

**Rust**
- [TKET2](https://github.com/CQCL/tket2) - Rewrite based toolkit for optimization of quantum programs (version 2 of the [TKET](https://github.com/CQCL/tket) quantum compiler).

**Common Lisp**
- [quilc](https://github.com/rigetti/quilc) - Rigetti's optimizing Quil compiler.

## Quantum converters
**Javascript**
- [qconvert-js](http://github.com/quantastica/qconvert-js) - Quantastica's quantum programming language converter in Javascript.

**Python**
- [qconvert](http://github.com/quantastica/qconvert) - Quantastica's quantum programming language converter in Python.

## Quantum assembly

- [Blackbird](https://github.com/XanaduAI/blackbird) - Open-source quantum instruction language currently used for Xanadu's photonic hardware.
- [OpenQASM](https://github.com/QISKit/openqasm) - Open-source quantum assembly language.
- [QMASM](https://github.com/lanl/qmasm) - Quantum macro assembler for D-Wave's quantum annealers.
- [Quil](https://arxiv.org/abs/1608.03355) - Open hybrid quantum/classical instruction set currently used by Rigetti. [Parser](https://github.com/rigetticomputing/pyquil/tree/master/pyquil/_parser)

## Quantum control

**Python**
- [C3](https://github.com/q-optimize/c3) - Open-loop, closed-loop and automated Control, Calibration and Characterization of quantum devices.
- [Krotov](https://github.com/qucontrol/krotov) - Python implementation of Krotov's method for quantum optimal control.
- [Qibo](https://github.com/qiboteam/qibo) - Qibo provides a platform agnostic quantum hardware control module with drivers for multiple instruments.
- [Quanlse](https://github.com/baidu/Quanlse) - Quanlse provides quantum control solutions via a cloud SDK, developed by [Baidu Quantum](https://research.baidu.com/Research_Areas/index-view?id=75).

## Quantum interoperability

- [Digital Soul](https://github.com/NeuralDreamResearch/DigitalSoul) - Unified platform for CPU, GPU, FPGA, and Quantum Computing.
- [scikit-quant](https://github.com/scikit-quant/scikit-quant) - This is a package to improve interoperability between different quantum computer software packages.

## Quantum error correction

**Julia**
- [CodingTheory](https://github.com/esabo/CodingTheory) - Julia package for constructing and analyzing classical and quantum error-correcting codes.

**Python**
- [MQT QECC](https://github.com/cda-tum/mqt-qecc) - Synthesis of fault-tolerant circuits. Decoders. Automatic Application of error correcting codes. Available via the [`mqt.qecc`](https://pypi.org/p/mqt.qecc) Python package.
- [PyMatching](https://github.com/oscarhiggott/PyMatching) - Python package for decoding quantum error correcting codes with minimum-weight perfect matching.
- [qecsim](https://github.com/qecsim/qecsim) - Python package for simulating quantum error correction using stabilizer codes.
- [Qiskit Experiments](https://github.com/Qiskit-Extensions/qiskit-experiments) - Python package for quantum error correction experiments (supported by IBM).
- [Qsurface](https://github.com/watermarkhu/qsurface) - Python package for simulation and visualization of quantum error-correction on surface codes.

## Quantum and post-quantum cryptography

**C**
- [liboqs](https://github.com/open-quantum-safe/liboqs) - C library for quantum-resistant cryptographic algorithms.
- [openssh](https://github.com/open-quantum-safe/openssh-portable) - OpenSSH with quantum-safe key exchange algorithms.
- [openssl](https://github.com/open-quantum-safe/openssl) - OpenSSL with quantum-safe cryptographic algorithms.
- [PQClean](https://github.com/PQClean/PQClean) - Clean, portable, tested implementations of post-quantum cryptography.
- [TQ42 Cryptography](https://github.com/terra-quantum-public/tq42-pqc-oss) - Post-quantum algorithms, hash functions, digital signature, key encapsulation mechanism, PRNG, and key management functions.

**Python**
- [Crypto-Vinaigrette](https://github.com/aditisrinivas97/Crypto-Vinaigrette) - Quantum-resistant asymmetric key generation tool for digital signatures.
- [Qash-QKDC](https://github.com/TimeMelt/qash-qkdc) - [Hashing algorithms/circuits](https://timemelt.itch.io/qash-qkdc) powered by quantum operations.
- [Qashchain](https://github.com/TimeMelt/qashchain) - [Quantum blockchain](https://timemelt.itch.io/qashchain) based on [qash-qkdc](https://github.com/TimeMelt/qash-qkdc) circuits.
- [QRL](https://github.com/theQRL/QRL/) - [Quantum Resistant Ledger](https://theqrl.org/) utilizing hash-based one-time merkle tree signature scheme instead of ECDSA.

## Experimental quantum computing

**Julia**
- [Qlab.jl](https://github.com/BBN-Q/Qlab.jl) - Generic lab tools in Julia.

**Matlab**
- [Qlab](https://github.com/BBN-Q/Qlab) - Measurement and control software for superconducting qubits.

**Python**
- [ARTIQ](https://github.com/m-labs/artiq) - Next-generation control system for quantum information experiments.
- [OLSQ](https://github.com/tbcdebug/OLSQ) - OpenQASM package to perform optimal layout synthesis for quantum computing.
- [MQT DASQA](https://github.com/cda-tum/mqt-dasqa) - Framework to encapsulate application-driven superconducting architecture design.
- [MQT Qudits](https://github.com/cda-tum/mqt-qudits) - A framework for research and education for mixed-dimensional qudit quantum computing available via the [`mqt.qudits`] Python package.
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
- [QEDA](https://github.com/Spooky-Manufacturing/QEDA) - Quantum Electronics Design Automation - The RTL of Quantum Computing!

## Quantum fun

**Board games**
- [Entanglion](https://github.com/Entanglion/entanglion) - The world’s first open source quantum computing board game. For 2 players.
- [Unitary](https://github.com/quantumlib/unitary) - API library providing common operations for adding quantum behaviors to games.

**F#**
- [Quantum Puzzle Generator](https://github.com/mrdimosthenis/QuantumPuzzleGenerator) - Educational puzzle game for Android and iOS.

**Python**
- [bloqit](https://github.com/kelzheng/bloqit) - Tiny qubit duel for your smart phone.
- [QiskitBlocks](https://content.luanti.org/packages/javafxpert/qiskitblocks/) - Game that teaches quantum computing using Qiskit in a Minetest block world.
- [Quantum Awesomeness](https://github.com/decodoku/A_Game_to_Benchmark_Quantum_Computers) - [Simple puzzles to benchmark various quantum processor](https://medium.com/@decodoku/understanding-quantum-computers-through-a-simple-puzzle-game-a290dde89fb2).
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

**C++**
- [MQT DDVis](https://github.com/cda-tum/mqt-ddvis) - Installation-free web-tool that visualizes quantum decision diagrams for classical simulation and verification. Hosted at https://www.cda.cit.tum.de/app/ddvis/.
- [MQT Debugger](https://github.com/cda-tum/mqt-debugger) - Debugging quantum circuits with IDE integration based on DAP server.
- [MQT QCEC](https://github.com/cda-tum/mqt-qcec) - Equivalence checking of quantum circuits. Verifying compilation flows. Available via the [`mqt.qcec`](https://pypi.org/p/mqt.qcec) package and fully compatible with Qiskit.
- [MQT QuSAT](https://github.com/cda-tum/mqt-qusat) - Encoding and equivalence checking of Clifford circuits using satisfiablity testing (SAT).

**Mathematica**
- [Quantum](http://homepage.cem.itesm.mx/lgomez/quantum/) - Free Mathematica add-on for Dirac Bra-Ket Notation, Quantum Algebra, Quantum Computing and the QHD approximation to the Heisenberg Equations of Motion.
- [QI](https://github.com/rogercolbeck/QI) - Toolkit for common quantum information functions.


**Python**
- [Arline Quantum](https://github.com/ArlineQ/arline_quantum) - Arline Quantum is an open-source library providing basic functionality for creating and manipulating quantum circuits. It also contains a list of mock quantum hardware.
- [Covalent](https://github.com/AgnostiqHQ/covalent) - Tool for running high performance/quantum workflows on advanced computing hardwares.
- [Gridsynth-Python-wrapper](https://github.com/InfamousPlatypus/Gridsynth-Python-wrapper) - Wrapper for using Gridsynth in Python/
- [IBM Q bot](https://github.com/RQC-QApp/QuantumComputingBot) - Bot for Slack and Telegram to monitor the load of IBM Q quantum computers.
- [MQT Bench](https://github.com/cda-tum/mqt-bench) - Quantum circuit benchmark suite providing benchmark algorithms for different compilation levels. Web application hosted at https://www.cda.cit.tum.de/mqtbench/. Also available via the [`mqt.bench`](https://pypi.org/p/mqt.bench) Python package.
- [MQT Problem Solver](https://github.com/cda-tum/mqt-problemsolver) - Automated Framework for Realizing Quantum Computing Solutions.
- [orqviz](https://github.com/zapatacomputing/orqviz) - Library to easily visualize the loss landscape of variational quantum algorithms.
- [pulsemaker](https://github.com/adgt/pulsemaker) - Python widget library for designing pulses and pulse schedules for quantum computing hardware.
- [pymablock](https://gitlab.kwant-project.org/qt/pymablock) - Package for the construction of effective Hamiltonians using quasi-degenerate perturbation theory.
- [pyQuirk](https://github.com/adgt/pyQuirk) - Python widget for Quirk to be used in Jupyter notebooks, JupyterLab, and the IPython kernel.
- [qBraid](https://docs.qbraid.com/home/introduction) - Transpiles quantum circuits to and from Cirq, Qiskit, Amazon Braket, Pennylane, Pyquil and allows for execution on any backend.
- [qonduit](https://github.com/adgt/qonduit) - Python library with visualization tools and workflows for quantum computing that utilize the best of what’s available.
- [qprof](https://gitlab.com/qcomputing/qprof/qprof) - `gprof`-compatible profiler for quantum programs.
- [QRAND](https://github.com/pedrorrivero/qrand) - Multiplatform and multiprotocol quantum random number generator for arbitrary probability distributions.
- [QuantumGraphs](https://github.com/ziofil/QuantumGraphs) - Grow and study random graphs by a continuous, randomly collapsing quantum walk.
- [toqito](https://github.com/vprusso/toqito) - Framework to study problems pertaining to entanglement theory, nonlocal games, and other aspects of quantum information.
- [ZXLive](https://github.com/Quantomatic/zxlive) - GUI editor for ZX diagrams.

**TypeScript**
- [SpookyIDE](http://github.com/Spooky-Manufacturing/SpookyIDE) - IDE designed for quantum computing.

**Others**
- [Quil syntax highlighter](https://github.com/JavaFXpert/quil-syntax-highlighter) - Syntax highlighter for PyCharm.

## Quantum data

- [QDataSet](https://github.com/eperrier/QDataSet) - Quantum datasets for the training and development of QML algorithms.

## Abandoned projects
*2+ years of inactivity. Feel free to reanimate, document and contribute to some of this work!*
- [BLACK-STONE](https://github.com/thephoeron/black-stone) - Specification and implementation of quantum common lisp, for gate-model quantum computers.
- [goqu](https://github.com/cco3/goqu) - Quantum computing simulation library for GoLang.
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
- [Qiskit Aqua](https://github.com/Qiskit/qiskit-aqua) - Library of various quantum algorithm implemented with [Qiskit](https://github.com/Qiskit/qiskit).
- [qiskit-ignis](https://github.com/qiskit/qiskit-ignis) - Tools for quantum hardware verification, noise characterization, and error correction.
- [Qiskit Tutorial](https://github.com/QISKit/qiskit-tutorial) - Jupyter notebook filled with tutorials for [Qiskit](https://github.com/QISKit/qiskit).
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
- [8Q](https://github.com/Spooky-Manufacturing/8Q) - 8 Qbit, Photonic Quantum Computer.

## Contributing
See the [contribution guidelines](CONTRIBUTING.md/#readme).

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the Quantum Open Source Foundation has waived all copyright and related or neighboring rights to this work.
