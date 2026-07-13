# Quantum Algorithms

Implementations of foundational quantum computing algorithms from scratch in Python using [Qiskit](https://www.qiskit.org/). Built as part of an independent study of quantum computing and quantum information, working primarily from Muccioli's *Introduction to Quantum Information Processing* and Hidary's *Quantum Computing: An Applied Approach*, with Nielsen & Chuang's *Quantum Computation and Quantum Information* as a reference.

Each algorithm is implemented and verified in its own notebook, spanning oracle-based algorithms and entanglement protocols, along with Grover's search and a complete end-to-end implementation of Shor's algorithm with classical RSA factoring.

## Algorithms

| Notebook | Description |
|----------|-------------|
| [`deutsch.ipynb`](deutsch.ipynb) | Deutsch's algorithm — the original constant-vs-balanced problem on 2 qubits |
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
