# Episode 20 — Optimize for Target Hardware

**This episode covers** the introduction to hardware-aware optimization in Qiskit, focusing on how the transpiler stack converts abstract quantum circuits into Instruction Set Architecture (ISA) circuits tailored for a specific backend. We explain the role of the PassManager, StagedPassManager, transpilation stages, and how Qiskit addons and functions can integrate into the optimization process. This foundational knowledge will prepare you for more advanced hardware optimization patterns in future episodes.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ToroData/Mastering-Qiskit-v2.0-From-Fundamentals-to-Hardware/blob/main/ep20-hardware-aware-optimization/episode-20.ipynb)

## 🎯 Learning goals

- Understand the purpose of optimizing quantum circuits for specific hardware backends.
- Learn what an Instruction Set Architecture (ISA) circuit is and why it is required.
- Identify the stages of Qiskit’s transpiler pipeline (init, layout, routing, translation, optimization, scheduling).
- Recognize the role of the PassManager and StagedPassManager.
- Get an overview of available Qiskit addons and functions for optimization.

---

## 📁 Assets

The **LinkedIn carousel** for this episode is available in the `images/` folder.

![Example](images/20.png)

---

**Next episode:** Episode 21 — Execute on Target Hardware
