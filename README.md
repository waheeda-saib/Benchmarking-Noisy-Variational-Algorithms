# Benchmarking Noisy Variational Algorithms for Quantum Chemistry

![Github License](https://img.shields.io/hexpm/l/plug) 

This repository was created as part of the MSc thesis at the University of Edinburgh on “The Effect of Noise on the Performance of Variational Algorithms for Quantum Chemistry”. The source code for all the benchmarking experiments implemented in this study has been made available in this repository, together with the circuit performance data and the results of each experiment presented on Jupyter notebooks.

The project goal was to view how noise changes which ansatz is the best for a quantum chemistry problem using VQE. Additionally we assess the ability of the expressibility measure to identify suitable circuits for VQE applied to a quantum chemistry use case.

## Getting Started
The software requirements needed to run the benchmarking experiments are

### Prerequisites
- Qiskit v0.23.0
- 
### Install
```console
npm install your-project
```

### Usage
Describe how you use it here.
```javascript
import { configure, useProject } from 'your-project';

configure();

const App = () => {
  const [project, setProject] = useProject();
  // ... More pseudo code here...
}
```
## Built With

This project makes use of the Qiskit SDK : https://github.com/Qiskit

## Author
- Waheeda Saib

## License

This project is licensed under the [Apache License 2.0. License](https://github.com/waheeda-saib/Benchmarking-Noisy-Variational-Algorithms/blob/main/LICENSE)
