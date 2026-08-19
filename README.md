<p align="center"><img src="hopf_fibration.png" alt="bDialog" height="300px"></p>

# Awesome Open-Source Quantum Software Projects with stars

[![Twitter Follow](https://img.shields.io/twitter/follow/qosfoundation?style=social)](https://twitter.com/qosfoundation)

Curated list of open-source developed quantum software projects.

*Please read the [contribution guidelines](CONTRIBUTING.md#readme) before contributing.*

Also please check out the [Unitary Fund](http://unitary.fund/)'s 4k$ grant project for quantum OSS!

Clone this repository into your qBraid account:

[<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com?gitHubUrl=https://github.com/qosf/awesome-quantum-software.git)

## Contents

* [Quantum full-stack libraries](#quantum-full-stack-libraries)
* [Quantum simulators](#quantum-simulators)
* [Quantum analog Hamiltonian](#quantum-analog-hamiltonian)
* [Quantum annealing](#quantum-annealing)
* [Quantum algorithms](#quantum-algorithms)
* [Quantum compilers](#quantum-compilers)
* [Quantum converters](#quantum-converters)
* [Quantum assembly](#quantum-assembly)
* [Quantum control](#quantum-control)
* [Quantum interoperability](#quantum-interoperability)
* [Quantum error correction](#quantum-error-correction)
* [Quantum and post-quantum cryptography](#quantum-and-post-quantum-cryptography)
* [Experimental quantum computing](#experimental-quantum-computing)
* [Quantum fun](#quantum-fun)
* [Quantum tools](#quantum-tools)
* [Quantum data](#quantum-data)
* [Abandoned projects](#abandoned-projects)
* [Contributing](#contributing)
* [License](#license)

For a curated list of learning resources please check out [desireevl's repo](https://github.com/desireevl/awesome-quantum-computing) ⭐ 3,256 | 🐛 27 | 📅 2024-07-24.

## Quantum full-stack libraries

**C**

* [Qiskit](https://www.ibm.com/quantum/qiskit) - SDK for working with quantum computers at the level of extended quantum circuits, operators, and primitives. (supported by IBM).

**C++**

* [CUDA-Q](https://github.com/NVIDIA/cuda-quantum) ⭐ 1,116 | 🐛 535 | 🌐 C++ | 📅 2026-08-19 - Platform for accelerated quantum-classical applications on GPUs, CPUs and QPUs.
* [qpp](https://github.com/softwareQinc/qpp) ⭐ 673 | 🐛 2 | 🌐 C++ | 📅 2026-07-20 - Quantum++ is a modern C++ general purpose quantum computing library, composed solely of template header files.
* [staq](https://github.com/softwareqinc/staq) ⭐ 184 | 🐛 6 | 🌐 OpenQASM | 📅 2026-02-22 - Full stack quantum processing toolkit ([arXiv paper](https://arxiv.org/abs/1912.06070)).
* [avaloni](https://github.com/avalon-lang/avaloni) ⭐ 22 | 🐛 0 | 🌐 C++ | 📅 2018-12-16 - Programming language (interpreter) for classical-quantum hybrid computers.
* [Qristal](https://github.com/qbrilliance/qristal) ⭐ 13 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2025-10-20 - Quantum Brilliance's hybrid quantum-classical C++/Python development platform ([docs](https://qristal.readthedocs.io); [core module](https://github.com/qbrilliance/qristal-core) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2025-10-20).
* [XACC](https://github.com/ORNL-QCI/xacc) ⭐ 3 | 🐛 6 | 🌐 C++ | 📅 2025-01-17 - Extreme-scale programming model for quantum acceleration within high-performance computing ([arXiv paper](https://arxiv.org/abs/1710.01794)).

**OCaml**

* [QCaml](https://opam.ocaml.org/packages/qcaml/) - Lightweight OCaml library to experiment with quantum states, gates and measurements.

**Python**

* [Cirq](https://github.com/quantumlib/Cirq) ⭐ 5,052 | 🐛 119 | 🌐 Python | 📅 2026-08-19 - Framework for creating, editing, and invoking Noisy Intermediate Scale Quantum (NISQ) circuits.
* [Forest](https://github.com/rigetticomputing/pyquil) ⭐ 1,497 | 🐛 242 | 🌐 Python | 📅 2026-08-19 - [Rigetti](https://www.rigetti.com/)'s software library for writing, simulating, compiling and executing quantum programs.
* [CUDA-Q](https://github.com/NVIDIA/cuda-quantum) ⭐ 1,116 | 🐛 535 | 🌐 C++ | 📅 2026-08-19 - Platform for accelerated quantum-classical applications on GPUs, CPUs and QPUs.
* [ProjectQ](https://github.com/ProjectQ-Framework/ProjectQ) ⭐ 976 | 🐛 41 | 🌐 Python | 📅 2026-08-17 - Hardware-agnostic framework with compiler and simulator with emulation capabilities.
* [Strawberry Fields](https://github.com/xanaduai/strawberryfields) ⚠️ Archived - [Xanadu](https://www.xanadu.ai)'s software library for photonic quantum computing.
* [Ocean](https://github.com/dwavesystems/dwave-ocean-sdk) ⭐ 537 | 🐛 26 | 🌐 Python | 📅 2026-08-10 - [D-Wave System](https://www.dwavesys.com/home)'s suite of tools for solving hard problems with quantum computers.
* [Tequila](https://github.com/aspuru-guzik-group/tequila) ⭐ 437 | 🐛 5 | 🌐 Python | 📅 2026-08-13 - Extensible Quantum Information and Learning Architecture developed by Alan Aspuru-Guzik's group (UofT).
* [blueqat](https://github.com/Blueqat/Blueqat) ⭐ 387 | 🐛 0 | 🌐 Python | 📅 2026-08-02 - Quantum computing SDK.
* [Braket](https://github.com/amazon-braket/amazon-braket-sdk-python) ⭐ 373 | 🐛 34 | 🌐 Python | 📅 2026-08-19 - [Amazon's](https://aws.amazon.com/braket/) fully managed quantum computing service for building quantum algorithms.
* [Qibo](https://github.com/qiboteam/qibo) ⭐ 360 | 🐛 104 | 🌐 Python | 📅 2026-08-18 - An open-source framework for quantum simulation, self-hosted quantum hardware control and calibration.
* [TensorCircuit](https://github.com/tencent-quantum-lab/tensorcircuit) ⭐ 358 | 🐛 23 | 🌐 Python | 📅 2025-10-22 - Tensor network based quantum software framework for the NISQ era.
* [Qrisp](https://qrisp.eu/) - A high-level programming language and framework for creating and compiling quantum algorithms ([GitHub](https://github.com/eclipse-qrisp/Qrisp) ⭐ 289 | 🐛 186 | 🌐 Python | 📅 2026-08-19).
* [Perceval](https://github.com/Quandela/Perceval) ⭐ 206 | 🐛 13 | 🌐 Python | 📅 2026-07-31 - [Quandela](https://www.quandela.com)'s software library for programming realistic photonic quantum computers.
* [Tangelo](https://github.com/goodchemistryco/Tangelo) ⚠️ Archived and [Tangelo-Examples](https://github.com/goodchemistryco/Tangelo-Examples/) ⚠️ Archived - Toolkit for quantum chemistry simulation workflows on quantum computers, maintained by [SandboxAQ](https://www.sandboxaq.com/).
* [OpenQL](https://github.com/QE-Lab/OpenQL) ⭐ 109 | 🐛 51 | 🌐 C++ | 📅 2024-09-03 - Compiler framework with algorithm libraries, optimizer, scheduler, QEC, mapping, micro-code generator.
* [quantum-os](https://github.com/quantumos-org/quantum-os) ⭐ 96 | 🐛 0 | 🌐 C | 📅 2022-02-05 - Operating system based on Linux kernel for quantum computing.
* [Qadence](https://github.com/pasqal-io/qadence) ⭐ 89 | 🐛 21 | 🌐 Python | 📅 2025-12-08 - [Pasqal](https://www.pasqal.com)'s package for building differentiable digital and digital-analog quantum programs realizable on neutral atom devices.
* [bosonic-qiskit](https://github.com/C2QA/bosonic-qiskit) ⭐ 75 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2026-07-15 - Simulate hybrid boson-qubit systems within Qiskit, implemented as a part of the Co-design Center for Quantum Advantage (C2QA) of the National Quantum Initiative.
* [quantumcat](https://github.com/artificial-brain/quantumcat/) ⭐ 27 | 🐛 4 | 🌐 Python | 📅 2024-01-03 - Cross-platform open-source high-level quantum computing library focused on building applications.
* [Qristal](https://github.com/qbrilliance/qristal) ⭐ 13 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2025-10-20 - Quantum Brilliance's hybrid quantum-classical C++/Python development platform ([docs](https://qristal.readthedocs.io); [core module](https://github.com/qbrilliance/qristal-core) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2025-10-20).
* [hybridlane](https://github.com/pnnl/hybridlane) ⭐ 4 | 🐛 10 | 🌐 Python | 📅 2026-08-19 - Full-stack library for mixed-variable (CV-DV) quantum programming across simulators and hardware within PennyLane.
* [PyQudit](https://github.com/Ordoptimus/pyqudit) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2021-07-13 - Python package for generalized and universal versions of quantum gates in N-dimensions.
* [Ket](https://quantumket.org) - Embedded programming language that introduces the ease of Python to quantum programming.
* [PennyLane](https://pennylane.ai) - Cross-platform Python library for differentiable programming of quantum computers.
* [pytket](https://docs.quantinuum.com/tket/) - Quantum computing toolkit for building, compiling, and executing quantum circuits (developed by Quantinuum).
* [Qiskit](https://www.ibm.com/quantum/qiskit) - SDK for working with quantum computers at the level of extended quantum circuits, operators, and primitives. (supported by IBM).

**Q#**

* [Q#](https://www.microsoft.com/en-us/quantum/development-kit) - Microsoft's quantum programming language with Visual Studio integration.

**Rust**

* [LIFT](https://github.com/rustnew/Lift) ⭐ 7 | 🐛 4 | 🌐 Rust | 📅 2026-08-05 - Unified compiler framework for AI and quantum computing: a single SSA intermediate representation for tensor ops, quantum gates, and classical-quantum hybrids, with 13 optimisation passes, O0-O3 pipelines, noise-aware scheduling, cost modelling, and LLVM IR / ONNX / OpenQASM 3.0 backends. Published on [crates.io](https://crates.io/crates/lift-core) ([docs](https://docs.rs/lift-core)).

**Silq**

* [Silq](https://silq.ethz.ch/) - Silq is a high-level quantum programming language with safe uncomputation and intuitive semantics.

## Quantum simulators

**Assembly**

* [Quplexity](https://github.com/MrGilli/Quplexity) ⭐ 36 | 🐛 1 | 🌐 Assembly | 📅 2025-09-23 - Modular toolkit for QC simulators. Quplexity offers essential mathematical functions and logic relative to quantum computer simulation. Quplexity is written in ARM(64) and x86 Assembly, which results in improved performance and "weight" benefits.

**C**

* [QuEST](https://github.com/aniabrown/QuEST) ⭐ 484 | 🐛 56 | 🌐 C++ | 📅 2026-08-17 -  Quantum Exact Simulation Toolkit is a high performance multicore simulator of universal quantum circuits.
* [TNQVM](https://github.com/ornl-qci/tnqvm) ⭐ 46 | 🐛 6 | 🌐 C++ | 📅 2025-03-05 - Tensor Network QPU Simulator for Eclipse [XACC](https://github.com/ORNL-QCI/xacc) ⭐ 3 | 🐛 6 | 🌐 C++ | 📅 2025-01-17.
* [QuaC](https://github.com/0tt3r/QuaC) ⭐ 31 | 🐛 1 | 🌐 C | 📅 2024-07-04 - Parallel time-dependent open quantum systems solver.

**Common Lisp**

* [QVM](https://github.com/rigetti/qvm) ⭐ 455 | 🐛 87 | 🌐 Common Lisp | 📅 2025-10-16 - Rigetti's high-performance quantum virtual machine.

**Coq**

* [QWIRE](https://github.com/jpaykin/QWIRE) ⭐ 111 | 🐛 1 | 🌐 Coq | 📅 2025-05-11 - Quantum circuit language and formal verification tool [described in this paper](https://dl.acm.org/citation.cfm?id=3009894).

**C++**

* [qsim](https://github.com/quantumlib/qsim) ⭐ 689 | 🐛 48 | 🌐 C++ | 📅 2026-08-15 - Open-source, GPU-enabled C++ and Python library for fast state-vector simulation of quantum circuits.
* [Qiskit Aer](https://github.com/Qiskit/qiskit-aer) ⭐ 685 | 🐛 244 | 🌐 C++ | 📅 2026-05-25 - High performance simulator for quantum circuits that includes noise models (supported by IBM).
* [Quantum++](https://github.com/softwareqinc/qpp) ⭐ 673 | 🐛 2 | 🌐 C++ | 📅 2026-07-20 - High-performance general purpose quantum simulator (can simulate d-dimensional qudits) ([paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0208073)).
* [Intel Quantum Simulator](https://github.com/intel/intel-qs) ⭐ 263 | 🐛 16 | 🌐 C++ | 📅 2026-08-13 - Distributed qubit register quantum simulator using OpenMP and MPI.
* [Qrack](https://github.com/vm6502q/qrack) ⭐ 229 | 🐛 11 | 🌐 C++ | 📅 2026-08-12 - Comprehensive qubit and gate implementation for developing universal virtual quantum processors.
* [MQT DDSIM](https://github.com/cda-tum/mqt-ddsim) ⭐ 161 | 🐛 11 | 🌐 C++ | 📅 2026-08-19 - Quantum circuit simulator using decision diagrams as a datastructure. Python interface and Qiskit backend via the [`mqt.ddsim`](https://pypi.org/p/mqt.ddsim) Python package.
* [PennyLane Lightning](https://github.com/PennyLaneAI/pennylane-lightning) ⭐ 144 | 🐛 38 | 🌐 C++ | 📅 2026-08-18 - Fast state-vector simulator written in C++. GPU support. Python interface via [PennyLane](https://pennylane.ai).
* [tweedledum](https://github.com/boschmitt/tweedledum) ⭐ 107 | 🐛 24 | 🌐 C++ | 📅 2026-07-16 - Library for synthesis, compilation, and optimization of quantum circuits.
* [QCSim](https://github.com/aromanro/QCSim) ⭐ 103 | 🐛 6 | 🌐 C++ | 📅 2026-08-19 - Quantum computing simulator with many algorithms as examples and tests ([blog post](https://compphys.go.ro/quantum-computing-simulator/)).
* [Huawei HiQsimulator](https://github.com/Huawei-HiQ/HiQsimulator) ⚠️ Archived - Single-amplitude, Full-amplitude and Error-correction circuit simulation engine.
* [QCEAD](https://github.com/llens/QuantumComputingEvolutionaryAlgorithmDesign) ⭐ 22 | 🐛 2 | 🌐 Python | 📅 2026-05-19 - C++ program to both simulate a quantum computer and use parallel evolutionary techniques to design algorithms.
* [QPlayer](https://github.com/eQuantumOS/QPlayer) ⭐ 12 | 🐛 0 | 🌐 C++ | 📅 2025-09-15 - Light-weight, scalable and fast quantum Schrödinger simulator ([paper](https://onlinelibrary.wiley.com/doi/full/10.4218/etrij.2021-0442)).
* [qSim](https://github.com/haykkh/qSim) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2022-08-15 - High level, elementary simulation library.
* [qFlex](https://github.com/ngnrsaa/qflex) ⭐ 0 | 🐛 0 | 📅 2026-01-19 - Flexible high-performance simulator for verifying and benchmarking quantum circuits implemented on real hardware.

**F#**

* [Liqui|>](http://stationq.github.io/Liquid/) - Toolsuite for quantum simulation developed by [Microsoft QuArC](https://www.microsoft.com/en-us/research/group/quantum-architectures-and-computation-group-quarc/).

**GoLang**

* [Q](https://github.com/itsubaki/q) ⭐ 281 | 🐛 0 | 🌐 Go | 📅 2026-08-19 - Quantum Computation Simulator written purely in GoLang.

**Java**

* [Strange](https://github.com/redfx-quantum/strange) ⭐ 242 | 🐛 15 | 🌐 Java | 📅 2026-05-31 - Java API that can be used to create Quantum Programs.

**JavaScript**

* [Quirk](https://github.com/Strilanc/Quirk) ⭐ 1,097 | 🐛 54 | 🌐 JavaScript | 📅 2024-07-16 - Drag-and-drop quantum circuit simulator in your browser.
* [Quantum Circuit Simulator](https://github.com/perak/quantum-circuit) ⭐ 274 | 🐛 13 | 🌐 JavaScript | 📅 2026-08-15 - Smoothly runs 20+ qubit simulations in browser or on node.js server.
* [Quantum-computing-playground](https://github.com/gwroblew/Quantum-Computing-Playground) ⭐ 113 | 🐛 3 | 🌐 JavaScript | 📅 2016-08-12 - Browser-based simple IDE interface to run, visualize and debug quantum programs.
* [Quantum tensors](https://github.com/Quantum-Game/quantum-tensors) ⭐ 59 | 🐛 3 | 🌐 TypeScript | 📅 2023-01-07 - JavaScript / TypeScript package for sparse tensor operations on complex numbers for quantum computing.
* [jsquil](https://github.com/mapmeld/jsquil) ⭐ 51 | 🐛 0 | 🌐 JavaScript | 📅 2020-06-24 - JavaScript interface for writing [Quil](https://en.wikipedia.org/wiki/Quil_\(instruction_set_architecture\)) programs.
* [Quantum JavaScript (Q.js)](https://quantumjavascript.app/) - Drag-and-drop circuit editor, simulator, documented API, text-as-circuit DSL, concept primers.

**Julia**

* [Yao.jl](https://github.com/QuantumBFS/Yao.jl) ⭐ 1,040 | 🐛 40 | 🌐 Julia | 📅 2026-08-10 - Extensible, Efficient Quantum Algorithm Design for Humans.
* [QuantumToolbox.jl](https://github.com/qutip/QuantumToolbox.jl) ⭐ 170 | 🐛 31 | 🌐 Julia | 📅 2026-08-07 - High-performance, GPU-ready and autodiff-friendly simulations of open quantum systems.
* [IonSim.jl](https://github.com/HaeffnerLab/IonSim.jl) ⭐ 80 | 🐛 17 | 🌐 Julia | 📅 2025-11-04 - Simulate the dynamics of a configuration of trapped ions interacting with laser light.
* [PauliStrings.jl](https://github.com/nicolasloizeau/PauliStrings.jl) ⭐ 71 | 🐛 18 | 🌐 Julia | 📅 2026-08-15 - Many-body simulations in the Pauli strings representation.
* [Cliffords.jl](https://github.com/BBN-Q/Cliffords.jl) ⭐ 46 | 🐛 3 | 🌐 Julia | 📅 2021-07-01 - Efficient calculation of Clifford circuits in Julia.
* [KadanoffBaym.jl](https://github.com/NonequilibriumDynamics/KadanoffBaym.jl) ⭐ 31 | 🐛 0 | 🌐 Julia | 📅 2026-06-18 - Adaptive many-body time evolution of non-equilibrium Green functions.
* [BosonSampling.jl](https://github.com/benoitseron/BosonSampling.jl) ⭐ 28 | 🐛 8 | 🌐 Julia | 📅 2026-08-16 - Efficient simulation of multiphoton interference.
* [QSimulator.jl](https://github.com/BBN-Q/QSimulator.jl) ⭐ 28 | 🐛 3 | 🌐 Julia | 📅 2022-05-19 - Unitary and Lindbladian evolution in Julia.
* [QuantumInfo.jl](https://github.com/BBN-Q/QuantumInfo.jl) ⭐ 18 | 🐛 3 | 🌐 Julia | 📅 2022-02-21 - Julia library for quantum information related calculations.
* [SmoQ.jl](https://github.com/MarcinPlodzien/SmoQ.jl) ⭐ 17 | 🐛 2 | 🌐 Julia | 📅 2026-02-09 - Matrix-free simulation of pure and mixed quantum states.
* [RandomQuantum.jl](https://github.com/BBN-Q/RandomQuantum.jl) ⭐ 13 | 🐛 3 | 🌐 Julia | 📅 2022-12-16 - Package for generating random quantum states and processes.
* [QuantumOptics.jl](https://qojulia.org/) - Numerical framework to simulate various kinds of open quantum systems in Julia.

**Python**

* [Stim](https://github.com/quantumlib/Stim) ⭐ 809 | 🐛 87 | 🌐 C++ | 📅 2026-08-04 - Fast stabilizer circuit simulator.
* [qsim](https://github.com/quantumlib/qsim) ⭐ 689 | 🐛 48 | 🌐 C++ | 📅 2026-08-15 - Open-source, GPU-enabled C++ and Python library for fast state-vector simulation of quantum circuits.
* [quimb](https://github.com/jcmgray/quimb) ⭐ 658 | 🐛 70 | 🌐 Python | 📅 2026-08-15 - Easy but fast python library for quantum information and many-body calculations, including with tensor networks.
* [Quintuple](https://github.com/corbett/QuantumComputing) ⭐ 628 | 🐛 3 | 🌐 Python | 📅 2022-12-29 - Simulating the 5-qubit processor of the [IBM Quantum Experience](https://quantumexperience.ng.bluemix.net/qx/experience).
* [Qibo](https://github.com/qiboteam/qibo) ⭐ 360 | 🐛 104 | 🌐 Python | 📅 2026-08-18 - Framework for quantum simulation with hardware acceleration using just-in-time compilation.
* [QuNetSim](https://github.com/tqsd/QuNetSim) ⭐ 144 | 🐛 23 | 🌐 Python | 📅 2024-04-02 - Quantum network simulation framework.
* [SimulaQron](https://github.com/StephanieWehner/SimulaQron) ⭐ 133 | 🐛 15 | 🌐 Python | 📅 2026-05-15 - Application level simulator of a quantum network.
* [Tsim](https://github.com/QuEraComputing/tsim) ⭐ 122 | 🐛 8 | 🌐 Python | 📅 2026-08-12 - GPU-accelerated universal quantum circuit sampler via ZX-calculus stabilizer-rank decomposition ([Stim](https://github.com/quantumlib/Stim) ⭐ 809 | 🐛 87 | 🌐 C++ | 📅 2026-08-04-like API, with non-Clifford support).
* [Graphix](https://github.com/TeamGraphix/graphix) ⭐ 114 | 🐛 17 | 🌐 Python | 📅 2026-08-18 - Measurement-Based Quantum Computing (MBQC) compiler, simulator and QPU interface.
* [The Walrus](https://github.com/xanaduAI/thewalrus) ⭐ 109 | 🐛 28 | 🌐 Python | 📅 2026-07-24 - [Xanadu](https://www.xanadu.ai)'s library for simulating Gaussian Boson Sampling.
* [QCompute](https://github.com/baidu/QCompute) ⭐ 102 | 🐛 3 | 🌐 Python | 📅 2023-12-18 - [Baidu](http://research.baidu.com/Research_Areas/index-view?id=75)'s software development kit for designing quantum circuits and simulating on a high-performance simulator.
* [Piquasso](https://github.com/Budapest-Quantum-Computing-Group/piquasso) ⭐ 59 | 🐛 14 | 🌐 Python | 📅 2026-08-01 - A photonic quantum computing simulator library written in Python/C++.
* [QCircuits](https://github.com/grey-area/qcircuits) ⭐ 59 | 🐛 3 | 🌐 Python | 📅 2022-07-08 - User-friendly quantum circuit simulator designed for students and newcomers to quantum computing.
* [Interlin-q](https://github.com/Interlin-q/Interlin-q) ⭐ 47 | 🐛 10 | 🌐 Python | 📅 2021-09-26 - Quantum network simulator imitating distributed quantum systems with interconnect communication between nodes.
* [PyQTorch](https://github.com/pasqal-io/pyqtorch) ⭐ 47 | 🐛 1 | 🌐 Python | 📅 2025-06-20 - PyTorch-based state vector simulator designed for quantum machine learning from [Pasqal](https://www.pasqal.com).
* [QuPy](https://github.com/ken-nakanishi/qupy) ⭐ 45 | 🐛 2 | 🌐 Python | 📅 2019-05-21 - Quantum circuit simulator for both CPU and GPU.
* [QTop](https://github.com/jacobmarks/QTop) ⭐ 39 | 🐛 2 | 🌐 Python | 📅 2020-02-15 - Simulation and visualization of topological quantum computers.
* [QuSpin](https://github.com/weinbe58/QuSpin) ⭐ 30 | 🐛 0 | 🌐 Python | 📅 2022-12-22 - Exact diagonalization and dynamics of arbitrary boson, fermion and spin many-body systems.
* [Horqrux](https://github.com/pasqal-io/horqrux) ⭐ 25 | 🐛 1 | 🌐 Python | 📅 2025-06-28 - Jax-based quantum state vector simulator tailored for quantum machine learning from [Pasqal](https://www.pasqal.com).
* [Quditto](https://github.com/Networks-it-uc3m/Quditto) ⭐ 25 | 🐛 1 | 🌐 Python | 📅 2026-02-19 - QKD Network emulator that automatically deploys distributed, ETSI GS QKD 014–compliant QKD networks.
* [MentPy](https://github.com/BestQuark/mentpy) ⚠️ Archived - Python package for creating and simulating Measurement-based Quantum Computating (MBQC) programs.
* [PIQS](https://github.com/nathanshammah/piqs) ⭐ 21 | 🐛 7 | 🌐 Python | 📅 2024-04-23 - Efficient simulation of open quantum dynamics of identical qubits.
* [QuForge](https://github.com/tiago939/QuForge) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2026-08-07 - Python package for qudit simulation.
* [MISTIQS](https://github.com/USCCACS/MISTIQS) ⭐ 17 | 🐛 1 | 🌐 Python | 📅 2021-06-02 - Generating/compiling/executing quantum circuits for simulating quantum many-body dynamics of systems.
* [quantum-computing](https://github.com/QuantumSystems/quantum-computing) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2026-07-14 - Functionally complete simulator for universal quantum computing in Python
* [SeQuencing](https://github.com/sequencing-dev/sequencing) ⭐ 15 | 🐛 6 | 🌐 Python | 📅 2022-09-09 - Construct and simulate realistic quantum control sequences using QuTiP.
* [Dense-Evolution](https://github.com/tatopenn-cell/Dense-Evolution) ⭐ 10 | 🐛 3 | 🌐 Python | 📅 2026-08-19 - High-performance NISQ statevector simulator with JAX JIT/XLA compilation, optional CuPy GPU acceleration, and built-in zero-noise-extrapolation error mitigation.
* [SOQCS](https://github.com/SOQCSAdmin/SOQCS) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2024-01-02 - Library to define, simulate, and study non-ideal quantum optical circuits (API provided both in Python and C++).
* [scpn-quantum-control](https://github.com/anulum/scpn-quantum-control) ⭐ 3 | 🐛 13 | 🌐 Python | 📅 2026-08-10 - Quantum simulation of coupled Kuramoto-XY oscillators on IBM hardware, with Rust-accelerated Hamiltonian construction, synchronisation witnesses, and Lindblad open-system dynamics.
* [Dynamiqs](https://www.dynamiqs.org/) - High-performance quantum systems simulation with JAX (GPU-accelerated & differentiable).
* [QuTiP](http://qutip.org/) - User-friendly and efficient numerical simulations of a wide variety of open quantum systems.
* [SQUANCH](https://github.com/att-innovate/squanch) - Distributed simulation framework for quantum networks and channels.
* [gdsfactory](https://gdsfactory.github.io/gdsfactory/) and [plugins](https://gdsfactory.github.io/gplugins) - Open Source Python library designed for crafting chips (Photonics, Analog, Quantum, MEMs, and more), 3D printed objects, and PCBs. Plugins for Simulating Analog, RF, and Photonics circuits.

**Rust**

* [QCGPU](https://github.com/QCGPU/qcgpu-rust) ⭐ 449 | 🐛 5 | 🌐 Python | 📅 2023-07-06 - High-performance GPU-accelerated quantum computer simulation outlined in this [arXiv paper](https://arxiv.org/pdf/1805.00988.pdf).
* [RustQIP](https://github.com/Renmusxd/RustQIP) ⭐ 311 | 🐛 26 | 🌐 Rust | 📅 2025-12-23 - Rust Quantum Computing library leveraging graph building to build efficient quantum circuit simulations.
* [Quriust](https://github.com/ScipioneParmigiano/quriust) ⭐ 5 | 🐛 0 | 🌐 Rust | 📅 2024-05-10 - A blazing fast Rust library for simulating quantum circuits. Only for quriust ones.

**Swift**

* [SwiftQuantumComputing](https://github.com/indisoluble/SwiftQuantumComputing) ⭐ 52 | 🐛 0 | 🌐 Swift | 📅 2022-03-20 - Quantum circuit simulator with a bit of genetic programming.

## Quantum Analog Hamiltonian

* [Pulser](https://github.com/pasqal-io/Pulser) ⭐ 239 | 🐛 38 | 🌐 Python | 📅 2026-08-12 - Python library for pulse-level/analog control of neutral atom devices.
* [Bloqade](https://github.com/QuEraComputing/Bloqade.jl) ⭐ 213 | 🐛 85 | 🌐 Julia | 📅 2026-04-08 - Package for the quantum computation and quantum simulation based on the neutral-atom architecture.

## Quantum annealing

**C++**

* [C-to-D-Wave](https://github.com/lanl/c2dwave) ⭐ 12 | 🐛 0 | 🌐 C++ | 📅 2019-05-08 - Compile a very small subset of C to a D-Wave Hamiltonian function

**Go**

* [QA Prolog](https://github.com/lanl/QA-Prolog) ⭐ 40 | 🐛 0 | 🌐 Go | 📅 2022-01-25 - Compile a subset of [Prolog](https://en.wikipedia.org/wiki/Prolog) to a D-Wave Hamiltonian function
* [edif2qmasm](https://github.com/lanl/edif2qmasm/) ⭐ 25 | 🐛 0 | 🌐 Go | 📅 2022-09-23 - Compile [Verilog](https://en.wikipedia.org/wiki/Verilog), [VHDL](https://en.wikipedia.org/wiki/VHDL), and other hardware-description languages to a D-Wave Hamiltonian function

**Julia**

* [QAOA.jl](https://github.com/FZJ-PGI-12/QAOA.jl) ⭐ 17 | 🐛 1 | 🌐 Julia | 📅 2026-03-29 - Simulate quantum annealing and mean-field quantum annealing in Julia.

**Python**

* [QMASM](https://github.com/lanl/qmasm/) ⭐ 342 | 🐛 0 | 🌐 Python | 📅 2021-02-28 - Quantum macro assembler for D-Wave systems
* [dimod](https://github.com/dwavesystems/dimod) ⭐ 142 | 🐛 159 | 🌐 Python | 📅 2026-08-04 - Shared API for Ising and QUBO problems.
* [dwave-system](https://github.com/dwavesystems/dwave-system) ⭐ 98 | 🐛 85 | 🌐 Python | 📅 2026-06-17 - API for easily incorporating D-Wave quantum annealers as samplers in the [Ocean](https://ocean.dwavesys.com/) software stack.
* [dwave\_networkx](https://github.com/dwavesystems/dwave_networkx) ⭐ 95 | 🐛 38 | 🌐 Python | 📅 2026-06-16 - Exploration and analysis of network graphs.
* [dwave\_neal](https://github.com/dwavesystems/dwave-neal) ⭐ 64 | 🐛 5 | 🌐 Python | 📅 2022-11-25 - Implementation of a simulated annealing sampler.
* [dwave-cloud-client](https://github.com/dwavesystems/dwave-cloud-client) ⭐ 63 | 🐛 78 | 🌐 Python | 📅 2026-07-31 - Min. implementation of the REST interface to communicate with D-Wave's Solver API.
* [qubo-nn](https://github.com/instance01/qubo-nn/) ⭐ 55 | 🐛 0 | 🌐 Python | 📅 2021-09-29 - Classifying, auto-encoding and reverse-engineering QUBO matrices. Also includes 20 problem formulations.
* [minorminer](https://github.com/dwavesystems/minorminer) ⭐ 54 | 🐛 31 | 🌐 Python | 📅 2026-08-19 - Heuristic tool for minor graph embedding.
* [qubovert](https://github.com/jtiosue/qubovert) ⭐ 41 | 🐛 3 | 🌐 Python | 📅 2026-04-13 - Formulating and simulated annealing of Ising, QUBO, and higher order problems with constraints.
* [chimera\_embedding](https://github.com/dwavesystems/chimera-embedding) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2019-06-25 - Algorithms to generate native-structured embeddings for Chimera graphs.
* [qqa](https://github.com/Yuma-Ichikawa/QQA4CO) ⭐ 24 | 🐛 6 | 🌐 Python | 📅 2026-08-02 - GPU-parallel Quasi-Quantum Annealing toolkit for QUBO and Ising combinatorial optimisation, with PI-GNN / CPRA neural backends and a Simulated Annealing baseline, all under a single PyTorch API.
* [dwavebinarycsp](https://github.com/dwavesystems/dwavebinarycsp) ⚠️ Archived - Map constraint satisfaction problems with binary variables to binary quadratic models.
* [penaltymodel](https://github.com/dwavesystems/penaltymodel) ⭐ 20 | 🐛 6 | 🌐 Python | 📅 2025-08-26 - Utilities and interfaces for using penalty models.
* [embedding\_utilities](https://github.com/dwavesystems/dwave_embedding_utilities) ⚠️ Archived - Mapping samples between original and embedded graph.
* [micro\_client\_sapi\_dimod](https://github.com/dwavesystems/dwave_micro_client_dimod) ⚠️ Archived - [Dimod](https://github.com/dwavesystems/dimod) ⭐ 142 | 🐛 159 | 🌐 Python | 📅 2026-08-04 wrapper for the D-Wave Micro Client.

**Python, C & Matlab**

* [Qbsolv](https://github.com/dwavesystems/qbsolv) ⚠️ Archived - QUBO solver with [D-Wave](https://www.dwavesys.com) or classical tabu solver backend.

## Quantum algorithms

**C++**

* [XACC VQE](https://github.com/ornl-qci/xacc-vqe) ⭐ 15 | 🐛 13 | 🌐 C++ | 📅 2019-07-09 - Variational quantum eigensolver built on [XACC](https://github.com/ORNL-QCI/xacc) ⭐ 3 | 🐛 6 | 🌐 C++ | 📅 2025-01-17 for distributed, and shared memory systems.

**HTML**

* [myQShor](https://github.com/Michaelvll/myQShor) ⭐ 29 | 🐛 0 | 🌐 HTML | 📅 2019-07-28 - Quantum implementation of Shor's algorithm.

**Julia**

* [QuantumTomography.jl](https://github.com/BBN-Q/QuantumTomography.jl) ⭐ 34 | 🐛 6 | 🌐 Julia | 📅 2026-04-16 - Julia package to perform quantum state and process tomography.
* [QAOA.jl](https://github.com/FZJ-PGI-12/QAOA.jl) ⭐ 17 | 🐛 1 | 🌐 Julia | 📅 2026-03-29 - Implementation the Quantum Approximate Optimization Algorithm (QAOA) in Julia.

**Python**

* [OpenFermion](https://github.com/quantumlib/OpenFermion) ⭐ 1,729 | 🐛 31 | 🌐 Python | 📅 2026-08-18 - Compiling and analyzing quantum algorithm for quantum chemistry simulations.
* [QPanda](https://github.com/OriginQ/QPanda-2) ⭐ 1,206 | 🐛 18 | 🌐 C++ | 📅 2024-11-13 - QPanda is a quantum computing framework that can be used to build, run, and optimize quantum algorithms.
* [Paddle Quantum](https://github.com/PaddlePaddle/Quantum) ⭐ 646 | 🐛 29 | 🌐 Jupyter Notebook | 📅 2023-04-24 - Quantum machine learning platform to construct & train quantum neural networks, developed by Baidu.
* [Qiskit Nature](https://github.com/Qiskit/qiskit-nature) ⭐ 397 | 🐛 58 | 🌐 Python | 📅 2026-08-13 - Quantum Chemistry including ground state, excited states and dipole moment calculations.
* [Grove](https://github.com/rigetticomputing/grove) ⚠️ Archived - Quantum algorithms implemented using [Rigetti](https://www.rigetti.com/)'s [pyQuil](https://github.com/rigetticomputing/pyquil) ⭐ 1,497 | 🐛 242 | 🌐 Python | 📅 2026-08-19.
* [ReCirq](https://github.com/quantumlib/ReCirq) ⭐ 309 | 🐛 19 | 🌐 Python | 📅 2026-07-17 - Modules for running quantum computing applications and experiments through [Cirq](https://github.com/quantumlib/Cirq) ⭐ 5,052 | 🐛 119 | 🌐 Python | 📅 2026-08-19.
* [OpenQAOA](https://github.com/entropicalabs/openqaoa) ⭐ 142 | 🐛 25 | 🌐 Python | 📅 2024-08-29 - Multi-backend SDK to create, customise and execute QAOA on NISQ devices and simulators.
* [Quantum TSP](https://github.com/mstechly/quantum_tsp_tutorials) ⭐ 109 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2023-06-25 - Tutorials on solving Travelling Salesman Problem using quantum computing (QAOA).
* [QuantumFlow](https://github.com/rigetti/quantumflow) ⚠️ Archived - Quantum Algorithms Development Toolkit e.g. allowing for backpropagation with QAOA.
* [FermiLib](https://github.com/ProjectQ-Framework/FermiLib) ⭐ 90 | 🐛 4 | 🌐 Python | 📅 2018-05-04 - Software for analyzing fermionic quantum simulation algorithms with [ProjectQ](https://github.com/ProjectQ-Framework/ProjectQ) ⭐ 976 | 🐛 41 | 🌐 Python | 📅 2026-08-17.
* [QFog](https://github.com/artiste-qb-net/quantum-fog) ⭐ 80 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2023-02-13 - Framework for analyzing both classical and quantum Bayesian Networks.
* [VQF](https://github.com/mstechly/vqf) ⭐ 55 | 🐛 2 | 🌐 Python | 📅 2026-04-13 - Implementation of Variational Quantum Factoring algorithm (in pyQuil)
* [Quantum\_Edward](https://github.com/artiste-qb-net/Quantum_Edward) ⭐ 51 | 🐛 11 | 🌐 Python | 📅 2018-11-07 - Python tools for supervised learning by Quantum Neural Networks
* [QGrad](https://github.com/qgrad/qgrad) ⭐ 44 | 🐛 4 | 🌐 Python | 📅 2022-05-08 - Library to integrate automatic differentiation tools such as JAX with QuTiP and related quantum software packages.
* [pyRiemann-qiskit](https://github.com/pyRiemann/pyRiemann-qiskit) ⭐ 30 | 🐛 14 | 🌐 Python | 📅 2026-08-07 - Library for machine learning and quantum programming based on pyRiemann and Qiskit projects.
* [MQT QAO](https://github.com/cda-tum/mqt-qao) ⚠️ Archived - Automatic Framework for Solving Optimization Problems with Quantum Computers available via the [`mqt.qao`](https://pypi.org/p/mqt.qao) Python package.
* [MQT QUBOMaker](https://github.com/cda-tum/mqt-qubomaker) ⚠️ Archived - Automated QUBO formulation for optimization and pathfinding problems offering multiple encodings. Available via the [`mqt.qubomaker`](https://pypi.org/p/mqt.qubomaker) Python package.
* [Arline Quantum](https://github.com/ArlineQ/arline_quantum) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2024-01-01 - Library with implementation of quantum gates and hardware, a part of [Arline Benchmarks](https://github.com/ArlineQ/arline_benchmarks) ⭐ 32 | 🐛 3 | 🌐 Python | 📅 2022-03-02 project.
* [PyZFS](https://github.com/hema-ted/pyzfs) ⭐ 14 | 🐛 5 | 🌐 Python | 📅 2020-03-30 - Package to compute zero-field-splitting tensors for molecules and spin quantum bits in semiconductors.
* [Adapt](https://github.com/BBN-Q/Adapt) ⭐ 8 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2023-03-08 - Algorithms for adaptive refinement of measurements.
* [Boson Sampling](https://github.com/IffTech/Boson-Sampling) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2021-10-06 - Library to calculate interferometer output probabilities given Fock state inputs to help better understand [Aaronson-Arkhipov Boson Sampling arXiv:1011.3245 \[quant-ph\]](https://arxiv.org/abs/1011.3245)
* [WebMark](https://github.com/ohtu2021-kvantti/WebMark) ⭐ 5 | 🐛 6 | 🌐 Python | 📅 2021-05-13 - Web platform for benchmarking quantum computing algorithms.
* [G/SG Morph](https://github.com/IffTech/GSG-Morph) ⭐ 3 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2021-10-18 - Quantum annealing algorithms for Graph/Subgraph Isomorphism based on [Calude et al.'s paper "QUBO formulations for the graph isomorphism problem and related problems" 10.1016/j.tcs.2017.04.016](https://doi.org/10.1016/j.tcs.2017.04.016)
* [spin\_qudit\_tomography](https://github.com/perlinm/spin_qudit_tomography) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2021-11-11 - Code used in spin tomography using qudits.
* [Qudit Team](https://github.com/q-inho/QuditsTeam-1) ⭐ 0 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-04-01 - Repository to extend Qiskit versatility to higher dimensional quantum states.
* [Qualtran](https://qualtran.readthedocs.io/en/latest/) - A library for expressing and analyzing Fault Tolerant Quantum algorithms.
* [Tensorflow Quantum](https://www.tensorflow.org/quantum) - Library for hybrid quantum-classical machine learning.
* [XACC Examples](https://github.com/ORNL-QCI/xacc-examples) - Example code using [XACC](https://github.com/ORNL-QCI/xacc) ⭐ 3 | 🐛 6 | 🌐 C++ | 📅 2025-01-17 for quantum computing.
* [XACC QChem](https://github.com/ORNL-QCI/xacc-qchem-benchmarks) - QPU Benchmarks for Quantum Chemistry via [XACC](https://github.com/ORNL-QCI/xacc) ⭐ 3 | 🐛 6 | 🌐 C++ | 📅 2025-01-17, [Psi4](http://www.psicode.org/) and [OpenFermion](https://github.com/quantumlib/OpenFermion) ⭐ 1,729 | 🐛 31 | 🌐 Python | 📅 2026-08-18.

**Q#**

* [Quantum Katas](https://github.com/Microsoft/QuantumKatas) ⚠️ Archived -  Programming exercises for learning Q# and quantum computing.

## Quantum compilers

**C++**

* [TKET](https://github.com/CQCL/tket) ⭐ 314 | 🐛 92 | 🌐 C++ | 📅 2026-08-18 - C++ library for placement, routing, and optimization of quantum circuits (developed by Quantinuum).
* [Catalyst](https://github.com/PennyLaneAI/catalyst) ⭐ 232 | 🐛 313 | 🌐 Python | 📅 2026-08-19 - AOT/JIT compiler for hybrid quantum computing beyond NISQ. Written in MLIR. Python frontend via [PennyLane](https://pennylane.ai).
* [ScaffCC](https://github.com/epiqc/ScaffCC) ⭐ 202 | 🐛 8 | 🌐 C++ | 📅 2021-09-28 - Compilation, analysis and optimization framework for the Scaffold quantum programming language.
* [MQT QMAP](https://github.com/cda-tum/mqt-qmap) ⭐ 141 | 🐛 24 | 🌐 C++ | 📅 2026-08-19 - Quantum circuit mapping. Clifford synthesis. Compilation for neutral atom architectures. Compatible with Qiskit through the [`mqt.qmap`](https://pypi.org/p/mqt.qmap) Python package.
* [tweedledum](https://github.com/boschmitt/tweedledum) ⭐ 107 | 🐛 24 | 🌐 C++ | 📅 2026-07-16 - C++17 library for analysis, compilation/synthesis, and optimization of quantum circuits.
* [MQT SyReC](https://github.com/cda-tum/mqt-syrec) ⭐ 38 | 🐛 19 | 🌐 C++ | 📅 2026-08-19 - HDL-based synthesis of reversible circuits for optimized circuit designs.
* [QCOR](https://github.com/ORNL-QCI/qcor) ⭐ 11 | 🐛 0 | 📅 2021-12-20 - C++ language extension and associated compiler implementation for hybrid quantum-classical programming.

**Mathematica**

* [UniversalQCompiler](https://github.com/Q-Compiler/UniversalQCompiler) ⭐ 72 | 🐛 1 | 🌐 Mathematica | 📅 2025-09-25 - Synthesis of isometries (including unitaries and state preparation), channels and POVMs.

**Julia**

* [QuantumCircuitOpt.jl](https://github.com/harshangrjn/QuantumCircuitOpt.jl) ⭐ 60 | 🐛 7 | 🌐 Julia | 📅 2026-07-24 - Julia package for provably optimal decompositions and compilations of quantum circuits

**Python**

* [Qiskit Terra](https://github.com/Qiskit/qiskit-terra) ⭐ 7,721 | 🐛 1,147 | 🌐 Python | 📅 2026-08-19 - Python library for quantum circuit rewriting and optimization (supported by IBM).
* [PyZX](https://github.com/Quantomatic/pyzx) ⭐ 539 | 🐛 26 | 🌐 OpenQASM | 📅 2026-08-16 - Python library for quantum circuit rewriting and optimisation using the ZX-calculus.
* [Mitiq](https://github.com/unitaryfoundation/mitiq) ⭐ 442 | 🐛 96 | 🌐 Python | 📅 2026-08-07 - Cross-platform, quantum error mitigation toolkit and compiler from [Unitary Foundation](https://unitary.foundation/).
* [Qubiter](https://github.com/artiste-qb-net/qubiter) ⭐ 123 | 🐛 41 | 🌐 HTML | 📅 2023-12-25 - Quantum compiler with Python wrapper for [LAPACK's CS Decomposition](http://www.netlib.org/lapack/README-CSD.html) to build a binary tree of matrices.
* [MQT Predictor](https://github.com/cda-tum/mqt-predictor) ⭐ 87 | 🐛 27 | 🌐 Python | 📅 2026-08-19 - RL-based compiler optimization. ML-based device selection. Available via the [`mqt.predictor`](https://pypi.org/p/mqt.predictor) Python package.
* [UCC](https://github.com/unitaryfoundation/ucc/) ⭐ 79 | 🐛 52 | 🌐 Python | 📅 2026-08-17 - Unitary Compiler Collection: frontend-agnostic open-source quantum compiler developed by Unitary Foundation.
* [Qlasskit](https://github.com/dakk/qlasskit) ⭐ 74 | 🐛 11 | 🌐 Python | 📅 2026-01-03 - Compiler from Python language to quantum circuits and binary quadratic models.
* [MQT IonShuttler](https://github.com/cda-tum/mqt-ion-shuttler) ⭐ 36 | 🐛 1 | 🌐 Python | 📅 2026-08-17 - Exact and heuristic scheduling to manage ion movement within trapped-ion hardware.
* [Arline Benchmarks](https://github.com/ArlineQ/arline_benchmarks) ⭐ 32 | 🐛 3 | 🌐 Python | 📅 2022-03-02 - Automated benchmarking platform for quantum compilers, quantum hardware and quantum algorithms.
* [QEDA](https://github.com/Spooky-Manufacturing/QEDA) ⭐ 28 | 🐛 111 | 🌐 Java | 📅 2021-12-19 - Quantum electronic design automation software for optical circuits using QASM.
* [SAT Circuits Engine](https://github.com/ohadlev77/sat-circuits-engine) ⭐ 10 | 🐛 1 | 🌐 HTML | 📅 2023-06-01 - Qiskit-based high-level quantum circuits synthesis engine for n-SAT problems.
* [QGL2 Compiler](https://github.com/BBN-Q/pyqgl2) ⭐ 9 | 🐛 40 | 🌐 Python | 📅 2021-12-26 - Language compiler for imperative Quantum Gate Language ([QGL](https://github.com/BBN-Q/QGL) ⭐ 33 | 🐛 36 | 🌐 Python | 📅 2026-05-21).
* [NchooseK](https://github.com/lanl/NchooseK) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2025-09-01 - Constraint-programming system that compiles to both circuit-model quantum computers and quantum annealers.
* [Qiskit ZX transpiler](https://github.com/dlyongemallo/qiskit-zx-transpiler) ⭐ 7 | 🐛 2 | 🌐 Python | 📅 2026-04-25 - Transpiler pass for Qiskit which uses ZX-calculus for circuit optimization.
* [CleitonForge](https://github.com/cleitonaugusto/CleitonForge) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2026-08-19 - Differential fuzzer for quantum compilers and simulators (Rust + Python), with a shrinker and an exact-operator oracle.
* [EMRG](https://github.com/FedorShind/EMRG) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-07-07 - Quantum error mitigation toolkit with ZNE, PEC, and CDR support.
* [BQSKit](https://github.com/BQSKit) - Berkeley Quantum Synthesis Toolkit is an optimizing quantum compiler and related tool-set.

**Rust**

* [TKET2](https://github.com/CQCL/tket2) ⭐ 59 | 🐛 179 | 🌐 Rust | 📅 2026-08-19 - Rewrite based toolkit for optimization of quantum programs (version 2 of the [TKET](https://github.com/CQCL/tket) ⭐ 314 | 🐛 92 | 🌐 C++ | 📅 2026-08-18 quantum compiler).
* [LIFT](https://github.com/rustnew/Lift) ⭐ 7 | 🐛 4 | 🌐 Rust | 📅 2026-08-05 - Unified compiler framework for AI and quantum computing; its quantum front covers gate decomposition, noise-aware scheduling, qubit layout mapping, real qubit routing (SWAP + BFS), and OpenQASM 3.0 export. Published on [crates.io](https://crates.io/crates/lift-core).

**Common Lisp**

* [quilc](https://github.com/rigetti/quilc) ⭐ 0 | 🐛 0 | 📅 2026-08-11 - Rigetti's optimizing Quil compiler.

## Quantum converters

**Javascript**

* [qconvert-js](http://github.com/quantastica/qconvert-js) ⭐ 16 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-29 - Quantastica's quantum programming language converter in Javascript.

**Python**

* [qconvert](http://github.com/quantastica/qconvert) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2021-07-14 - Quantastica's quantum programming language converter in Python.

## Quantum assembly

* [OpenQASM](https://github.com/QISKit/openqasm) ⭐ 1,499 | 🐛 105 | 🌐 Python | 📅 2026-08-17 - Open-source quantum assembly language.
* [Quil](https://arxiv.org/abs/1608.03355) - Open hybrid quantum/classical instruction set currently used by Rigetti. [Parser](https://github.com/rigetticomputing/pyquil/tree/master/pyquil/_parser) ⭐ 1,497 | 🐛 242 | 🌐 Python | 📅 2026-08-19
* [QMASM](https://github.com/lanl/qmasm) ⭐ 342 | 🐛 0 | 🌐 Python | 📅 2021-02-28 - Quantum macro assembler for D-Wave's quantum annealers.
* [Blackbird](https://github.com/XanaduAI/blackbird) ⭐ 77 | 🐛 5 | 🌐 C++ | 📅 2022-10-18 - Open-source quantum instruction language currently used for Xanadu's photonic hardware.

## Quantum control

**Python**

* [Qibo](https://github.com/qiboteam/qibo) ⭐ 360 | 🐛 104 | 🌐 Python | 📅 2026-08-18 - Qibo provides a platform agnostic quantum hardware control module with drivers for multiple instruments.
* [Krotov](https://github.com/qucontrol/krotov) ⭐ 84 | 🐛 10 | 🌐 Python | 📅 2025-02-25 - Python implementation of Krotov's method for quantum optimal control.
* [C3](https://github.com/q-optimize/c3) ⭐ 74 | 🐛 50 | 🌐 Python | 📅 2024-03-05 - Open-loop, closed-loop and automated Control, Calibration and Characterization of quantum devices.
* [Quanlse](https://github.com/baidu/Quanlse) ⭐ 43 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2021-12-22 - Quanlse provides quantum control solutions via a cloud SDK, developed by [Baidu Quantum](https://research.baidu.com/Research_Areas/index-view?id=75).
* [gradpulse](https://github.com/PureStateLabs/gradpulse) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-01 - Differentiable, multi-solver-validated pulse optimizer for open-system superconducting-gate fidelities.

## Quantum interoperability

* [scikit-quant](https://github.com/scikit-quant/scikit-quant) ⭐ 47 | 🐛 12 | 🌐 C++ | 📅 2024-02-22 - This is a package to improve interoperability between different quantum computer software packages.
* [Digital Soul](https://github.com/NeuralDreamResearch/DigitalSoul) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2024-06-18 - Unified platform for CPU, GPU, FPGA, and Quantum Computing.

## Quantum error correction

**C++**

* [Tesseract Decoder](https://github.com/quantumlib/tesseract-decoder) ⭐ 113 | 🐛 31 | 🌐 C++ | 📅 2026-08-18 - Most Likely Error decoder designed for Low Density Parity Check (LDPC) quantum error-correcting codes.

**Julia**

* [CodingTheory](https://github.com/esabo/CodingTheory) ⭐ 39 | 🐛 12 | 🌐 Julia | 📅 2026-07-11 - Julia package for constructing and analyzing classical and quantum error-correcting codes.

**Python**

* [PyMatching](https://github.com/oscarhiggott/PyMatching) ⭐ 357 | 🐛 27 | 🌐 C++ | 📅 2026-05-22 - Python package for decoding quantum error correcting codes with minimum-weight perfect matching.
* [MQT QECC](https://github.com/cda-tum/mqt-qecc) ⭐ 232 | 🐛 12 | 🌐 Python | 📅 2026-08-18 - Synthesis of fault-tolerant circuits. Decoders. Automatic Application of error correcting codes. Available via the [`mqt.qecc`](https://pypi.org/p/mqt.qecc) Python package.
* [Qiskit Experiments](https://github.com/Qiskit-Extensions/qiskit-experiments) ⭐ 196 | 🐛 139 | 🌐 Python | 📅 2026-08-12 - Python package for quantum error correction experiments (supported by IBM).
* [Tesseract Decoder](https://github.com/quantumlib/tesseract-decoder) ⭐ 113 | 🐛 31 | 🌐 C++ | 📅 2026-08-18 - Most Likely Error decoder designed for Low Density Parity Check (LDPC) quantum error-correcting codes.
* [qecsim](https://github.com/qecsim/qecsim) ⭐ 94 | 🐛 1 | 🌐 Python | 📅 2021-08-05 - Python package for simulating quantum error correction using stabilizer codes.
* [Qsurface](https://github.com/watermarkhu/qsurface) ⭐ 81 | 🐛 20 | 🌐 Python | 📅 2026-08-04 - Python package for simulation and visualization of quantum error-correction on surface codes.
* [Chromobius](https://github.com/quantumlib/chromobius) ⭐ 40 | 🐛 6 | 🌐 Python | 📅 2026-08-01 - Python implementation of a "mobius decoder" for color codes used in quantum error correction.
* [autoq-qec](https://github.com/Ronaldoengenhariadacomputacao/autoq-qec) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-08-19 - Multi-code fault-tolerant QEC resource estimator for arbitrary Qiskit circuits (Surface Code, Floquet Code, Bacon-Shor, Steane).

## Quantum and post-quantum cryptography

**C**

* [liboqs](https://github.com/open-quantum-safe/liboqs) ⭐ 3,038 | 🐛 114 | 🌐 C | 📅 2026-08-19 - C library for quantum-resistant cryptographic algorithms.
* [PQClean](https://github.com/PQClean/PQClean) ⚠️ Archived - Clean, portable, tested implementations of post-quantum cryptography.
* [openssl](https://github.com/open-quantum-safe/openssl) ⚠️ Archived - OpenSSL with quantum-safe cryptographic algorithms.
* [openssh](https://github.com/open-quantum-safe/openssh-portable) ⭐ 238 | 🐛 6 | 🌐 C | 📅 2026-08-07 - OpenSSH with quantum-safe key exchange algorithms.
* [TQ42 Cryptography](https://github.com/terra-quantum-public/tq42-pqc-oss) ⭐ 52 | 🐛 0 | 🌐 C++ | 📅 2025-03-14 - Post-quantum algorithms, hash functions, digital signature, key encapsulation mechanism, PRNG, and key management functions.

**Python**

* [QRL](https://github.com/theQRL/QRL/) ⭐ 466 | 🐛 51 | 🌐 Python | 📅 2026-08-08 - [Quantum Resistant Ledger](https://theqrl.org/) utilizing hash-based one-time merkle tree signature scheme instead of ECDSA.
* [Crypto-Vinaigrette](https://github.com/aditisrinivas97/Crypto-Vinaigrette) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2019-06-02 - Quantum-resistant asymmetric key generation tool for digital signatures.
* [Qash-QKDC](https://github.com/TimeMelt/qash-qkdc) ⭐ 0 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-09-02 - [Hashing algorithms/circuits](https://timemelt.itch.io/qash-qkdc) powered by quantum operations.
* [Qashchain](https://github.com/TimeMelt/qashchain) ⭐ 0 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-03-13 - [Quantum blockchain](https://timemelt.itch.io/qashchain) based on [qash-qkdc](https://github.com/TimeMelt/qash-qkdc) ⭐ 0 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-09-02 circuits.

## Experimental quantum computing

**Julia**

* [Qlab.jl](https://github.com/BBN-Q/Qlab.jl) ⭐ 15 | 🐛 16 | 🌐 Julia | 📅 2026-04-20 - Generic lab tools in Julia.

**Matlab**

* [Qlab](https://github.com/BBN-Q/Qlab) ⭐ 39 | 🐛 8 | 🌐 MATLAB | 📅 2021-07-09 - Measurement and control software for superconducting qubits.

**Python**

* [ARTIQ](https://github.com/m-labs/artiq) ⚠️ Archived - Next-generation control system for quantum information experiments.
* [QCoDeS](https://github.com/QCoDeS/Qcodes) ⭐ 454 | 🐛 261 | 🌐 Python | 📅 2026-08-19 - Python-based data acquisition framework for quantum experiments.
* [Qiskit Metal](https://github.com/Qiskit/qiskit-metal) ⭐ 424 | 🐛 29 | 🌐 Jupyter Notebook | 📅 2026-08-11 - Quantum hardware design and analysis.
* [scqubits](https://github.com/scqubits/scqubits) ⭐ 284 | 🐛 21 | 🌐 Python | 📅 2026-07-21 - Simulating superconducting qubits, obtaining energy spectra, plotting energy levels and more.
* [pyEPR](https://github.com/zlatko-minev/pyEPR) ⭐ 207 | 🐛 12 | 🌐 Python | 📅 2026-07-17 - Automated Python module for the design and quantization of Josephson quantum circuits.
* [PyRPL](https://github.com/lneuhaus/pyrpl) ⭐ 206 | 🐛 156 | 🌐 HTML | 📅 2026-08-19 - Turn your RedPitaya into a powerful DSP device, suitable as a digital lockbox and measurement device in quantum optics.
* [QTT](https://github.com/QuTech-Delft/qtt) ⚠️ Archived - Quantum Technology Toolbox is a framework for the tuning and calibration of quantum dots and spin qubits.
* [qupulse](https://github.com/qutech/qupulse) ⭐ 60 | 🐛 77 | 🌐 Python | 📅 2026-08-11 - Quantum computing pulse parametrization and sequencing framework (formerly qc-toolkit).
* [QFlow-lite](https://github.com/jpzwolak/QFlow-lite) ⭐ 40 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2022-02-22 - Machine Learning tools for autotuning quantum dot experiments.
* [MQT Qudits](https://github.com/cda-tum/mqt-qudits) ⭐ 39 | 🐛 4 | 🌐 Python | 📅 2026-08-19 - A framework for research and education for mixed-dimensional qudit quantum computing available via the \[`mqt.qudits`] Python package.
* [QGL](https://github.com/BBN-Q/QGL) ⭐ 33 | 🐛 36 | 🌐 Python | 📅 2026-05-21 -  Domain-specific language embedded in Python for specifying pulse sequences.
* [QEDA](https://github.com/Spooky-Manufacturing/QEDA) ⭐ 28 | 🐛 111 | 🌐 Java | 📅 2021-12-19 - Quantum Electronics Design Automation - The RTL of Quantum Computing!
* [OLSQ](https://github.com/tbcdebug/OLSQ) ⭐ 26 | 🐛 0 | 🌐 OpenQASM | 📅 2022-07-23 - OpenQASM package to perform optimal layout synthesis for quantum computing.
* [MQT DASQA](https://github.com/cda-tum/mqt-dasqa) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2025-03-14 - Framework to encapsulate application-driven superconducting architecture design.
* [Atomiq](https://atomiq.one/) - Quantum hardware orchestration stack for complex quantum setups.
* [Quantify](https://gitlab.com/quantify-os/quantify-core) -  Data acquisition platform focused on Quantum Computing and solid-state physics experiments.

## Quantum fun

**Board games**

* [Entanglion](https://github.com/Entanglion/entanglion) ⭐ 477 | 🐛 3 | 📅 2023-06-30 - The world’s first open source quantum computing board game. For 2 players.
* [Unitary](https://github.com/quantumlib/unitary) ⭐ 43 | 🐛 25 | 🌐 OpenQASM | 📅 2026-06-02 - API library providing common operations for adding quantum behaviors to games.

**C++**

* [Quandoom](https://github.com/Lumorti/Quandoom) ⭐ 948 | 🐛 0 | 🌐 C++ | 📅 2024-12-20 - Port of DOOM for a quantum computer.

**F#**

* [Quantum Puzzle Generator](https://github.com/mrdimosthenis/QuantumPuzzleGenerator) ⭐ 8 | 🐛 0 | 🌐 F# | 📅 2026-06-15 - Educational puzzle game for Android and iOS.

**Python**

* [Quantum Awesomeness](https://github.com/decodoku/A_Game_to_Benchmark_Quantum_Computers) ⭐ 49 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-08-16 - [Simple puzzles to benchmark various quantum processor](https://medium.com/@decodoku/understanding-quantum-computers-through-a-simple-puzzle-game-a290dde89fb2).
* [Quantum Catsweeper](https://github.com/desireevl/quantum-catsweeper) ⭐ 22 | 🐛 1 | 🌐 Python | 📅 2022-07-16 - Quantum game loosely based on Minesweeper Flag.
* [Quantum Battleships](https://github.com/decodoku/Battleships_with_complementary_measurements) ⭐ 10 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2018-02-02 - [Playing battleships with quantum measurements](https://medium.com/@decodoku/how-to-program-a-quantum-computer-part-2-f0d3eee872fe).
* [bloqit](https://github.com/kelzheng/bloqit) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2020-02-01 - Tiny qubit duel for your smart phone.
* [SudoQ](https://github.com/subwayHareArmy/SudoQ) ⭐ 6 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2019-10-07 - Sudoku solver that leverages a D-Wave Quantum Annealer.
* [Quantum Nematode](https://github.com/SyntheticBrains/nematode) ⭐ 4 | 🐛 3 | 🌐 Python | 📅 2026-07-25 - C. elegans navigation simulation using quantum variational circuits.
* [QiskitBlocks](https://content.luanti.org/packages/javafxpert/qiskitblocks/) - Game that teaches quantum computing using Qiskit in a Minetest block world.

**Python & JavaScript**

* [Quantum Music Composer for IBM Q](https://github.com/JavaFXpert/quantum-toy-piano-ibmq) - Compose and perform quantum music with IBM Q.
* [Quantum Music Composer for Rigetti](https://github.com/JavaFXpert/quantum-toy-piano) - Compose and perform quantum music with Rigetti's Forest.

**JavaScript**

* [Quantum Game with Photons](https://github.com/stared/quantum-game) ⭐ 361 | 🐛 21 | 🌐 JavaScript | 📅 2025-10-29 - Puzzle game in browser, with polarization, superposition, and measurement.

**Scala**

* [feyn](https://mrdimosthenis.github.io/feyn) - Puzzle game for the browser in which you need to find the combination of gates that the qubits need to pass.

## Quantum tools

**C#**

* [QuantumSuperposition](https://github.com/hutchpd/QuantumSuperposition) ⭐ 26 | 🐛 6 | 🌐 C# | 📅 2026-08-04 - Quantum-inspired C#/.NET library for first-class superpositions and time-looped convergence (PositronicVariables) to model uncertainty and collapse. (Related: [Go port](https://github.com/hutchpd/QuantumSuperPosition-Go) ⭐ 0 | 🐛 0 | 🌐 Go | 📅 2024-11-25).

**C++**

* [MQT QCEC](https://github.com/cda-tum/mqt-qcec) ⭐ 117 | 🐛 13 | 🌐 C++ | 📅 2026-08-19 - Equivalence checking of quantum circuits. Verifying compilation flows. Available via the [`mqt.qcec`](https://pypi.org/p/mqt.qcec) package and fully compatible with Qiskit.
* [MQT QuSAT](https://github.com/cda-tum/mqt-qusat) ⭐ 28 | 🐛 2 | 🌐 C++ | 📅 2026-08-17 - Encoding and equivalence checking of Clifford circuits using satisfiablity testing (SAT).
* [MQT DDVis](https://github.com/cda-tum/mqt-ddvis) ⭐ 27 | 🐛 3 | 🌐 JavaScript | 📅 2026-08-16 - Installation-free web-tool that visualizes quantum decision diagrams for classical simulation and verification. Hosted at <https://www.cda.cit.tum.de/app/ddvis/>.
* [MQT Debugger](https://github.com/cda-tum/mqt-debugger) ⭐ 21 | 🐛 7 | 🌐 C++ | 📅 2026-08-19 - Debugging quantum circuits with IDE integration based on DAP server.

**Java**

* [PlankDB](https://github.com/swampus/plank-db) ⭐ 2 | 🐛 1 | 🌐 Java | 📅 2025-10-14 – A Spring Boot key-value store with Grover-powered quantum search via IBM Qiskit. Clean Architecture, REST API, classical + quantum modes supported.

**Mathematica**

* [Quantum](http://homepage.cem.itesm.mx/lgomez/quantum/) - Free Mathematica add-on for Dirac Bra-Ket Notation, Quantum Algebra, Quantum Computing and the QHD approximation to the Heisenberg Equations of Motion.
* [QI](https://github.com/rogercolbeck/QI) ⭐ 47 | 🐛 0 | 🌐 Mathematica | 📅 2025-09-25 - Toolkit for common quantum information functions.

**Python**

* [Covalent](https://github.com/AgnostiqHQ/covalent) ⭐ 867 | 🐛 100 | 🌐 Python | 📅 2026-08-17 - Tool for running high performance/quantum workflows on advanced computing hardwares.
* [toqito](https://github.com/vprusso/toqito) ⭐ 290 | 🐛 5 | 🌐 Python | 📅 2026-08-18 - Framework to study problems pertaining to entanglement theory, nonlocal games, and other aspects of quantum information.
* [MQT Bench](https://github.com/cda-tum/mqt-bench) ⭐ 126 | 🐛 19 | 🌐 Python | 📅 2026-08-19 - Quantum circuit benchmark suite providing benchmark algorithms for different compilation levels. Web application hosted at <https://www.cda.cit.tum.de/mqtbench/>. Also available via the [`mqt.bench`](https://pypi.org/p/mqt.bench) Python package.
* [ZXLive](https://github.com/Quantomatic/zxlive) ⭐ 103 | 🐛 65 | 🌐 Python | 📅 2026-08-16 - GUI editor for ZX diagrams.
* [orqviz](https://github.com/zapatacomputing/orqviz) ⭐ 95 | 🐛 2 | 🌐 Python | 📅 2023-12-18 - Library to easily visualize the loss landscape of variational quantum algorithms.
* [QUARK](https://github.com/QUARK-framework/QUARK) ⭐ 72 | 🐛 7 | 🌐 Python | 📅 2025-07-30 - Framework for Quantum Computing Application Benchmarking.
* [MQT Problem Solver](https://github.com/cda-tum/mqt-problemsolver) ⭐ 54 | 🐛 5 | 🌐 Python | 📅 2026-08-17 - Automated Framework for Realizing Quantum Computing Solutions.
* [QRAND](https://github.com/pedrorrivero/qrand) ⭐ 28 | 🐛 17 | 🌐 Python | 📅 2021-11-27 - Multiplatform and multiprotocol quantum random number generator for arbitrary probability distributions.
* [pulsemaker](https://github.com/adgt/pulsemaker) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2021-12-12 - Python widget library for designing pulses and pulse schedules for quantum computing hardware.
* [pyQuirk](https://github.com/adgt/pyQuirk) ⭐ 24 | 🐛 1 | 🌐 HTML | 📅 2022-05-19 - Python widget for Quirk to be used in Jupyter notebooks, JupyterLab, and the IPython kernel.
* [IBM Q bot](https://github.com/RQC-QApp/QuantumComputingBot) ⭐ 22 | 🐛 1 | 🌐 Python | 📅 2018-11-30 - Bot for Slack and Telegram to monitor the load of IBM Q quantum computers.
* [QuantumGraphs](https://github.com/ziofil/QuantumGraphs) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2020-08-03 - Grow and study random graphs by a continuous, randomly collapsing quantum walk.
* [Arline Quantum](https://github.com/ArlineQ/arline_quantum) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2024-01-01 - Arline Quantum is an open-source library providing basic functionality for creating and manipulating quantum circuits. It also contains a list of mock quantum hardware.
* [qonduit](https://github.com/adgt/qonduit) ⭐ 15 | 🐛 2 | 🌐 Python | 📅 2021-03-22 - Python library with visualization tools and workflows for quantum computing that utilize the best of what’s available.
* [PauLie](https://github.com/QPauLie/PauLie) ⭐ 11 | 🐛 22 | 🌐 Python | 📅 2026-08-19 - Library for studying algebraic properties of quantum systems, in particular the dynamical Lie algebra of Pauli string generated dynamics.
* [QXMT](https://github.com/Qyusu/qxmt) ⭐ 6 | 🐛 2 | 🌐 Python | 📅 2026-06-12 - Experiment management tool for quantum computing and quantum machine learning.
* [Gridsynth-Python-wrapper](https://github.com/InfamousPlatypus/Gridsynth-Python-wrapper) ⭐ 2 | 🐛 3 | 🌐 Python | 📅 2022-07-27 - Wrapper for using Gridsynth in Python/
* [pymablock](https://gitlab.kwant-project.org/qt/pymablock) - Package for the construction of effective Hamiltonians using quasi-degenerate perturbation theory.
* [qBraid](https://docs.qbraid.com/home/introduction) - Transpiles quantum circuits to and from Cirq, Qiskit, Amazon Braket, Pennylane, Pyquil and allows for execution on any backend.
* * [Qlro](https://github.com/linsletoh/qlro) ⭐ 0 | 🐛 0 | 📅 2026-04-29 - Quantum device selection that ranks tracked backends for a given workload via the WCPP framework, using third-party Metriq benchmarks plus a community-fed (predicted, observed) accuracy dataset ([qlro.io](https://qlro.io); [paper](https://doi.org/10.5281/zenodo.19785800)).
* [qprof](https://gitlab.com/qcomputing/qprof/qprof) - `gprof`-compatible profiler for quantum programs.

**TypeScript**

* [SpookyIDE](http://github.com/Spooky-Manufacturing/SpookyIDE) ⭐ 24 | 🐛 1 | 🌐 TypeScript | 📅 2021-10-03 - IDE designed for quantum computing.

**Others**

* [Quil syntax highlighter](https://github.com/JavaFXpert/quil-syntax-highlighter) - Syntax highlighter for PyCharm.

## Quantum data

* [QDataSet](https://github.com/eperrier/QDataSet) ⭐ 135 | 🐛 1 | 🌐 Python | 📅 2021-08-17 - Quantum datasets for the training and development of QML algorithms.
* [QuPrep](https://github.com/quprep/quprep) ⭐ 3 | 🐛 5 | 🌐 Python | 📅 2026-08-03 - Classical-to-quantum data encoding and preprocessing library for quantum machine learning.

## Abandoned projects

*2+ years of inactivity. Feel free to reanimate, document and contribute to some of this work!*

* [Qiskit Tutorial](https://github.com/QISKit/qiskit-tutorial) ⚠️ Archived - Jupyter notebook filled with tutorials for [Qiskit](https://github.com/QISKit/qiskit) ⭐ 7,721 | 🐛 1,147 | 🌐 Python | 📅 2026-08-19.
* [QuSim](https://github.com/adamisntdead/QuSimPy) ⭐ 726 | 🐛 2 | 🌐 Python | 📅 2021-06-04 - Ideal noise-free multi-qubit simulator written in 150 lines of code.
* [Qiskit Aqua](https://github.com/Qiskit/qiskit-aqua) ⚠️ Archived - Library of various quantum algorithm implemented with [Qiskit](https://github.com/Qiskit/qiskit) ⭐ 7,721 | 🐛 1,147 | 🌐 Python | 📅 2026-08-19.
* [qiskit-ignis](https://github.com/qiskit/qiskit-ignis) ⚠️ Archived - Tools for quantum hardware verification, noise characterization, and error correction.
* [Qiskit-JS](https://github.com/Qiskit/qiskit-js) ⚠️ Archived - [Quantum information software kit](https://qiskit.org/) for JavaScript (supported by IBM).
* [8Q](https://github.com/Spooky-Manufacturing/8Q) ⭐ 99 | 🐛 4 | 🌐 Python | 📅 2022-05-02 - 8 Qbit, Photonic Quantum Computer.
* [Quipper](https://github.com/thephoeron/quipper-language) ⭐ 95 | 🐛 3 | 🌐 Haskell | 📅 2015-08-31 - Scalable functional programming language for quantum computing based on [Quantum Lambda Calculus](https://arxiv.org/abs/cs/0404056).
* [QuantumUtils](https://github.com/QuantumUtils/quantum-utils-mathematica) ⭐ 79 | 🐛 14 | 🌐 Mathematica | 📅 2018-05-30 - Tools for quantum control, simulation, channel representation conversion, and perturbations.
* [BLACK-STONE](https://github.com/thephoeron/black-stone) ⭐ 70 | 🐛 4 | 🌐 Common Lisp | 📅 2017-02-17 - Specification and implementation of quantum common lisp, for gate-model quantum computers.
* [Quantum Virtual Machine](https://github.com/rigetticomputing/reference-qvm) ⚠️ Archived - Reference implementation of Rigetti's Quantum Virtual Machine.
* [QCL](https://github.com/aviggiano/qcl) ⭐ 45 | 🐛 2 | 🌐 C++ | 📅 2018-01-13 - High level, hardware-agnostic programming language for quantum computers (syntax like C or Pascal).
* [QSEL](https://github.com/dabacon/qsel) ⭐ 42 | 🐛 0 | 🌐 Python | 📅 2023-02-26 -  Quantum programming language putting entanglement and superposition front and center.
* [PyQLab](https://github.com/BBN-Q/PyQLab) ⭐ 25 | 🐛 6 | 🌐 Python | 📅 2017-06-06 - Library for instrument control and superconducting QIP experiments.
* [jquil](https://github.com/QCHackers/jquil) ⭐ 16 | 🐛 0 | 🌐 Java | 📅 2018-07-23 - Java library for quantum programming using [Quil](https://en.wikipedia.org/wiki/Quil_\(instruction_set_architecture\)).
* [QGL.jl](https://github.com/BBN-Q/QGL.jl) ⭐ 13 | 🐛 7 | 🌐 Julia | 📅 2023-12-19 - Performance orientated [QGL](https://github.com/BBN-Q/QGL) ⭐ 33 | 🐛 36 | 🌐 Python | 📅 2026-05-21 compiler.
* [QOCS](https://github.com/dillanchang/QOCS) ⭐ 11 | 🐛 0 | 🌐 OCaml | 📅 2017-07-27 - Quantum OCaml Circuit Simulator is a functional approach to simulating quantum gates.
* [Squankum](https://github.com/jeffwass/Squankum) ⭐ 10 | 🐛 0 | 🌐 Java | 📅 2012-05-05 - Visual Java quantum simulator.
* [sapi\_dimod](https://github.com/dwavesystems/dwave_sapi_dimod) ⚠️ Archived - [Dimod](https://github.com/dwavesystems/dimod) ⭐ 142 | 🐛 159 | 🌐 Python | 📅 2026-08-04 wrapper for D-Wave's Solver API (SAPI).
* [libQuantumJava](https://github.com/gbanegas/libQuantumJava) ⭐ 8 | 🐛 0 | 🌐 Java | 📅 2018-08-07 - Crude translation from the C implementation of `libquantum` to a Java version.
* [PySimulator](https://github.com/BBN-Q/PySimulator) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2014-02-14 - Python with C++ backend simulator for superconducting circuits.
* [Quince](https://github.com/BBN-Q/Quince) ⭐ 8 | 🐛 5 | 🌐 Python | 📅 2023-12-07 - Node-based GUI that allows for graphical configuration of qubit experiments in Auspex.
* [QCViewer](https://github.com/QCT-IQC/QCViewer) ⭐ 7 | 🐛 0 | 🌐 C++ | 📅 2015-09-18 - Visual quantum circuit design and simulation tool.
* [QACG](https://github.com/QCT-IQC/qacg) ⭐ 6 | 🐛 0 | 🌐 Haskell | 📅 2013-08-22 - Quantum Arithmetic Circuit Generator in Haskell.
* [Qlmp](https://github.com/wintershammer/QImp) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2017-05-28 -  Interpreter for the functional quantum programming language Qumin.
* [goqu](https://github.com/cco3/goqu) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2024-04-02 - Quantum computing simulation library for GoLang.
* [libquantum](http://libquantum.de) - C library for quantum computing and quantum simulation.
* [pQCS](https://qsoft.iqc.uwaterloo.ca/#software) - [Parallel quantum circuit synthesis](https://uwspace.uwaterloo.ca/handle/10012/9267) with optimal T-count.

## Contributing

See the [contribution guidelines](CONTRIBUTING.md/#readme).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the Quantum Open Source Foundation has waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
