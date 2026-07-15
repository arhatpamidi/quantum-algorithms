# Quantum Algorithms

Implementations of foundational quantum computing algorithms from scratch in Python using [Qiskit](https://www.qiskit.org/). Built as part of an independent study of quantum computing and quantum information, working through Muccioli's *Introduction to Quantum Information Processing* and Hidary's *Quantum Computing: An Applied Approach*, with Nielsen & Chuang's *Quantum Computation and Quantum Information* as a reference.

Each algorithm is implemented and verified in its own notebook. These include simpler oracle-based algorithms, entanglement-based protocols, and the Quantum Fourier Transform, with the most substantial implementations being Grover's search and Shor's algorithm with classical RSA factoring.

## Algorithms

| Notebook | Description |
|----------|-------------|
| [`deutsch.ipynb`](deutsch.ipynb) | Deutsch's algorithm — Determine in a single query whether a one-bit black-box function is constant or balanced |
| [`deutsch_jozsa.ipynb`](deutsch_jozsa.ipynb) | Deutsch-Jozsa — generalized to arbitrary input size |
| [`bernstein_vazirani.ipynb`](bernstein_vazirani.ipynb) | Bernstein-Vazirani — recovering a hidden bitstring in a single query |
| [`simon.ipynb`](simon.ipynb) | Simon's algorithm — finding a hidden period, the precursor to Shor's |
| [`quantum_teleportation.ipynb`](quantum_teleportation.ipynb) | Quantum teleportation of an arbitrary single-qubit state |
| [`superdense_coding.ipynb`](superdense_coding.ipynb) | Superdense coding — transmitting two classical bits via one qubit |
| [`chsh_game.ipynb`](chsh_game.ipynb) | CHSH game / Bell inequality test — demonstrating a quantum violation of the classical bound |
| [`qft.ipynb`](qft.ipynb) | Quantum Fourier Transform |
| [`quantum_phase_estimation.ipynb`](quantum_phase_estimation.ipynb) | Quantum Phase Estimation — eigenvalue estimation, the core subroutine of Shor's |
| [`grovers.ipynb`](grovers.ipynb) | Grover's search — quadratic speedup for unstructured search |
| [`shors_rsa.ipynb`](shors_rsa.ipynb) | Shor's algorithm with end-to-end RSA factoring |

## Tools

Python, Qiskit, NumPy
