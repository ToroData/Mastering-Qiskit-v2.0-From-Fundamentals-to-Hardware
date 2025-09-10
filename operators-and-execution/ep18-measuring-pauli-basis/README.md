# Episode 18 — Measuring Observables in the Pauli Basis

**This episode covers** how to represent and manipulate quantum operators in Qiskit using `SparsePauliOp`, `Pauli`, and `Operator` classes. You will learn how to build observables and Hamiltonians, perform algebraic operations between operators, convert dense matrices to sparse Pauli form, and measure in different Pauli bases, both manually and with the `Estimator` primitive.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ToroData/Mastering-Qiskit-v2.0-From-Fundamentals-to-Hardware/blob/main/ep18-measuring-pauli-basis/episode-18.ipynb)

## 🎯 Learning goals

* Represent observables efficiently with `SparsePauliOp`
* Compose, add, scale, and tensor operator objects
* Convert dense matrices to Pauli sums for quantum evaluation
* Understand when to use `Pauli` vs. `SparsePauliOp` vs. `Operator`
* Compute expectation values with `Estimator`
* Measure in X/Y/Z bases via basis-change circuits

---

## 📁 Assets

The **LinkedIn carousel** for this episode is available in the `images/` folder.

![Example](images/1.png)

---

**Next episode:** Episode 19 — Working with the Operator Class in Depth
