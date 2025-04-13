<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Constantine-Quantum-Tech/tqsim/refs/heads/main/images/cqtech_logo_blue.png">
  <img alt="CQTech's Logo" align="right" height="70" src="https://raw.githubusercontent.com/Constantine-Quantum-Tech/tqsim/refs/heads/main/images/cqtech_logo_blue.png">
</picture>



# Simulating The Unruh Temperature

This repository contain the jupyter notebook we used to genrate the results presented in the Quantum Simulation of the Unruh Temperature via the Thermal Properties of
Virtually Evolving Bose-Einstein Condensate paper. 
## Installation
First you need to install qutip software:

```bash
pip install qutip
```
## Usage 

1-Import the necessary packages :

```bash
import numpy as np
import matplotlib.pyplot as plt
from qutip import Qobj
from qutip import expect, tensor, qeye, sesolve, mesolve, fock, destroy, create
```
2-Follow the jupyter notebook code:
\
#### You can view the notebook here:  
👉  [Quantum simulation of Unruh Tempreature .ipynb](https://github.com/Constantine-Quantum-Tech/simulating-Unruh-temperature/blob/main/Quantum%20simulation%20of%20Unruh%20Tempreature%20.ipynb)

## Authors :
*Imad-Eddine Chorfi, Abdellah Tounsi, Mohamed Messaoud Louamri, Nacer eddine Belaloui, and Mohamed Taha Rouabah – Constantine Quantum Technologies.*

## License
Copyright © 2022, [Constantine Quantum Technologies](https://cqtech.org). Released under the [Apache License 2.0](LICENSE).
