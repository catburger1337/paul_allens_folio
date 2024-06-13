# paul_allens_folio

"Let's see Paul Allen's card."

# QxQ 2023-2024 Capstone Project: Quantum encryption in Python with Quantum Key Distribution (QKD)

The work done in this capstone project is based on the BB84 protocol and inspired by the theory and code presented during the two-semester quantum
computing course from Qubit by Qubit - The Coding School. The BB84, which was developed by Bennett & Brassard in 1984, has been
studied over the weeks 9, 10 and 11.

## Description

Status: finished.

Quantum Key Distribution uses some principles of quantum mechanics like entanglement, measurement, no-cloning theorem and the uncertainty principle.

A sender and a receiver exchange classical messages through a quantum channel that may have the presence of an eavesdropper. The messages are encoded by a random selection of quantum states (|0>, |1> in the Z basis and |+>, |-> in the X basis). A comparision of basis and bits over a classical channel generates a secret key. If they can't agree about the string of bits they shared, then an eavesdropper tried to intercept information during the process.

Tipically, those with access to a quantum mechanics lab play with photons to produce Bell states.
Here, I'm a doing a (classical) simulation of QKD with a Python library called Cirq.


## Usage

```python

!pip install cirq --quiet
import cirq
import math
import binascii
import numpy as np
from random import choices
def binary_labels(num_qubits):
    return [bin(x)[2:].zfill(num_qubits) for x in range(2 ** num_qubits)]

```

## Functions

```python

key_size(message)
encryption()
decryption()

```

## Contributing

This project is finished.

Feel free to use the code to learn more about quantum computing. Make a copy of the [notebook](https://github.com/catburger1337/paul_allens_folio/blob/main/QxQ_Capstone_Quantum_Encrypt_QKD.ipynb), change values, variables, functions - play with it. Simulate. Find answers to your questions - challenge them! Make better answers. Will you try it, at least?

## License

Click the link to understand how a MIT license works.
[MIT](https://choosealicense.com/licenses/mit/)
