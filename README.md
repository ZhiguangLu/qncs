# Quantum Correlation Solver (QCS)
QCS is an open-source Python code that allows to study the single-photon transmission and reflection, as well as the  *n*th-order equal-time correlation functions (ETCFs)
in driven-dissipative quantum systems. The documentation for the package and example notebooks can be found in the current directory.
## Applicable conditions
Here, the system needs to meet two conditions. One is that the system Hamiltonian that does't include the coherent driving part must satisfy U(1) symmetry, namely the 
total excitation number conservation. The other is that the driving strength must be small enough. Based on the two points, we could reduce the computation complexity of 
ETCFs from exponential to polynomial when the system contains multiple optical cavities, emitters, and both.

## Computable physical quantites and quantum effects in quantum optics
* Transmission and reflectance spectrums, ETCFs, cross-correlation function, and 2nd-order unequal-time correlation function.
* Photon blockade, antibunching and bunching effects.
* Dynamical photon blockade effects.
## The commonest systems
* Cavity QED system.
* Waveguide QED system.

## Installation

## Use

```python
from QuantumCorrelationSolver import QCS
# creat the effective Hamiltonian
...
Heff

```

For more details and examples on the use of *QCS* see the documentation and example folder.

<img src="https://github.com/ZhiGuangLu/Load-Figures/blob/main/Qcs.png" width="735px">

## License
QCS is licensed under the terms of the BSD license.
## Documentation

## Notebooks

## Citation

## Resources
