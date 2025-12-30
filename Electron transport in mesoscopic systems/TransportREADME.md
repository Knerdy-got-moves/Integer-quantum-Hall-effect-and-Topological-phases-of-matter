# Quantum Hall Effect and Topological Insulators

This repository serves as a comprehensive collection of notes and derivations exploring the physics of the Quantum Hall Effect and topological phases of matter. The documentation is based on the **Mesoscopic Physics** course.

---

## Course Information
* **Course:** Mesoscopic Physics
* **Lecturer:** Prof. Colin Benjamin
* **Notes By:** Rishi Paresh Joshi

---

## Contents

### 1. From Kubo Formula to TKNN Formula
This section documents the derivation of quantized Hall conductivity by connecting linear response theory to topological invariants.

**Key Highlights:**
* **Linear Response:** Evaluating the Kubo formula in the D.C. limit ($\omega \to 0$) at zero temperature.
* **Berry Phase & Curvature:** Transitioning to momentum space using Bloch states to identify the Berry connection $\vec{A}_{\vec{k},l}$.
* **Chern Number ($C$):** Proving that the Hall conductivity is quantized as an integral of the Berry curvature over the Brillouin Zone (BZ):
  
    $$\sigma_{xy}=\frac{e^2}{h}\int_{BZ} \frac{dk_x dk_y}{(2\pi)^2} (\nabla_{\vec{k}} \times \vec{A}_{\vec{k},l})_z = \frac{e^2}{h} C$$




---

### 2. Landauer-Büttiker Formalism
This section details the scattering matrix approach to transport, focusing on transmission probabilities in multi-terminal mesoscopic devices.

**Key Highlights:**
* **Multi-probe Current:** The current at any probe $p$ is determined by the difference in chemical potentials weighted by transmission:
    $$I_p = \frac{2e^2}{h} \sum_{q \neq p} (T_{qp}V_p - T_{pq}V_q)$$
* **Sum Rules:** Demonstrating current conservation where the sum of conductances into a probe equals the sum out ($\sum_q G_{qp} = \sum_q G_{pq}$).
* **Quantized Steps:** Analysis of how gate voltage tunes the subband index $N$, resulting in conductance quantization.



---

## Glossary of Terms

| Symbol | Description |
| :--- | :--- |
| $\sigma_{xy}$ | Hall conductivity (transverse conductivity). |
| $f(E_n)$ | Fermi-Dirac distribution function at energy $E_n$. |
| $\hat{v}_{\alpha}$ | Velocity operator ($\alpha$-th component). |
| $a$ | Total area of the physical system. |
| $C$ | Chern number (topological invariant). |
| $\vec{A}_{\vec{k},l}$ | Berry connection for the $l$-th energy band. |
| $\Omega(\vec{k})$ | Berry curvature ($\vec{\nabla}_{\vec{k}} \times \vec{A}_{\vec{k},l}$). |
| $I_p$ | Net current flowing through probe $p$. |
| $V_p$ | Voltage/Potential at probe $p$. |
| $T_{pq}$ | Transmission probability from probe $q$ to probe $p$. |
| $G_{pq}$ | Conductance coefficient between probes $p$ and $q$. |
| $\mu_p$ | Chemical potential of the reservoir at contact $p$. |
| $R_H$ | Hall resistance, typically measured as $R_{13,24}$. |
| $R_{4T}$ | Intrinsic 4-terminal sample resistance (excluding contact resistance). |
| $M$ | Number of occupied subbands or transverse modes. |

---

## Summary of Key Formulas

| Concept | Equation |
| :--- | :--- |
| **Hall Conductivity** | $\sigma_{xy} = \frac{e^2}{h} C$ |
| **Büttiker Formula** | $I_p = \sum_{q \neq p} G_{pq}(V_p - V_q)$ |
| **Sample Resistance** | $R_{4T} = \frac{h}{2e^2} \frac{\sum (1-T_n)}{\sum T_n}$ |
| **Quantized Conductance** | $G_{2T} = \frac{2e^2}{h} N$ |
