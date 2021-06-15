# Benchmarking Noisy Variational Algorithms for Quantum Chemistry

![Github License](https://img.shields.io/hexpm/l/plug) 

This repository was created as part of a MSc thesis at the University of Edinburgh on "The Effect of Noise on the Performance of Variational Algorithms for Quantum Chemistry". The source code for all the benchmarking experiments implemented in this study has been made available in this repository, together with the circuit performance data and the results of each experiment presented on Jupyter notebooks.

The project goal was to view how noise changes which ansatz is the best for a quantum chemistry problem using VQE. Additionally we assess the ability of the expressibility measure to identify suitable circuits for VQE applied to a quantum chemistry use case.

## Getting Started

To view the results of the benchmarking experiments, each folder contains related experiments represented by Jupyter notebooks with the associated results.

The software requirements needed to run the benchmarking experiments include Python, Numpy, Pandas and Jupyter notebook that is contained in the Anaconda data science toolkit. The Qiskit SDK was used to implement our quantum experiments.

### Prerequisites

- [Anaconda](https://www.anaconda.com/products/individual) 
- [Python](https://www.python.org/), version 3.7
- [Qiskit](https://qiskit.org/documentation/getting_started.html), version 0.23.0

### Install
Once Anaconda has been downloaded and installed, the following commands may be used to update python and install qiskit.

```console
conda install python=3.7
pip   install qiskit==0.23.0 

```

## Built With

This project makes use of the Qiskit SDK : https://github.com/Qiskit

## Author
- Waheeda Saib

## License

This project is licensed under the [Apache License 2.0.](https://github.com/waheeda-saib/Benchmarking-Noisy-Variational-Algorithms/blob/main/LICENSE)
