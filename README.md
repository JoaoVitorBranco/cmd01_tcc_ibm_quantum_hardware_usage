# CMD01 - TCC - IBM Quantum Hardware Usage

## 📂 Description

This repository contains practical experiments on the IBM Quantum platform, focusing on the implementation and execution of the order finding algorithm—a key component of Shor's algorithm for integer factorization. The notebook explores both theoretical and practical aspects, including modular exponentiation, quantum Fourier transform (QFT), and execution on real quantum hardware.

## ⚛️ About the Project

The notebook `0_sampler.ipynb` demonstrates:
- Loading environment variables and authenticating with IBM Quantum.
- Selecting the least busy real backend for execution.
- Running basic quantum circuits (Hadamard gate measurement).
- Querying backend qubit counts and operational status.
- Building modular exponentiation gates and QFT circuits.
- Constructing and executing the order finding circuit, including:
  - Modular multiplication gates
  - Quantum Fourier Transform
  - Measurement and result analysis
- Executing the order finding algorithm on real IBM Quantum hardware and simulators.
- Processing results to estimate the order using continued fractions.

## 📖 Theory

The order finding algorithm is a central part of Shor's algorithm, which enables efficient integer factorization using quantum computers. The notebook includes:
- Construction of modular multiplication gates
- Implementation of the quantum Fourier transform (QFT)
- Use of continued fractions to estimate the order from quantum measurements

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

3. Open and run the notebook `0_sampler.ipynb` to execute the experiments and view results.

## 📒 Notebook Structure

The notebook is organized as follows:
1. **Imports and Setup**: Loads libraries, environment variables, and IBM Quantum credentials.
2. **Basic Quantum Experiments**: Runs simple circuits and visualizes results using improved histograms.
3. **Backend Information**: Lists available IBM Quantum backends and their qubit counts.
4. **Order Finding Algorithm**:
   - Implements modular multiplication gates
   - Defines the order finding circuit
   - Executes the algorithm on both simulators and real hardware
   - Processes results to estimate the order
5. **References**: Links to IBM Quantum documentation and resources.

## 🔗 References

- [IBM Quantum Platform](https://quantum.cloud.ibm.com/instances)
- [Qiskit IBM Runtime Documentation](https://quantum.cloud.ibm.com/docs/en/api/qiskit-ibm-runtime/ibm-backend)

## 👥 Authors

- [João Vitor Choueri Branco](https://www.linkedin.com/in/jo%C3%A3o-vitor-choueri-branco-a756ab209)
- [Vitor Guirão Soller](https://www.linkedin.com/in/vitor-soller)

## 🧠 Advisor

- [Prof. Dr. Sandro Martini](https://www.linkedin.com/in/profsandromartini1972)
