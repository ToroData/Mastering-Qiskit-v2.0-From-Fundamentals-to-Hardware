# Contributing Guidelines

Thank you for your interest in contributing to **Mastering Qiskit v2.0 — From Fundamentals to Hardware**.  
This project is **independent of IBM** and based solely on my experience and knowledge of Qiskit.  
By contributing, you agree to follow these guidelines to ensure the quality, consistency, and integrity of the course.

---

## 1. Types of Contributions

We welcome contributions that improve the course and its materials:

- **Code improvements**:  
  - Bug fixes, optimization, and enhancements to existing notebooks.  
  - New code sections that can be integrated into the existing episodes.  
  - Entirely new notebooks must first be proposed and discussed (see below).

- **Documentation and wording**:  
  - Fixing typos, grammar issues, and improving clarity.  
  - Enhancing explanations for better understanding.

- **Translations**:  
  - Currently limited to **English** and **Spanish** to ensure fidelity.  
  - Other languages are not supported at this time.

- **Advanced content proposals**:  
  - Can be suggested for future episodes, but may not be integrated immediately.

---

## 2. Contribution Process

- **For substantial changes** (new features, large code additions, advanced content):
  - Open a GitHub **Issue** to discuss your idea before starting development.  
  - Provide context, reasoning, and possible integration points.

- **For small fixes** (typos, minor code corrections):
  - Directly open a **Pull Request (PR)**.

- **Review policy**:
  - All contributions must be reviewed and approved by the repository maintainer before merging.
  - The maintainer reserves the right to request changes or reject contributions that do not align with the project’s scope or standards.

---

## 3. Code & Content Standards

- **Python code style**:
  - Follow [PEP 8](https://peps.python.org/pep-0008/) style guidelines.
  - Use type hints where they enhance clarity.
  - Write clear, concise **docstrings** for every function, including:
    - **Parameters** and their types.
    - **Return values**.
    - **Exceptions raised** (if applicable).

- **Notebooks**:
  - No fixed section structure is required, but content must be coherent and consistent with the rest of the course.
  - Integrate explanations alongside code cells to aid learning.

- **Assets**:
  - All images, videos, or supplementary files must be placed in an `assets/` folder inside the episode's directory.  
  - Organize assets in subfolders (e.g., `assets/img`, `assets/video`).

---

## 4. Licensing & Qiskit Usage

- This project is licensed under the **Apache License 2.0**.
- By contributing, you agree that your work will be distributed under this license.
- The project uses Qiskit, an IBM open-source framework, but is **not affiliated with IBM**.
- Contributions must:
  - Maintain independence from IBM proprietary materials.
  - Avoid plagiarism from IBM or other sources.

---

## 5. Collaboration & Conduct

- All contributors must follow the [Code of Conduct](CODE_OF_CONDUCT.md).
- Expected behaviors include:
  - Respectful and inclusive communication.
  - Constructive feedback.
  - No harassment, racism, sexism, or discrimination of any kind.

---

## 6. Testing & Validation

- There is **no automated CI testing** at this time.
- The maintainer will manually review and test contributions before merging.
- Contributors are encouraged to:
  - Ensure that notebooks run without errors before submitting.
  - Verify that outputs match expectations.

---

## 7. How to Submit a Pull Request

1. **Fork** this repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/my-improvement
