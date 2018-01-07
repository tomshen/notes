---
layout: post
title: Quantum Computing in the NISQ era and beyond
date: 2018-01-06T18:50:05-05:00
---

Notes on ["Quantum Computing in the NISQ era and beyond"](https://arxiv.org/abs/1801.00862):

> Noisy Intermediate-Scale Quantum (NISQ) technology will be available in the near future. Quantum computers with 50-100 qubits may be able to perform tasks which surpass the capabilities of today's classical digital computers, but noise in quantum gates will limit the size of quantum circuits that can be executed reliably. NISQ devices will be useful tools for exploring many-body quantum physics, and may have other useful applications, but the 100-qubit quantum computer will not change the world right away --- we should regard it as a significant step toward the more powerful quantum technologies of the future. Quantum technologists should continue to strive for more accurate quantum gates and, eventually, fully fault-tolerant quantum computing.

- No known classical algorithm can simulate a quantum computer
- Need to distinguish between classically hard and quantumly hard problems
- The lowest possible error rate per gate for two-qubit gates is > 0.1%
- Quantum error correction is a difficult problem that is holding us back from effectively solvely many problems and currently has high overhead
- 2000-qubit quantum devices currently exist (e.g. [D-Wave 2000Q](https://www.dwavesys.com/sites/default/files/D-Wave%202000Q%20Tech%20Collateral_0117F.pdf)), but they are quantum annealers rather than circuit-based quantum devices.
- Quantum annealers solve optimiziatino problems, but not by executing quantum circuits (how do they use qubits then?)
- [BQP](https://en.wikipedia.org/wiki/BQP) is the quantum complexity class analogous to classical BPP (not P).