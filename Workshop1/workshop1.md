# Workshop 1 

https://docs.google.com/document/d/1xkUs3dtwMs_k7cJdNEom1Rn6uGIL7_HxfvdorTvI3mw/edit?tab=t.0 --> Qiskit Cheatsheet (download when it's completed)

### Classical vs. Quantum Information: 
- Classical Information is encoded in bits (0s and 1s). In the actual computer, this is done with transistors (0 is represented by a voltage drop). 
- Quantum Information has three new properties 
    - Superposition --> instead of the the transistors, quantum particles are used
    - Interference 
    - Entanglement --> Ex: 2 qubits are in a superposition and they are entangled. This results in correlations between measuring the state of the qubit.

### Quantum Gates
- Bloch Sphere: Location of the state along the bloch sphere shows probability of different measurements
<img src="bloch-sphere.png" width="400">
- Quantum Gates: Changes a quantum state 
- The X Gate: 180 degree rotation around the x-axis of the Bloch sphere 
- The H (Hadamard) Gate: The H gate creates a superposition
    - Applying the H gate to the |1> state creates the |-> state. 
    - 180 degree rotation around the x = z axis. 

### Ket Notation 
a|0> + be^(i*phi)|1>, phi: 0 to 2pi
a^2 + b^2 = 1

|+> = 1/sqrt(2)|0> + 1/sqrt(2)|1>
|-> = 1/sqrt(2)|0> + 1/sqrt(2)*e^i|1> = 1/sqrt(2)|0> - 1/sqrt(2)|1>