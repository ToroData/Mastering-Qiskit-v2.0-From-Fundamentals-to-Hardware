# Ep. 13: Understanding Qubit and Bit Ordering

This episode covers how qubit and bit ordering works in Qiskit, the difference between internal indexing, diagram ordering, and measurement string representation — and why misunderstanding this is one of the most common sources of bugs in Qiskit code.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ToroData/Mastering-Qiskit-v2.0-From-Fundamentals-to-Hardware/blob/main/ep13-bit-ordering/episode-13.ipynb)

## 🎯 Learning goals

- Understand how Qiskit internally indexes qubits in a `QuantumCircuit`.
- Recognize how diagram ordering differs from internal indexing.
- Interpret bit significance in integers (LSB vs MSB).
- Correctly read and interpret measurement strings.
- Relate statevector indices to computational basis states.
- Apply controlled gate conventions consistently.
- Know the difference between reversing diagram order and reversing logical qubit order.

---

## 📁 Assets

The **LinkedIn carousel** for this episode is available in the [images/](images/) folder.

![Example](images/1.png)

---

**Next episode:** Episode 14 — Working with Qiskit’s Measurement and Result Objects
