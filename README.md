# Quantum Algorithms

Implementations of foundational quantum computing algorithms from scratch in Python using [Qiskit](https://www.qiskit.org/). Built as part of an independent study of quantum computing and quantum information, working through Muccioli's *Introduction to Quantum Information Processing* and Hidary's *Quantum Computing: An Applied Approach*, with Nielsen & Chuang's *Quantum Computation and Quantum Information* as a reference.

Each algorithm is implemented and verified in its own notebook. These include simpler oracle-based algorithms, entanglement-based protocols, and the Quantum Fourier Transform, with the most substantial implementations being Grover's search and Shor's algorithm with classical RSA factoring.

## Algorithms

| Notebook | Description |
|----------|-------------|
| [`deutsch.ipynb`](deutsch.ipynb) | Deutsch's algorithm — Determine in a single query whether a one-bit black-box function is constant or balanced |
| [`deutsch_jozsa.ipynb`](deutsch_jozsa.ipynb) | Deutsch-Jozsa Algorithm — Determine in a single query whether an n-bit black-box function is constant or balanced |
| [`bernstein_vazirani.ipynb`](bernstein_vazirani.ipynb) | Bernstein-Vazirani Algorithm — Recover a hidden n-bit string from a linear black-box function in a single query |
| [`simon.ipynb`](simon.ipynb) | Simon's Algorithm - Recover the hidden period of a 2:1 function or identify it as 1:1 in $O(n)$ |
| [`quantum_teleportation.ipynb`](quantum_teleportation.ipynb) | Quantum Teleportation - Transfer an arbitrary single qubit state using an entangled Bell pair |
| [`superdense_coding.ipynb`](superdense_coding.ipynb) | Superdense Coding — Transmit 2 classical bits by sending 1 qubit of a Bell pair, mirroring quantum teleportation |
| [`chsh_game.ipynb`](chsh_game.ipynb) | CHSH Game — Demonstrate quantum mechanics' incompatibility with local hidden variable theories through violation of classical CHSH bound using entanglement |
| [`qft.ipynb`](qft.ipynb) | Quantum Fourier Transform |
| [`quantum_phase_estimation.ipynb`](quantum_phase_estimation.ipynb) | Quantum Phase Estimation — eigenvalue estimation, the core subroutine of Shor's |
| [`grovers.ipynb`](grovers.ipynb) | Grover's search — quadratic speedup for unstructured search |
| [`shors_rsa.ipynb`](shors_rsa.ipynb) | Shor's algorithm with end-to-end RSA factoring |

## Tools

Python, Qiskit, NumPy
