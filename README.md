# paul_allens_folio

"Let's see Paul Allen's card."

# QxQ 2023-2024 Capstone Project: Quantum encryption in Python with Quantum Key Distribution (QKD)

The work done in this capstone project was based on the BB84 protocol and inspired by the theory and code presented during the two-semester quantum
computing course from Qubit by Qubit - The Coding School. The BB84, which was developed by Bennett & Brassard in 1984, has been
studied over the weeks 9, 10 and 11.

## Description



Placeholder.


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

This project is not accepting contributions for now.

## License

[MIT](https://choosealicense.com/licenses/mit/)
