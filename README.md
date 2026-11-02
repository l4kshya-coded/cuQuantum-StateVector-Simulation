# GPU-Accelerated Quantum State-Vector Simulation

A high-performance computational script demonstrating quantum circuit simulation and multi-qubit state vector manipulation offloaded to an NVIDIA GPU using **cuQuantum** and **Qiskit Aer**.

## Overview
Simulating quantum mechanics on standard CPUs scales exponentially ($2^N$), creating a severe computational bottleneck. This project utilizes NVIDIA GPU acceleration via the `cuStateVec` library backend to execute tensor operations and quantum gate transformations for multi-qubit systems (GHZ states) efficiently.

## Technical Stack
* **Language:** Python
* **Compute Framework:** NVIDIA cuQuantum / Qiskit Aer GPU
* **Hardware Environment:** NVIDIA Tesla T4 GPU (Cloud / Google Colab runtime)
* **Libraries:** `qiskit`, `qiskit-aer-gpu`, `cupy`

## Execution & Code
The complete executable Jupyter notebook is available in this repository under `cuquantum_statevector_simulation.ipynb`. It configures a hardware-accelerated state vector simulation backend and outputs collapsed measurement probabilities for entangled qubit registers.

------------------------------------------------------------------------------------
*Developed as part of the NVIDIA Developer Program technical ecosystem.*
