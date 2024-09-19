# Basic Quantum Circuit Optimization and Execution
## Overview
This project demonstrates the creation, optimization, 
and execution of quantum circuits using Qiskit and IBM Quantum services. 
It includes the setup of quantum backends, circuit construction with basic quantum gates, 
and visualization of results. The project showcases how to use Qiskit’s pass manager to 
optimize circuits for specific backends and how to visualize the outcomes of quantum computations.
## Features

- **Quantum Backend Setup**: Connects to IBM Quantum’s cloud services using the `QiskitRuntimeService` and selects a specific backend for execution.
- **Circuit Construction**: Creates and optimizes quantum circuits with Hadamard, CNOT, and `ry` rotation gates, including measurement.
- **Optimization**: Utilizes Qiskit’s preset pass manager to optimize circuits for efficient execution on the chosen backend.
- **Job Submission**: Submits optimized circuits for execution and retrieves results from the quantum backend.
- **Data Visualization**: Visualizes quantum circuits and their measurement results using matplotlib and histograms.

## Getting Started

To get started with this project, follow these steps:

1. **Setup**: Ensure you have Qiskit installed and configured with access to IBM Quantum services.
2. **Backend Initialization**: Set up the backend using `QiskitRuntimeService` and select the appropriate quantum backend.
3. **Circuit Creation**: Define quantum circuits with desired gates and measurement.
4. **Optimization**: Apply the preset pass manager to optimize the circuit for the selected backend.
5. **Execution**: Run the optimized circuit and retrieve results using a sampler.
6. **Visualization**: Draw the quantum circuits and plot measurement results for analysis.

## Requirements

- Quiskit
- IBM Quantum account and API token
