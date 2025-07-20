
# 🧪 Variational Quantum Eigensolver (VQE) for H₃ Molecule using PennyLane

This project demonstrates how to use the **Variational Quantum Eigensolver (VQE)** to estimate the ground state energy (lowest eigenvalue) of the **H₃ molecule** using [PennyLane](https://pennylane.ai/), a quantum machine learning library.

---

## 📌 What’s in this project?

We use the following steps:
1. **Define the H₃ molecule** – specify atoms and their 3D coordinates.
2. **Build the Hamiltonian** – using PennyLane’s quantum chemistry module.
3. **Initialize the system** – with a Hartree-Fock reference state.
4. **Create a variational ansatz** – with double excitations.
5. **Define a cost function** – based on expectation of the Hamiltonian.
6. **Run optimization** – using gradient descent to find the lowest energy.

---

## 🛠 Requirements

Make sure you have Python 3.8+ and the following libraries installed:

```bash
pip install pennylane pennylane-qchem
```

---

## ▶️ Run the Code

You can open and run the code using Jupyter Notebook or any compatible environment.

The main file is:  
📄 `vqe_h3.ipynb`

---

## 🧠 Final Result

After training, the VQE algorithm predicts the ground state energy of the H₃ molecule to be:

```
Energy ≈ -1.2744 Ha
```

---

## 📚 Reference

- PennyLane VQE Docs: https://docs.pennylane.ai
- VQE Algorithm: https://pennylane.ai/qml/demos/tutorial_vqe/

---

## ✨ License

This project is open-source and free to use under the MIT license.
