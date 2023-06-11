#scattering
> When considering quantum mechanical particles scattered by some potential, the asymptotic outgoing wave can be written as
$$
\psi(r) = e^{ikz} + f(\theta)\frac{e^{ikr}}{r},
$$
where $f(\theta)$ is the scattering amplitude (here only described by one coordinate because of the fact that there is very likely to be axial symmetry for the problem).

(From [[Scattering amplitude]])

First note that is possible to transfer from a $\ket{p}$ or equivalently $\ket{k}$ basis to a basis of spherical waves $\ket{n,\ell,m}$. This is interesting because in the case of a spherically symmetric potential the angular momentum $\ell$ is a conserved quantity in the scattering. This means that the amplitude of each partial wave is preserved and the only effect the potential can have is to apply some phase shifts $\delta_\ell$ to the incoming spherical waves.

In general we can now express the scattering amplitude based solely on this set of phase shifts for each $\ell$ wave:
$$
f(\theta) = \frac{1}{k}\sum_\ell(2\ell+1)P_\ell(\cos{\theta})e^{i\delta_\ell} \sin{\delta_{\ell}}.
$$
In other words, this set of phase shifts carry the entire information of the interaction. For a graphical interpretation of the phase shifts, see
![[Pasted image 20230609150623.png]]

Keep in mind that for low energies, basically only the $\ell=0$ (s-waves) matter because 
$$\delta_{\ell} \propto k^{2\ell+1} \propto E^{\ell + 1/2}.$$
The intuitive picture here is that high $\ell$ waves are larger and so they are too big to "probe" the potential, while lower values can feel it.

In a sense the action of the potential is to contract or expand the radial wavefunction depending on the sign of the potential. This is what causes the phase shift.