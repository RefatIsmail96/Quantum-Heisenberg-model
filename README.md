# Quantum Simulation of the Heisenberg model

This project was done in collaboration with [Debarghya Chakraborty](https://pa.as.uky.edu/users/dch269) and [Nikolaos Angelinos](https://pa.as.uky.edu/users/nan236) as part of our participation in IBM's [Open Science Prize 2021](https://github.com/qiskit-community/open-science-prize-2021). The goal of the competition was to improve the fidelity of simulating the 3-qubit Heisenberg model on IBM's quantum processor, Jakarta. 
By employing trotterization, error mitigation techniques, and efficient block-diagonalization of the Hamiltonian, we achieved a fidelity of approximately 99% in the final state compared to the ideal evolution.

Our implemented quantum circuit evolves the initial $3$-qubit state $|110\rangle$, for time from $t=0$ to $t=\pi$, according to the Hamiltonian
```math
H= X_1 X_{2} + Y_1 Y_2 +Z_{1}Z_{2}  + X_{2} X_{3} + Y_2 Y_3 + Z_{2}Z_{3},
```
where indices (1,2,3) correspond to qubits 5, 3 and 1 on ibmq_jakarta. Our submission managed to implement the quantum circuit using only 2 CNOT gates, achieving the $99$% fidelity.
