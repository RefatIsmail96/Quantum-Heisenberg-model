# Quantum-Heisenberg-model
We develop a quantum circuit that evolves the initial $3$-qubit state $|110\rangle$, for time from $t=0$ to $t=\pi$, according to the Hamiltonian
```math
H= X_1 X_{2} + Y_1 Y_2 +Z_{1}Z_{2}  + X_{2} X_{3} + Y_2 Y_3 + Z_{2}Z_{3},
```
where indices (1,2,3) correspond to qubits 5, 3 and 1 on ibmq_jakarta. We approximate the time-evolution operator by a trotterized version $U(t)\approx U_{trott}(t,n)$ where $n$ is the number of Trotter steps.
