# Quantum Hall Effect Physics and Topological Insulators

[![Physics](https://img.shields.io/badge/Physics-Condensed%20Matter-blue)](https://en.wikipedia.org/wiki/Condensed_matter_physics)
[![Topology](https://img.shields.io/badge/Topic-Topological%20Phases-green)](https://en.wikipedia.org/wiki/Topological_insulator)

**Author:** Rishi Paresh Joshi  
**Affiliation:** National Institute of Science Education and Research (NISER), Bhubaneswar  
**Period:** Summer 2023 (IAS-SRF) + Mesoscopic Physics Coursework

---

## Abstract

This repository presents a comprehensive study of **topological phases of matter**, anchored by the **Integer Quantum Hall Effect (IQHE)**. The work is organized as a two-part structure:

1. **Core Manuscript (IAS-SRF Project):** A self-contained research report that methodically builds from foundational quantum mechanics to the topological explanation of quantized Hall conductance.

2. **Extended Modules (Mesoscopic Physics Course):** A series of advanced derivations extending the IQHE concepts into transport theory, Chern/Quantum Spin Hall insulators, and graphene's anomalous quantum Hall physics.

The central thesis demonstrates that the robustness of quantized Hall plateaus emerges from **topological invariants**—mathematical quantities immune to smooth perturbations—rather than fine-tuned material properties.

---

## Table of Contents

- [Research Narrative](#research-narrative)
- [Repository Structure](#repository-structure)
- [Part I: Integer Quantum Hall Effect (IAS-SRF Project)](#part-i-integer-quantum-hall-effect-ias-srf-project)
  - [Chapter 1: Perturbation Theory](#chapter-1-perturbation-theory)
  - [Chapter 2: Identical Particles](#chapter-2-identical-particles)
  - [Chapter 3: Adiabatic Theorem, Berry Phase, and Berry Connection](#chapter-3-adiabatic-theorem-berry-phase-and-berry-connection)
  - [Chapter 4: Bloch Theorem](#chapter-4-bloch-theorem)
  - [Chapter 5: Tight Binding Model](#chapter-5-tight-binding-model)
  - [Chapter 6: Classical Hall Effect](#chapter-6-classical-hall-effect)
  - [Chapter 7: Landau Levels](#chapter-7-landau-levels)
  - [Chapter 8: Integer Quantum Hall Effect](#chapter-8-integer-quantum-hall-effect)
- [Part II: Advanced Topics (Mesoscopic Physics Course)](#part-ii-advanced-topics-mesoscopic-physics-course)
  - [Module A: Electron Transport in Mesoscopic Systems](#module-a-electron-transport-in-mesoscopic-systems)
  - [Module B: Quantum Spin Hall and Chern Insulators](#module-b-quantum-spin-hall-and-chern-insulators)
  - [Module C: Quantum Hall Effect in Graphene](#module-c-quantum-hall-effect-in-graphene)
- [Mathematical Framework](#mathematical-framework)
- [Key Results Summary](#key-results-summary)
- [Building the Documents](#building-the-documents)
- [References and Further Reading](#references-and-further-reading)

---

## Research Narrative

### The Intellectual Journey

The study of topological phases represents one of the most profound paradigm shifts in condensed matter physics. Unlike conventional phases characterized by symmetry breaking (Landau theory), topological phases are distinguished by **global mathematical invariants** that remain quantized regardless of local perturbations.

This repository documents a structured approach to understanding these concepts:

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                        METHODOLOGICAL FRAMEWORK                              │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                              │
│   FOUNDATIONS                 SOLID-STATE              QUANTUM HALL         │
│   ───────────                 ──────────               ────────────         │
│                                                                              │
│   Perturbation    ────►      Bloch         ────►      Classical Hall        │
│   Theory                     Theorem                   (Baseline)           │
│        │                         │                          │               │
│        ▼                         ▼                          ▼               │
│   Identical       ────►      Tight         ────►      Landau Levels         │
│   Particles                  Binding                   (Quantization)       │
│        │                         │                          │               │
│        ▼                         ▼                          ▼               │
│   Adiabatic       ────────────────────────────────►   INTEGER QHE           │
│   + Berry Phase                                       (Topology!)           │
│                                                                              │
└─────────────────────────────────────────────────────────────────────────────┘
```

**Why this ordering matters:**
- **Perturbation theory** provides the mathematical machinery to handle small corrections—essential for understanding how disorder affects Landau levels.
- **Identical particles** and fermionic statistics dictate how electrons populate energy levels (Pauli exclusion), directly determining the filling factor ν.
- **Berry phase/curvature** introduces the geometric language that ultimately explains why Hall conductance is quantized as a topological invariant.
- **Bloch theorem** and **tight-binding models** bridge atomic physics to band theory, setting up the momentum-space framework where topology emerges.
- **Landau levels** are the quantum mechanical signature of electrons in magnetic fields—the discrete energy spectrum that makes quantization possible.
- **IQHE** synthesizes everything: edge states carry current, bulk states localize, and the Chern number guarantees quantization.

---

## Repository Structure

```
Quantum-Hall-effect-physics-and-Topological-insulators/
│
├── IQHE_IAS_SRF/                          # Main Research Project
│   ├── main.tex                           # Master LaTeX file
│   ├── Integer_quantum_Hall_effect_and_Topological_phases_of_matter.pdf
│   ├── InternshipREADME.md                # Project-specific navigation
│   │
│   ├── Perturbation Theory.tex            # Chapter 1
│   ├── Identical Particles.tex            # Chapter 2
│   ├── Adiabatic theorem, Berry Phase, and Berry connection.tex  # Chapter 3
│   ├── Bloch theorem.tex                  # Chapter 4
│   ├── Tight Binding Model.tex            # Chapter 5
│   ├── Classical Hall Effect.tex          # Chapter 6
│   ├── Landau levels.tex                  # Chapter 7
│   ├── Integer Quantum Hall Effect.tex    # Chapter 8
│   │
│   └── [Supporting figures and PDFs]
│
├── Electron transport in mesoscopic systems/   # Module A
│   ├── TransportREADME.md
│   └── [Derivation PDFs]
│
├── QSHI and Chern insulators/                  # Module B
│   ├── QSHIREADME.md
│   └── [Derivation PDFs]
│
├── QHE in Graphene/                            # Module C
│   ├── GrapheneREADME.md
│   └── [Derivation PDFs]
│
└── README.md                              # This file
```

---

## Part I: Integer Quantum Hall Effect (IAS-SRF Project)

> **Guide:** Ajit C. Balram, IMSc, Chennai

> **Project:** Indian Academy of Sciences Summer Research Fellowship (2023)

> **Full Report:** [`IQHE_IAS_SRF/Integer_quantum_Hall_effect_and_Topological_phases_of_matter.pdf`](IQHE_IAS_SRF/Integer_quantum_Hall_effect_and_Topological_phases_of_matter.pdf)

### Chapter 1: Perturbation Theory

**Source:** [`IQHE_IAS_SRF/Perturbation Theory.tex`](IQHE_IAS_SRF/Perturbation%20Theory.tex)

#### Motivation

Many physically interesting quantum systems—including electrons in disordered potentials or magnetic fields with small corrections—do not admit exact solutions. Perturbation theory provides a systematic expansion around solvable Hamiltonians, treating additional terms as small corrections. This mathematical framework is indispensable for understanding:

- How Landau levels shift under weak electric fields
- The role of disorder in creating localized states
- Energy corrections that lift degeneracies

#### Core Formalism

Given an exactly solvable Hamiltonian H⁰ with known eigenstates |ψₙ⁰⟩ and eigenvalues Eₙ⁰:

```
H⁰|ψₙ⁰⟩ = Eₙ⁰|ψₙ⁰⟩
```

When a small perturbation H' is added, the corrected energies and states expand as:

```
Eₙ = Eₙ⁰ + Eₙ¹ + Eₙ² + ...
|ψₙ⟩ = |ψₙ⁰⟩ + |ψₙ¹⟩ + |ψₙ²⟩ + ...
```

**First-order energy correction:**
```
Eₙ¹ = ⟨ψₙ⁰|H'|ψₙ⁰⟩
```

**First-order state correction:**
```
|ψₙ¹⟩ = Σⱼ≠ₙ [⟨ψⱼ⁰|H'|ψₙ⁰⟩ / (Eₙ⁰ - Eⱼ⁰)] |ψⱼ⁰⟩
```

#### Key Insight for IQHE

The validity condition—that the perturbation must not change the Hilbert space structure—has profound implications. In the IQHE context, disorder potentials V_dis that satisfy V_dis ≪ ℏω_B (the cyclotron energy) can be treated perturbatively. This explains why Landau level structure survives weak disorder, with perturbative mixing creating localized states in the "tails" while extended states persist at level centers.

---

### Chapter 2: Identical Particles

**Source:** [`IQHE_IAS_SRF/Identical Particles.tex`](IQHE_IAS_SRF/Identical%20Particles.tex)

#### Motivation

The IQHE occurs in systems with ~10¹¹ electrons/cm². Understanding their collective behavior requires the quantum mechanics of identical particles—specifically, how fermionic antisymmetry dictates state occupation.

#### The Exchange Degeneracy Problem

In quantum mechanics, identical particles with overlapping wavefunctions are fundamentally **indistinguishable**. Consider measuring two electrons: if we find one spin-up and one spin-down, the system could be in:
- |↑,↓⟩
- |↓,↑⟩  
- Any superposition α|↑,↓⟩ + β|↓,↑⟩

This ambiguity—**exchange degeneracy**—is resolved by the **Symmetrization Postulate**: physical states must be either totally symmetric (bosons) or totally antisymmetric (fermions).

#### The Slater Determinant

For N fermions occupying orbitals {φ₁, φ₂, ..., φₙ}, the antisymmetric wavefunction is:

```
Ψ(1,2,...,N) = (1/√N!) |φ₁(1)  φ₂(1)  ...  φₙ(1)|
                       |φ₁(2)  φ₂(2)  ...  φₙ(2)|
                       |  ⋮      ⋮     ⋱    ⋮   |
                       |φ₁(N)  φ₂(N)  ...  φₙ(N)|
```

The determinant structure automatically enforces:
1. **Antisymmetry:** Exchanging any two particles flips the sign
2. **Pauli Exclusion:** Two identical rows (same state) make the determinant zero

#### Relevance to IQHE

The **filling factor** ν = ρ/(B/φ₀) counts how many Landau levels are completely filled. Pauli exclusion ensures each level holds exactly one electron per flux quantum, and the quantized plateaus at σ_xy = νe²/h correspond to integer numbers of filled levels.

---

### Chapter 3: Adiabatic Theorem, Berry Phase, and Berry Connection

**Source:** [`IQHE_IAS_SRF/Adiabatic theorem, Berry Phase, and Berry connection.tex`](IQHE_IAS_SRF/Adiabatic%20theorem,%20Berry%20Phase,%20and%20Berry%20connection.tex)

#### Motivation

This chapter introduces the **geometric/topological language** that ultimately explains IQHE quantization. Just as a Foucault pendulum accumulates a geometric phase when transported around Earth, quantum states acquire **Berry phases** during adiabatic evolution—phases that depend only on the path geometry, not the speed of traversal.

#### The Adiabatic Theorem

For a slowly-varying Hamiltonian H(t), if the system starts in an eigenstate |n(0)⟩, it remains in the instantaneous eigenstate |n(t)⟩ (up to phases):

```
|ψₙ(t_f)⟩ = exp[-i/ℏ ∫₀^t E(t')dt'] · exp[iγ] · |ψₙ(t_i)⟩
```

The first exponential is the familiar **dynamical phase**. The second is the **geometric (Berry) phase**:

```
γ = i ∫₀^t ⟨ψₙ(t')|∂/∂t'|ψₙ(t')⟩ dt'
```

#### Berry Connection and Curvature

For parameters R = (R₁, R₂, ...), the Berry connection is:

```
𝒜ₙ(R) = i⟨n(R)|∇_R|n(R)⟩
```

And the Berry curvature (the "curl" of the connection):

```
Ω(R) = ∇_R × 𝒜ₙ(R)
```

The Berry phase around a closed loop C is:

```
γₙ[C] = ∮_C 𝒜ₙ(R) · dR = ∬_S Ω(R) · dS
```

#### Toy Model: Spin in a Rotating Field

The chapter develops an illuminating example: a spin-1/2 particle in a magnetic field whose direction traces a closed path on the unit sphere. The accumulated Berry phase equals:

```
γ = -s × (solid angle enclosed)
```

For s = 1/2, this gives γ = -(1/2)×Ω, where Ω is the solid angle. The Berry curvature acts as a **magnetic monopole** at the sphere's center—a geometric object with no classical analog.

#### Connection to IQHE

When the parameter space is **momentum space** (k_x, k_y), the integral of Berry curvature over the Brillouin zone yields the **Chern number**:

```
C = (1/2π) ∫_{BZ} Ω(k) d²k
```

This integer topological invariant directly determines the quantized Hall conductance: **σ_xy = Ce²/h**.

---

### Chapter 4: Bloch Theorem

**Source:** [`IQHE_IAS_SRF/Bloch theorem.tex`](IQHE_IAS_SRF/Bloch%20theorem.tex)

#### Motivation

Real materials have periodic atomic arrangements. Bloch's theorem explains how this periodicity constrains electronic wavefunctions, leading to the **band structure** framework where topological invariants naturally emerge.

#### Statement of the Theorem

For electrons in a periodic potential U(r) = U(r + R) where R is any lattice vector:

> Energy eigenstates can be chosen as **Bloch states**:
> ```
> ψₖ(r) = e^{ik·r} uₖ(r)
> ```
> where uₖ(r) has the lattice periodicity: uₖ(r) = uₖ(r + R)

#### Proof Sketch

1. **Translation operators** T̂_R commute with each other and with H
2. Simultaneous eigenstates exist for H and all T̂_R
3. Translation eigenvalues must satisfy: λ_{R₁}λ_{R₂} = λ_{R₁+R₂}
4. Normalization requires |λ_R|² = 1, so λ_R = e^{ik·R}
5. This forces the Bloch form ψₖ(r) = e^{ik·r}uₖ(r)

#### Significance

Bloch states are labeled by crystal momentum **k**, which lives in the **Brillouin zone** (a topologically non-trivial space—a torus in 2D). The Berry connection defined on this momentum space, 𝒜ₖ = i⟨uₖ|∇ₖ|uₖ⟩, yields the Chern number when integrated.

---

### Chapter 5: Tight Binding Model

**Source:** [`IQHE_IAS_SRF/Tight Binding Model.tex`](IQHE_IAS_SRF/Tight%20Binding%20Model.tex)

#### Motivation

The tight-binding model provides a concrete, computationally tractable framework for band structure calculations. It approximates crystal wavefunctions as superpositions of atomic orbitals, making explicit the hopping processes that determine band topology.

#### Formulation

Starting from atomic orbitals φₘ(r) localized at each site Rₙ:

```
ψₘ(r) = Σₙ bₘ(Rₙ) φₘ(r - Rₙ)
```

Bloch's theorem constrains the coefficients:
```
bₘ(Rₗ) = e^{ik·Rₗ} bₘ(0)
```

The energy bands become:

```
εₘ(k) = Eₘ - [βₘ + Σ_{Rₙ≠0} γₘ(Rₙ)e^{ik·Rₙ}] / [1 + Σ_{Rₙ≠0} αₘ(Rₙ)e^{ik·Rₙ}]
```

where:
- **βₘ** = on-site energy shift from neighboring potentials
- **γₘ(Rₙ)** = hopping integrals (inter-atomic matrix elements)
- **αₘ(Rₙ)** = overlap integrals

#### Role in Topological Physics

The tight-binding framework is the starting point for models like:
- **Haldane model** (Chern insulator on honeycomb lattice)
- **Kane-Mele model** (quantum spin Hall in graphene)
- **BHZ model** (HgTe quantum wells)

By engineering hopping terms, one can create systems with non-zero Chern numbers without external magnetic fields.

---

### Chapter 6: Classical Hall Effect

**Source:** [`IQHE_IAS_SRF/Classical Hall Effect.tex`](IQHE_IAS_SRF/Classical%20Hall%20Effect.tex)

#### Motivation

Before understanding what's "quantum" about the quantum Hall effect, we must establish the classical baseline. Edwin Hall's 1879 discovery—that a transverse voltage develops across a current-carrying conductor in a perpendicular magnetic field—is explained purely by the Lorentz force.

#### Drude Model Derivation

The equation of motion for electrons with drift velocity v:

```
m(dv/dt) = -eE - e(v × B) - mv/τ
```

At equilibrium (steady state), the resistivity tensor becomes:

```
ρ = (m/Ne²τ) [  1       ωcτ  ]
              [-ωcτ      1   ]
```

where ωc = eB/m is the cyclotron frequency.

This yields:
- **Longitudinal resistivity:** ρ_xx = m/(Ne²τ) (constant, independent of B)
- **Hall resistivity:** ρ_xy = B/(Ne) (linear in B)

#### The Quantum Surprise

Classically, ρ_xy varies smoothly and linearly with B. The IQHE reveals something dramatically different: **plateaus** at ρ_xy = h/(νe²) separated by sharp transitions, with ρ_xx vanishing on plateaus and spiking at transitions. This quantization, robust to ~1 part in 10⁹, signals fundamentally quantum mechanical physics.

---

### Chapter 7: Landau Levels

**Source:** [`IQHE_IAS_SRF/Landau levels.tex`](IQHE_IAS_SRF/Landau%20levels.tex)

#### Motivation

The quantization of electron motion in magnetic fields—into discrete **Landau levels**—is the essential quantum ingredient for IQHE. This chapter solves the problem exactly in two gauge choices, revealing the massive degeneracy that enables topological physics.

#### Hamiltonian and Magnetic Length

For an electron in 2D with perpendicular field B:

```
H = (1/2m)(p + eA)²
```

The natural length scale is the **magnetic length**:

```
ℓ_B = √(ℏc/eB) ≈ 26 nm / √(B[Tesla])
```

#### Landau Gauge Solution

Choosing A = B(-y, 0, 0), the Hamiltonian separates:

```
H → ℏωc[½y'² + ½p_y'²]  (1D harmonic oscillator!)
```

**Energy eigenvalues:**
```
Eₙ = (n + ½)ℏωc,    n = 0, 1, 2, ...
```

**Wavefunctions:**
```
ηₙ,kₓ(r) ∝ e^{ikₓx} · exp[-(y - kₓℓ²)²/2ℓ²] · Hₙ[(y - kₓℓ²)/ℓ]
```

Key features:
- Energy depends only on n, not on kₓ → **massive degeneracy**
- Each state is a Gaussian strip of width ~ℓ_B, centered at y = kₓℓ²_B
- Different kₓ values give spatially separated strips

#### Symmetric Gauge Solution

Choosing A = (B/2)(-y, x, 0), the problem has rotational symmetry:

```
ηₙ,ₘ(r) ∝ z^m · L_n^m(r²/2ℓ²) · e^{-r²/4ℓ²}
```

where z = x - iy and L_n^m are associated Laguerre polynomials.

#### Degeneracy and Filling Factor

The degeneracy per unit area equals:

```
G = 1/(2πℓ²_B) = B/φ₀ = eB/h
```

**One state per flux quantum φ₀ = h/e.**

The **filling factor** ν = ρ/G tells us how many Landau levels are occupied:
- ν = 1: Lowest Landau level exactly filled
- ν = 2: Two levels filled
- Non-integer ν: Partially filled levels

---

### Chapter 8: Integer Quantum Hall Effect

**Source:** [`IQHE_IAS_SRF/Integer Quantum Hall Effect.tex`](IQHE_IAS_SRF/Integer%20Quantum%20Hall%20Effect.tex)

#### Motivation

This chapter synthesizes all preceding material to explain the remarkable experimental observation: Hall resistivity locked at ρ_xy = (h/e²)(1/ν) over finite ranges of magnetic field, with ν an integer.

#### Landau Levels with Electric Field

Adding a longitudinal electric field E shifts the harmonic oscillator center and lifts degeneracy:

```
E_{n,k} = (n + ½)ℏωc - eE(kℓ²_B + eE/mω²_c) + (m/2)(E/B)²
```

The group velocity becomes:
```
v_y = (1/ℏ)(∂E/∂k) = -E/B
```

This is the classical **E×B drift**—cyclotron orbits drift perpendicular to both fields.

#### Edge States and Chiral Transport

Real samples have boundaries where the confining potential rises steeply. Near edges:

```
v_y = -(1/eB)(∂V/∂x)
```

- **Left edge:** ∂V/∂x > 0 → v_y < 0 (downward)
- **Right edge:** ∂V/∂x < 0 → v_y > 0 (upward)

Electrons on opposite edges travel in **opposite directions**—this is **chiral** transport. The bulk states are stationary (flat potential), while edge states carry all the current.

#### Current Calculation

The Hall current from edge states:

```
I_y = (e/2πℏ)[V(right edge) - V(left edge)] = (e²/h)V_H
```

For ν filled Landau levels:

```
I_y = ν(e²/h)V_H  →  ρ_xy = h/(νe²)
```

**The quantization emerges from counting filled edge channels!**

#### The Role of Disorder

Why do plateaus persist over ranges of B? The answer lies in **disorder**:

1. Disorder creates a random potential landscape with peaks and troughs
2. Electrons in the bulk become **localized**—trapped in closed orbits around potential extrema
3. **Extended states** survive only at Landau level centers
4. **Edge states** remain delocalized—chiral motion prevents backscattering

As B changes and degeneracy shifts:
- Electrons enter/exit localized states (no current contribution)
- Extended edge channels remain unchanged
- **Conductance stays quantized until the next level empties/fills**

#### Summary of IQHE Physics

| Feature | Physical Origin |
|---------|-----------------|
| Quantized ρ_xy | Integer Chern number × e²/h |
| Vanishing ρ_xx | No backscattering in chiral edge modes |
| Plateau width | Localized bulk states from disorder |
| Precision (~10⁻⁹) | Topological protection |

---

## Part II: Advanced Topics (Mesoscopic Physics Course)

> **Course:** Mesoscopic Physics  
> **Instructor:** Prof. Colin Benjamin  
> **Notes by:** Rishi Paresh Joshi

These modules extend the IQHE concepts to broader contexts in mesoscopic and topological physics.

---

### Module A: Electron Transport in Mesoscopic Systems

**Directory:** [`Electron transport in mesoscopic systems/`](Electron%20transport%20in%20mesoscopic%20systems/)  
**README:** [`TransportREADME.md`](Electron%20transport%20in%20mesoscopic%20systems/TransportREADME.md)

#### From Kubo Formula to TKNN

This derivation connects linear response theory to the topological formula for Hall conductivity:

**Kubo formula** (linear response):
```
σ_xy = (iℏ/A) Σₙ≠ₘ [f(Eₙ) - f(Eₘ)] × ⟨n|v̂_x|m⟩⟨m|v̂_y|n⟩ / (Eₙ - Eₘ)²
```

**TKNN formula** (topological):
```
σ_xy = (e²/h) × (1/2π) ∫_{BZ} d²k [∇_k × A_k]_z = (e²/h) × C
```

The Chern number C is a topological invariant—it cannot change under smooth deformations of the Hamiltonian, explaining the robustness of quantization.

#### Landauer-Büttiker Formalism

For multi-terminal devices, current at probe p:

```
I_p = (2e²/h) Σ_{q≠p} [T_{qp}V_p - T_{pq}V_q]
```

where T_{pq} is the transmission probability from q to p.

**Key Results:**
- Quantized conductance steps: G = (2e²/h)N for N channels
- Four-terminal resistance: R_{4T} = (h/2e²) × Σ(1-Tₙ)/ΣTₙ

---

### Module B: Quantum Spin Hall and Chern Insulators

**Directory:** [`QSHI and Chern insulators/`](QSHI%20and%20Chern%20insulators/)  
**README:** [`QSHIREADME.md`](QSHI%20and%20Chern%20insulators/QSHIREADME.md)

#### Overview

This module explores topological phases that exist **without external magnetic fields**:

| Property | Chern Insulator | QSH Insulator |
|----------|-----------------|---------------|
| Time Reversal | Broken | Preserved |
| Edge Modes | Chiral (one direction) | Helical (spin-momentum locked) |
| Invariant | Chern number C ∈ ℤ | Z₂ ∈ {0,1} |
| Realization | Haldane model | Kane-Mele, BHZ |

#### Key Topics Covered

1. **2D Dirac Hamiltonians** with mass terms that determine topology
2. **Berry curvature calculations** from eigenvector geometry
3. **Edge state derivation** via domain wall (Jackiw-Rebbi) physics
4. **Transport signatures** distinguishing chiral from helical modes:
   - Chiral: Charge current, no spin current
   - Helical: Pure spin current possible

---

### Module C: Quantum Hall Effect in Graphene

**Directory:** [`QHE in Graphene/`](QHE%20in%20Graphene/)  
**README:** [`GrapheneREADME.md`](QHE%20in%20Graphene/GrapheneREADME.md)

#### Why Graphene is Special

Graphene's honeycomb lattice creates **Dirac fermions** at low energies:

```
H = ℏv_F(σ_x k_x + σ_y k_y)
```

This leads to distinctive physics:

| Property | Standard 2DEG | Graphene |
|----------|---------------|----------|
| Dispersion | Parabolic (E ∝ k²) | Linear (E ∝ k) |
| Effective mass | m* ≠ 0 | Massless |
| Berry phase | 0 | π |
| LL spectrum | Eₙ ∝ (n + ½) | Eₙ ∝ √n |
| Hall quantization | νe²/h | (4n + 2)e²/h |

#### Key Derivations

1. **Tight-binding to Dirac**: Expanding near K/K' points
2. **Berry phase = π**: Calculated from spinor eigenvectors
3. **Anomalous Landau levels**: E_n = sgn(n)v_F√(2eℏB|n|)
4. **Zero-energy LL**: Shared by electrons and holes, giving "half-integer" shift
5. **Klein tunneling**: Perfect transmission through barriers (from π Berry phase)

---

## Mathematical Framework

### Key Equations Reference

| Concept | Formula |
|---------|---------|
| Magnetic length | ℓ_B = √(ℏ/eB) |
| Flux quantum | φ₀ = h/e |
| Cyclotron frequency | ω_c = eB/m |
| Landau level energy | E_n = (n + ½)ℏω_c |
| Degeneracy per area | G = eB/h |
| Filling factor | ν = ρ × h/eB |
| Hall conductivity | σ_xy = νe²/h |
| Hall resistivity | ρ_xy = h/νe² |
| Berry connection | A_k = i⟨u_k|∇_k|u_k⟩ |
| Berry curvature | Ω_k = ∇_k × A_k |
| Chern number | C = (1/2π)∫_{BZ} Ω_k d²k |

### Physical Constants (CGS)

| Symbol | Value | Description |
|--------|-------|-------------|
| e | 1.6 × 10⁻¹⁹ C | Electron charge |
| ℏ | 1.05 × 10⁻³⁴ J·s | Reduced Planck constant |
| h/e² | 25.8 kΩ | Resistance quantum |
| φ₀ | 4.14 × 10⁻¹⁵ Wb | Flux quantum |

---

## Key Results Summary

### Part I: IQHE Manuscript

1. **Perturbation theory** provides the framework for treating disorder as a small correction to Landau level physics

2. **Fermionic statistics** (Pauli exclusion) determines the filling of Landau levels and defines the integer ν

3. **Berry phase geometry** introduces the Chern number—the topological invariant guaranteeing quantization

4. **Bloch theorem** establishes momentum space as the natural setting for topological band theory

5. **Landau levels** exhibit massive degeneracy: one state per flux quantum, enabling topological physics

6. **Edge states** carry current chirally; bulk states localize due to disorder—together producing quantized plateaus

### Part II: Course Modules

7. **Kubo → TKNN**: Linear response theory reveals Hall conductivity as a Chern number integral

8. **Landauer-Büttiker**: Scattering formalism quantifies conductance through transmission probabilities

9. **Chern vs. QSH insulators**: Time-reversal symmetry distinguishes chiral from helical edge transport

10. **Graphene QHE**: Dirac physics produces anomalous "half-integer" quantization from π Berry phase

---

## Building the Documents

### Prerequisites

- LaTeX distribution (TeX Live or MiKTeX)
- Biber (for bibliography)

### Compiling the Main Report

```bash
cd IQHE_IAS_SRF/
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

The compiled report will be: `Integer_quantum_Hall_effect_and_Topological_phases_of_matter.pdf`

---

## References and Further Reading

### Textbooks

- **Jain, J.K.** *Composite Fermions* (Cambridge, 2007) — Comprehensive QHE treatment
- **Tong, D.** *Lectures on the Quantum Hall Effect* (arXiv:1606.06687) — Excellent pedagogical notes
- **Griffiths, D.J.** *Introduction to Quantum Mechanics* — Perturbation theory and basics
- **Auerbach, A.** *Interacting Electrons and Quantum Magnetism* — Berry phase applications
- **Marder, M.P.** *Condensed Matter Physics* — Band theory and tight-binding

### Original Papers

- **Klitzing, K. v., Dorda, G., & Pepper, M.** (1980) *New method for high-accuracy determination of the fine-structure constant based on quantized Hall resistance*. Phys. Rev. Lett. 45, 494.
- **Thouless, D.J., Kohmoto, M., Nightingale, M.P., & den Nijs, M.** (1982) *Quantized Hall conductance in a two-dimensional periodic potential*. Phys. Rev. Lett. 49, 405. (TKNN)
- **Haldane, F.D.M.** (1988) *Model for a quantum Hall effect without Landau levels*. Phys. Rev. Lett. 61, 2015.
- **Kane, C.L. & Mele, E.J.** (2005) *Quantum spin Hall effect in graphene*. Phys. Rev. Lett. 95, 226801.

---

## Acknowledgments

- **Indian Academy of Sciences** for the Summer Research Fellowship (2023)
- **Prof. Ajit C. Balram (IMSc)** for the Summer internship guidance 
- **Prof. Colin Benjamin** (NISER) for the Mesoscopic Physics course (2025)
- **NISER Bhubaneswar** for academic support and resources

---

*This repository represents a journey from foundational quantum mechanics to the frontier of topological condensed matter physics. The careful, chapter-by-chapter construction demonstrates not just knowledge of results, but understanding of the logical connections that make the Integer Quantum Hall Effect a paradigmatic example of topology in physics.*

---

**Contact:** Rishi Paresh Joshi | NISER Bhubaneswar  
**Last Updated:** 2025
