# Eclipse Qrisp: High-Level Quantum Programming for Dynamic Algorithms

**Tutorial at IEEE Quantum Week 2026 (QCE26), Toronto, Ontario, Canada**

This repository hosts the agenda, materials, and participant resources for our QCE26 tutorial on [Qrisp](https://github.com/eclipse-qrisp/Qrisp), an open-source, high-level quantum programming framework.

**Instructors**
- [Matic Petrič](https://github.com/MatP1337), Fraunhofer FOKUS
- [Pietropaolo Frisoni](https://github.com/PietropaoloFrisoni), IQM Quantum Computers
- [Purva Thakre](https://github.com/purva-thakre), IQM Quantum Computers

---

## About

Circuit-based quantum computation, as favored by popular frameworks like Qiskit and Cirq, becomes cumbersome as algorithms grow in complexity, forcing researchers to manually track gate placements and qubit allocations, particularly beyond the NISQ regime. This tutorial provides a hands-on introduction to Qrisp, which enables a top-down, Pythonic approach to quantum algorithm development that bypasses the need to start at the circuit level.

## What You'll Learn

- The fundamentals of high-level quantum programming and the shift from manual gate construction to intuitive software engineering
- How to use algorithmic primitives to efficiently prototype complex algorithms in Pythonic syntax
- How to perform resource estimation analysis to assess feasibility on current and future fault-tolerant hardware
- How to bridge theoretical algorithmic ideas and executable code
- The Qrisp ecosystem: documentation, installation, and support for dynamic quantum computation

## Audience & Level

**Prerequisites:** basic linear algebra, gate-level quantum circuits, and classical Python programming. No prior JAX experience required; Jasp is introduced from the ground up.

**Difficulty:** 40% beginner, 30% intermediate, 30% advanced

## Format

Two 90-minute sessions blending slide presentations with hands-on Google Colab notebook exercises. Participants are encouraged to bring a laptop with internet access. For those who prefer a local setup, each Colab notebook can be downloaded as a Jupyter notebook and run on your own machine.

## Agenda

Two 90-minute sessions. Each session pairs slide presentations with hands-on Google Colab notebooks.

### Session 1 — Introduction to static Qrisp (90 min)

**Part 1: Static Qrisp (0–60 min)**

| Time | Topic | Format |
|------|-------|--------|
| 0–15 | Introduction to static Qrisp | Slides |
| 15–60 | Hands-on Code Demo| Google Colab notebook |
| | Setup and installation | |
| | Qrisp quantum types: `QuantumVariable`, `QuantumFloat`, `QuantumBool`, `QuantumModulus` | |
| | Quantum environments: `control`, `condition`, `invert`, additional environments, and automatic uncomputation | |
| | Quantum arithmetic and Shor's algorithm: adders, modular arithmetic, and order finding | |
| | Extras (if time permits): the `Operator` class — Hamiltonians, trotterization, and expectation values | |

**Part 2: Block encodings (60–90 min)**

| Time | Topic | Format |
|------|-------|--------|
| 60–65 | Block encodings motivation | Slides |
| 65–80 | Block encodings, qubitization, QSP | Google Colab notebook |
| 80–90 | Block encodings as programming abstractions with the `BlockEncoding` class: constructors, arithmetic, resource estimation, inversion, polynomial transformations | Google Colab notebook |

### Session 2 — Jasp and just-in-time compilation (90 min)

**Part 1: Jasp (0–60 min)**

| Time | Topic | Format |
|------|-------|--------|
| 0–10 | Introduction to Jasp in Qrisp | Slides |
| 10–35 | How tracing works in Qrisp | Google Colab notebook |
| 35–60 | How just-in-time compilation works in Qrisp | Google Colab notebook |

**Part 2: Block encodings (60–90 min)**

| Time | Topic | Format |
|------|-------|--------|
| 60–65 | `BlockEncoding` class recap | Slides |
| 65–80 | Eigenstate filtering using QSP | Google Colab notebook |
| 80–90 | Wrap up | Slides |

## Resources

- Qrisp documentation: https://www.qrisp.eu/
- Qrisp on GitHub: https://github.com/eclipse-qrisp/Qrisp
- Tutorial materials (slides, Google Colab notebooks, handouts): _links provided during the session_

---

*This tutorial is part of [IEEE Quantum Week 2026](https://qce.quantum.ieee.org/2026/), 13-18 September 2026, Toronto, Canada.*
