# Quantum Hall Effect (QHE) in Graphene

This folder contains a series of detailed derivations and class notes from the **Mesoscopic Physics** course taught by **Prof. Colin Benjamin**. These notes trace the theoretical progression from basic graphene lattice physics to the anomalous Hall quantization observed in Dirac systems.

---

## Navigation & Note Summaries
### 1. [Quantum Hall Effect in 2DEG](https://github.com/Knerdy-got-moves/Quantum-Hall-effect-physics-and-Topological-insulators/blob/main/QHE%20in%20Graphene/Quantum%20Hall%20effect%20in%202DEG.pdf)
* **Motivation:** To provide a foundational understanding of edge-state transport and the Büttiker formalism.
* **Content:** Analysis of Landau levels in a parabolic confinement potential and the formation of chiral edge modes.
* **Key Takeaways:**
    * Edge modes are robust against backscattering because counter-propagating states are spatially separated.
    * Calculation of Hall resistance $R_H$ and longitudinal resistance $R_L$ in the presence of backscattering simulation.
  
### 2. [Monolayer Graphene Hamiltonian](https://github.com/Knerdy-got-moves/Quantum-Hall-effect-physics-and-Topological-insulators/blob/main/QHE%20in%20Graphene/Monolayer%20Graphene%20Hamiltonian.pdf)
* **Motivation:** To establish the low-energy effective theory of graphene starting from its honeycomb lattice structure.
* **Content:** A tight-binding derivation using a two-atom basis (A and B sublattices) to find the energy dispersion near the Brillouin zone corners.
* **Key Takeaways:**
    * Linearization of the spectrum leads to the Dirac equation for massless fermions: $H = \hbar v_F \vec{\sigma} \cdot \vec{k}$.
    * The realization that electrons in graphene behave as ultra-relativistic particles with a constant Fermi velocity $v_F \approx 10^6 \text{ m/s}$.



### 3. [Bilayer Graphene Hamiltonian](https://github.com/Knerdy-got-moves/Quantum-Hall-effect-physics-and-Topological-insulators/blob/main/QHE%20in%20Graphene/Bilayer%20Graphene%20Hamiltonian%20.pdf)
* **Motivation:** To investigate how interlayer coupling (Bernal stacking) modifies the relativistic nature of monolayer graphene.
* **Content:** Analysis of the $A_2 - B_1$ coupling and the effective $2 \times 2$ Hamiltonian at low energies.
* **Key Takeaways:**
    * Interlayer hopping $\gamma_1$ transforms the linear dispersion into a parabolic one at low energies.
    * Despite being "massive," the fermions in bilayer graphene maintain a chiral nature, resulting in unique topological properties.

### 4. [Berry Phase and Ballistic Transport](https://github.com/Knerdy-got-moves/Quantum-Hall-effect-physics-and-Topological-insulators/blob/main/QHE%20in%20Graphene/Berry%20phase%20Ballistic%20transport%20and%20Klein%20tunneling%20in%20graphene%20(1).pdf)
* **Motivation:** To calculate the topological invariants that distinguish graphene from conventional two-dimensional systems.
* **Content:** Detailed calculation of eigenvectors, Berry connection, and Berry curvature for the Dirac Hamiltonian.
* **Key Takeaways:**
    * Derivation of the **$\pi$ Berry Phase** acquired by an electron completing a circuit around a Dirac point.
    * Confirmation that the Berry curvature is localized at the valleys, acting as a "pseudo-magnetic field" in momentum space.


### 5. [QHE in Graphene](https://github.com/Knerdy-got-moves/Quantum-Hall-effect-physics-and-Topological-insulators/blob/main/QHE%20in%20Graphene/QHE%20and%20QHE%20in%20graphene.pdf)
* **Motivation:** To derive the distinct "half-integer" Hall quantization and compare it to the standard 2DEG.
* **Content:** Solving for Landau Levels (LL) using the ladder operator method and analyzing the density of states.
* **Key Takeaways:**
    * Graphene's LLs follow a square-root dependence: $E_n = \text{sgn}(n) v_F \sqrt{2e\hbar B |n|}$.
    * The existence of a **Zero-Energy Landau Level** ($n=0$) shared by electrons and holes leads to the shifted quantization: $\sigma_{xy} = 4(n + 1/2) \frac{e^2}{h}$.




---

## Technical Glossary

| Symbol | Definition |
| :--- | :--- |
| $v_F$ | Fermi velocity ($\approx 10^6 \text{ m/s}$ in graphene). |
| $\sigma_{x,y,z}$ | Pauli spin matrices representing the sublattice (pseudospin) degree of freedom. |
| $\gamma$ | Berry phase; $\pi$ for monolayer, $2\pi$ for bilayer graphene. |
| $\vec{A}_{k}$ |berry connection; $i\langle u_k / \vec{\nabla}_k / u_k \rangle$ |
| $\Omega$ | Berry curvature; $\vec{\nabla}_k\times\vec{A}_k$ |
| $l_B$ | Magnetic length, $\sqrt{\hbar/eB}$. |
| $\nu$ | Filling factor; indicates the number of occupied Landau Levels. |
| $R_H$ | Hall resistance; $R_H = \frac{h}{e^2 \nu}$. |

---

## Comparison Table

| Property | Standard 2DEG | Monolayer Graphene |
| :--- | :--- | :--- |
| **Effective Mass** | $m^*$ | Massless (Dirac fermions) |
| **Dispersion** | Parabolic ($E \sim k^2$) | Linear ($E \sim k$) |
| **LL Energy** | $E_n \propto (n + 1/2)$ | $E_n \propto \sqrt{n}$ |
| **Berry Phase** | $0$ | $\pi$ |
| **Degeneracy** | 2 (Spin) | 4 (Spin + Valley) |

---
**Course:** Mesoscopic Physics  
**Lecturer:** Prof. Colin Benjamin  
**Notes by:** Rishi Paresh Joshi
