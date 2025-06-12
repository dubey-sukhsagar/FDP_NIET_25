# FDP_NIET_25



---

## 📘 Notebook Descriptions

### 1. `grover_algorithm.ipynb`
This notebook introduces **Grover's search algorithm**, a fundamental quantum algorithm for unstructured search problems.

**Contents:**
- Explanation of the algorithm (oracle, diffusion operator, etc.)
- Step-by-step implementation using Qiskit
- Example: Finding a marked element in a small list
- Visualization of amplitude amplification

---

### 2. `Simulation of AES S-Box (C1).ipynb`
This notebook simulates the **S-box (Substitution Box)** component of a cryptographic cipher using quantum gates.

**Contents:**
- Reversible logic circuit design for a 4-bit S-box
- Implementation using basic quantum gates (Toffoli, CNOT, NOT)
- Truth table verification and analysis

---

### 3. `grover_attack_simplified_aes.ipynb`
This notebook demonstrates a **quantum attack on simplified AES** using Grover's algorithm to recover the encryption key.

**Contents:**
- Description of simplified AES (small key and block size)
- Construction of the oracle for known-plaintext attack
- Application of Grover's algorithm to find the correct key
- Performance and scalability discussion

---

## 🛠️ Requirements

To run the notebooks, install the following Python packages:

```bash
pip install qiskit matplotlib numpy qiskit_aer
