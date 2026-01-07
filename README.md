### Hi there, I'm Andreas!

PhD student in theoretical physics specializing in **computational many-body methods** (Tensor Networks, Exact Diagonalization, Monte Carlo). My work focuses on moiré systems and large-scale numerical simulations, and I enjoy building high-performance Julia libraries for scientific computing, quantitative modeling, and industry applications.

### About me

- Researcher at the University of Würzburg working on moiré materials and strongly correlated electrons using tensor-network and Monte Carlo methods.
- Interested in software development at the intersection of physics, software engineering, and quantitative finance, especially where numerical modeling, HPC, and rigorous data-driven decision making matter.

### What I'm currently working on

- Maintaining and developing many-body methods and generic Julia packages in the open-source organization [ManyBodyLab](https://github.com/ManyBodyLab) [manybodylab.com](https://www.manybodylab.com/):
  - Infinite tensor-network algorithms (e.g. iDMRG, MPO-compression) based on [ITensors.jl](https://github.com/ITensor/ITensors.jl)
  - MPI-parallelized tensor-network algorithms in [MPSKitParallel.jl](https://github.com/ManyBodyLab/MPSKitParallel.jl)
  - High-performance exact diagonalization tools in [DiagHamInterface.jl](https://github.com/ManyBodyLab/DiagHamInterface.jl)
  - Allocation-free Monte Carlo algorithms for quantum many-body systems in [WaveMC.jl](https://github.com/ManyBodyLab/WaveMC.jl) (based on the [Carlo.jl](https://github.com/lukas-weber/Carlo.jl) framework)
- Designing modular backends to support multiple tensor-network libraries, improving flexibility and reuse across projects and reducing duplication in downstream codes.
  - [TensorKitAdapters.jl](https://github.com/ManyBodyLab/TensorKitAdapters.jl) & [MPSKitAdapters.jl](https://github.com/ManyBodyLab/MPSKitAdapters.jl)
- Contributing to [MPSKit.jl](https://github.com/QuantumKitHub/MPSKit.jl), abstracting code and improving performance and maintainability.

### Featured Projects

#### [High-Frequency Limit Order Book (C++)](https://github.com/AFeuerpfeil/cpp_orderbook)
- Implemented a low-latency C++ matching engine (price-time priority) achieving 15+ million orders/s on real and synthetic LOBSTER data using a single CPU core
- Reduced p99 latency to <200 ns by replacing pointer-based linked lists with a pre-allocated contiguous memory pool (intrusive list), minimizing cache misses and allocator overhead during bursty workloads
- Designed a deterministic testing suite using fuzzing and edge cases to verify correctness against a reference model
- Engineered a binary parser for the NASDAQ TotalView-ITCH 5.0 protocol to efficiently ingest raw market data

### Get in touch

- **Email**: [andreas.feuerpfeil@manybodylab.com](mailto:andreas.feuerpfeil@manybodylab.com)
- **LinkedIn**: [Andreas Feuerpfeil](https://www.linkedin.com/in/andreasfeuerpfeil)
- **Website**: [manybodylab.com](https://www.manybodylab.com/)
