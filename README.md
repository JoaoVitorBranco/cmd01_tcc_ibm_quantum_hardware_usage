# CMD01 - TCC - IBM Quantum Hardware Usage

## 📂 Description

This repository contains experiments performed on the IBM Quantum platform, focusing on the implementation of the order finding algorithm—a fundamental component of Shor's algorithm. The goal is to evaluate the use of real IBM quantum hardware, its limitations, and differences compared to simulators.

## ⚛️ About the Experiment

The order finding algorithm is a central part of Shor's algorithm, used for integer factorization. In this project, quantum circuits are prepared and executed on real IBM Quantum backends using Qiskit and IBM Quantum Runtime.

Main steps of the experiment:
- Authentication and configuration of the IBM Quantum account.
- Automatic selection of the least busy real backend.
- Execution of simple circuits (e.g., Hadamard gate on a qubit).
- Measurement of real hardware results.
- Visualization and analysis of practical limitations.
- Querying the number of qubits available on different backends.

## 📦 Requirements

- Python 3.8+
- IBM Quantum account with API access
- Packages listed in `requirements.txt`:
  - qiskit
  - qiskit-ibm-runtime
  - python-dotenv
  - matplotlib

## 🚀 How to Run

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Create a `.env` file with your credentials:
   ```
   IBM_QUANTUM_API_KEY=your_token_here
   IBM_QUANTUM_INSTANCE_CRN=your_instance_crn_here
   ```

3. Run the notebook `0_sampler.ipynb` to execute the experiments.

## 📒 Code Structure

The notebook `0_sampler.ipynb` includes:
- Importing required libraries.
- Loading environment variables.
- IBM Quantum account setup.
- Selection of the least busy real backend.
- Execution of a simple circuit (Hadamard + measurement).
- Visualization of results with histograms.
- Querying the number of qubits of available backends.

## 🔗 References

- [IBM Quantum Platform](https://quantum.cloud.ibm.com/instances)
- [Qiskit IBM Runtime Documentation](https://quantum.cloud.ibm.com/docs/en/api/qiskit-ibm-runtime/ibm-backend)

## 👥 Authors

- [João Vitor Choueri Branco](https://www.linkedin.com/in/jo%C3%A3o-vitor-choueri-branco-a756ab209)
- [Vitor Guirão Soller](https://www.linkedin.com/in/vitor-soller)

## 🧠 Advisor

- [Prof. Dr. Sandro Martini](https://www.linkedin.com/in/profsandromartini1972)
