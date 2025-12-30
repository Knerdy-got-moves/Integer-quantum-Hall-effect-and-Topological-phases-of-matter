# Quantum Spin Hall (QSH) and Chern Insulators

This directory contains research-level derivations and course notes from **Mesoscopic Physics** (taught by **Prof. Colin Benjamin**) regarding the physics of Chern insulators and the Quantum Spin Hall effect.

---

## Folder Navigation

### 1. [Quantum Spin Hall and Chern Insulator](https://github.com/Knerdy-got-moves/Quantum-Hall-effect-physics-and-Topological-insulators/blob/main/QSHI%20and%20Chern%20insulators/Quantum%20Spin%20Hall%20Insulator%20and%20Chern%20Insulator.pdf)
* **Motivation:** To construct a realistic 2D Hamiltonian for insulators that break or preserve time-reversal symmetry (TRS) and study their topological phases.
* **Key Highlights:** * Hamiltonian $\hat{h}_k$ near Dirac points and the role of mass parameters $\Delta$ and $B$.
    * Distinguishing between topologically trivial and non-trivial phases based on the sign of $B\Delta$.
    * Derivation of edge mode velocities and the effect of asymmetric vs. symmetric hole/particle energy.
* **Conclusion:** The topology of the system is fundamentally linked to the "winding" of the $\vec{d}_k$ vector in momentum space.

### 2. [Chiral vs QSH Insulators (Assignment 12)](https://github.com/Knerdy-got-moves/Quantum-Hall-effect-physics-and-Topological-insulators/blob/main/QSHI%20and%20Chern%20insulators/Chiral%20vs%20Quantum%20spin%20Hall%20insuators.pdf)
* **Motivation:** A comparative study of edge modes and topological invariants using polar coordinates to simplify Berry phase calculations.
* **Key Highlights:** * Derivation of the edge mode energy: $E(k) = -sgn(m) \hbar v k$.
    * Calculation of Berry connection components and the resulting Berry phase $\gamma_s = -\pi(1 - su_z)$.
    * Application of the Unitary transformation $U$ to map the BHZ Hamiltonian into a Time Reversal Symmetric (TRS) form.
* **Conclusion:** The $Z_2$ invariant is identified as the difference between spin-up and spin-down Berry curvatures.

### 3. [Application of Berry Curvature and QSHE](https://github.com/Knerdy-got-moves/Quantum-Hall-effect-physics-and-Topological-insulators/blob/main/QSHI%20and%20Chern%20insulators/Application%20of%20Berry%20curvature%20and%20QSHE.pdf)
* **Motivation:** Connecting the abstract geometry of Berry curvature to measurable physical quantities like conductance.
* **Key Highlights:** * Relation of Hall conductivity $\sigma_{xy}$ to the Chern number $C$ via the Kubo formula.
    * Discussion of the Kane-Mele model for graphene and the BHZ prediction for HgTe quantum wells.
    * Interface Physics: Demonstrating how opposite mass terms $M(x)$ across an interface lead to zero-energy bound states localized at $x=0$.
* **Conclusion:** Topological protection arises from the inversion of mass terms, a concept central to the Jackiw-Rebbi model.

### 4. [Transport in Chiral vs Helical Mode (Assignment 13)](https://github.com/Knerdy-got-moves/Quantum-Hall-effect-physics-and-Topological-insulators/blob/main/QSHI%20and%20Chern%20insulators/Transport%20in%20Chiral%20vs%20Helical%20mode.pdf)
* **Motivation:** To simulate and calculate the actual current flow in multi-terminal devices for both the Quantum Hall (QHE) and Quantum Spin Hall (QSHE) regimes.
* **Key Highlights:** * Implementation of the Landauer-Büttiker formula for chiral (unidirectional) vs. helical (spin-momentum locked) modes.
    * Derivation of Hall resistance $R_H$ and spin current $I^S$.
    * Comparison of 4-terminal resistance measurements ($R_{14,14}$ and $R_{14,23}$) for both setups.
* **Conclusion:** Helical edge modes allow for the transport of a pure spin current even in the absence of a net charge current.

---

## Technical Summary Table

| Property | Chern Insulator | Quantum Spin Hall (QSH) |
| :--- | :--- | :--- |
| **Edge Modes** | Chiral (One direction per edge) | Helical (Spin-momentum locked) |
| **Symmetry** | Breaks Time Reversal (TRS) | Preserves Time Reversal (TRS) |
| **Invariant** | Chern Number ($C$) | $Z_2$ Invariant |
| **Transport** | Quantized Charge Conductance | Quantized Spin Conductance |
| **Realization** | Haldane Model / Magnetic Dopants | Kane-Mele / BHZ Model |

---
**Course:** Mesoscopic Physics  
**Lecturer:** Prof. Colin Benjamin  
**Notes by:** Rishi Paresh Joshi
