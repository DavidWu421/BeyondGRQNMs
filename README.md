# BeyondGRQNMs
Shifts and fits to various beyond-GR quasinormal mode frequencies

## Linearized Johannsen-Psaltis QNMs
These QNM shifts are for Johannsen-Psaltis (JP) black holes [[1]](#1), linearized in the spin $\chi$ as calculated by  [[2]](#2). As such, the JP QNM frequencies linearized in spin are given by 

$$\omega_{\ell m n}
=\omega_{\ell m n}^{(0)}
+((\delta\omega_0)_{\ell n} + 
\chi m (\delta\omega_1)_{\ell n}),$$

where $\omega_{\ell m n}^{(0)}$ is the background Kerr QNM frequency. Note that due to the linearization in spin, all $m$ dependence on the QNM shifts is linear and can be pulled out. JP black holes also break QNM isospectrality but maintain definite parity, leading to both even and odd parity modes. The $\delta\omega_0$ and $\delta\omega_1$ shifts are given for $0\leq n \leq 3$, $2\leq \ell \leq 10$, all $m$, and both even and odd parity.

## Weakly Charged Kerr-Newman QNMs
These are fits to the QNM shifts for weakly charged Kerr-Newman black holes, quadratic in $Q$. These are calculated with the EVP methedology of [[3]](#3) and then fit to the form of 

$\omega_{\ell m n}=\omega^{(0)}_ {\ell m n} +Q^2 \delta\omega_{\ell m n},$

where $\delta \omega=\Omega+i \gamma$. The fits to the shift are given by

$\Omega = \sum_{j=1}^5 a_j(1-\chi^2)^{j/2}+b_j \ln \left((1-\chi^2)^{j/2}\right)$

$\gamma = \sum_{j=1}^5 c_j(1-\chi^2)^{j/2}+d_j \ln \left((1-\chi^2)^{j/2}\right)$



## References
<a id="1">[1]</a> 
T. Johannsen and D. Psaltis, Metric for rapidly spinning
black holes suitable for strong-field tests of the no-hair
theorem, Physical Review D 83, 124015 (2011).

<a id="2">[2]</a> 
D. G. Wu, A. Hussain, and A. Zimmerman, Computing spectral shifts for Johannsen-Psaltis
Black Holes (2025), arXiv:2512.14679 [gr-qc].

<a id="3">[3]</a> 
A. Hussain and A. Zimmerman, An approach to com-
puting spectral shifts for black holes beyond Kerr, Phys-
ical Review D 106, 104018 (2022), arXiv:2206.10653 [gr-
qc].
