#  Quantum Teleportation with Qiskit  
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## 📖 Project Description

This repository contains a Qiskit-based simulation and demonstration of **quantum state teleportation** using a **random single-qubit gate**. The protocol leverages **quantum entanglement**, **Bell-state measurement**, and **classical communication** to transfer a quantum state from one qubit to another without physically moving it.

---

##  Background

Quantum teleportation is a fundamental quantum information protocol enabling the transfer of an unknown quantum state using a pair of entangled qubits and two classical bits. This project demonstrates:

- Generation of a **random quantum state** using the `UGate`.
- **Entanglement** creation between two qubits (Alice and Bob).
- **Bell-state measurement** by Alice.
- **Classical communication** of measurement results.
- **Reconstruction of the state** on Bob’s side.
- **Verification** of teleportation success via inverse gate.

---

## ⚙️ How It Works

1. A **random `UGate`** is applied to an initial qubit to simulate an unknown quantum state.
2. A **teleportation circuit** is composed which includes:
   - Entanglement creation between Alice and Bob.
   - Bell-state measurement by Alice.
   - Conditional operations on Bob's qubit.
3. The entire protocol is applied to the initial quantum state.
4. The **inverse** of the random gate is applied to Bob’s qubit.
5. The result is measured to verify **successful teleportation**.

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yagni24/quantum-teleportation-qiskit.git
   cd quantum-teleportation-qiskit
   
2. Install required packages:
   ```bash
   pip install qiskit matplotlib

3. Run the notebook:

   - Use Jupyter Notebook or JupyterLab to open and execute the cells step-by-step.

   - Make sure ```%matplotlib inline``` is enabled to view histograms.


📊 Output
The simulation produces:

- Histograms of final qubit measurements 
- Marginal distribution showing teleportation fidelity
- LaTeX rendering of the random unitary matrix
- Visual representation of circuit and entanglement


📄 License
This project is licensed under the MIT License — see the LICENSE file for details.

🙌 Acknowledgements
Built with ❤️ using Qiskit

Inspired by IBM Quantum tutorials and open-source quantum computing education








