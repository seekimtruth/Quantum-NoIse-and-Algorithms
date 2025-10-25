# Quantum-NoIse-and-Algorithms
From attosecond decoherence to noise-aware quantum algorithms. To bridge physical noise modeling and quantum algorithmic mitigation through hands-on implementations using Qiskit, Mitiq, and classical ML tools.

This repository collects my self-directed projects bridging **quantum algorithms** and **noise analysis**, 
from basic VQE implementations to hybrid and noise-aware techniques.

## Structure
| Folder | Topic | Description |
|--------|--------|-------------|
| 01_vqe_ising_noise | Noise-Axare VQE (Ising model) | 2-qubit Ising Hamiltonian + ZNE mitigation (baseline benchmark)
| 02_vqe_h2 | VQE for H₂ molecule | Quantum chemistry benchmark using Qiskit Nature |
| 03_vqe_lih_scaling | LiH scalability | Analyze noise & CNOT scaling vs accuracy |
| 04_qaoa_maxcut | QAOA for optimization | Solve Max-Cut using Qiskit Optimization |
| 05_noise_mitigation | Error mitigation | ZNE / PEC / CDR comparison with Mitiq |
| 06_density_matrix_noise | Density-matrix evolution | Visualize decoherence under amplitude & phase damping |

## Skills Demonstrated
- Quantum algorithms: VQE, QAOA; Variational Quantum Classifier
- Noise modeling: Amplitude/phase damping, measurement error mitigation
- Libraries: **Qiskit**, **Mitiq**; **Qiskit Nature**, **Optimization**
- Resource analysis: CNOT count, transpilation depth, runtime scaling
- Engineering practices: Mpdular scripts, reproducible notebooks, GitHub Actions CI

## Background & Motivation
PhD in **attosecond laser physics** - studied photoelectron spectrogram, density-matrix reconstruction, and decoherence quantification.  
These projects connect my experience into **quantum-computing noise domain**, connecting ultrafast-physics insight with quantum algorithms.

## Setup
'''bash
git clone https://github.com/<seekimtruth>/Quantum-Noise-and-Algorithms.git
	cd Quantum-Noise-and-Algorithms
	pip install -r requirements.txt
