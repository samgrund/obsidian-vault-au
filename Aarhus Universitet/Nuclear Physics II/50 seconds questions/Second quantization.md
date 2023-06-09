The second quantization formalism is an approach to the problem of describing and acting on quantum mechanical states containing identical particles. The states themselves live in $n$-particle "Fock" states that corresponds to some total occupation number, where each vector element $n_i$ corresponds to the occupation number of state $i$
$$
\ket{\vec{n}} =\ket{n_0,n_1,...n_j} \in \text{Fock space}
$$
The benefit of this notation that it is way more compact than keeping track of the state ket of every particle individually, which anyway is somewhat meaningless as they are indistinguishable.

A second benefit of the second quantization formalism is that the symmetrization properties of a state of e.g. fermions are not embedded in the state itself but rather on the operators acting on the state. This is not so as to say that the states are not (anti)-symmetrized, but instead of having large sums of individual product states to obey the corresponding symmetrization, we now have a neat notation where we can just state its symmetrization. The operators acting on these states (i.e. the creation and annihilation operators $\hat{a}^\dagger$ and $\hat{a}$) must then act in accordance with the symmetrization properties. These operator properties are captured in the (anti)commuation relations:
$$
[a_i^\dagger,a_j^\dagger] = [a_i,a_j] = 0, \hspace{.3cm} [a_i,a_j^\dagger] = \delta_{ij} \hspace{.5cm}\text{(Bosons)}
$$
$$
\{a_i^\dagger,a_j^\dagger\} = \{a_i,a_i\} = 0, \hspace{.3cm}\{a_i,a_j^\dagger \} = \delta_{ij} \hspace{.5cm}\text{(Fermions)}
$$
You can derive these if you want to. I do not:)

**Note**: By symmetrization properties of a state I of essentially mean the eigenvalue of the permutation operator, i.e.
$$
P_{12}\ket{n} = -\ket{n} \hspace{.5cm} \text{(Fermions)}
$$
$$
P_{12}\ket{n} = \ket{n} \hspace{.5cm} \text{(Bosons)}
$$
In fact the antisymmetrical property of the fermion state leads directly to the Fermi exclusion principle.