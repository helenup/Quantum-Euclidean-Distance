# Quantum-Euclidean-Distance
Quantum Euclidean Distance using Qiskit

This notebook presents the calculation of the well known Euclidean Distance in its Quantum Version using Qiskit.

First step is to encode classical data into quantum states: Amplitude embedding, angle embedding, basis embedding and so on. 
Once the data is encode, next step is to figure out how to know the distance between two quantum states (how similar they are). The metric of similarity can
be defined based on two extremes: the quantum states are the same state, or they are perfectly orthogonal.
The swap test operator expresses the overlap (inner product) of the two quantum states (|Ψ⟩, |φ〉) in terms of measurement probability of an auxiliary qubit, called ancilla, being in state |0〉. If the probability P(|0〉) = 0.5 means that the states are orthogonal, whereas the probability P(|0〉) = 1 indicates that the states are identical. The H gate is applied to the ancilla qubit (|0〉) to obtain a superposition (state 0 and 1 with equal probabilities).
