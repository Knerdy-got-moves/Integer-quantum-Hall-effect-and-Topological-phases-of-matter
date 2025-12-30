# IQHE_IAS_SRF

This folder contains the source and compiled materials for an IAS-SRF report on the **Integer Quantum Hall Effect (IQHE)** and related topological physics. The main manuscript is built from `main.tex`, which stitches together the chapter `.tex` files listed below.

## How to navigate the report

### Option A: Read the compiled report
- **Full report (PDF):** `Integer_quantum_Hall_effect_and_Topological_phases_of_matter.pdf`

### Option B: Read chapter-by-chapter
The report is organized in the exact order in `main.tex`. Each chapter below includes:
- **Navigation:** the source `.tex` file (and any existing chapter PDF, if present).
- **Motivation:** why the chapter is included.
- **Key takeaways & conclusions:** the main ideas to carry forward.

---

### 1) Perturbation Theory
- **Navigate:** `Perturbation Theory.tex`
- **Motivation:** Establishes a foundational method for handling small corrections to solvable quantum systems—essential for understanding how weak fields or potentials modify energy spectra.
- **Key takeaways & conclusions:**
  - Perturbation theory provides a controlled expansion around exactly solvable problems.
  - Small changes in Hamiltonians can shift levels and states in predictable ways, setting the stage for later Landau-level discussions.

### 2) Identical Particles
- **Navigate:** `Identical Particles.tex` (related PDF: `Quantum identical particles.pdf`)
- **Motivation:** Builds the quantum-statistical framework for electrons, emphasizing antisymmetry and fermionic behavior critical to many-body physics in IQHE.
- **Key takeaways & conclusions:**
  - Fermionic antisymmetry and Pauli exclusion dictate occupation of states.
  - Exchange symmetry has direct physical consequences for spectra and filling of Landau levels.

### 3) Adiabatic Theorem, Berry Phase, and Berry Connection
- **Navigate:** `Adiabatic theorem, Berry Phase, and Berry connection.tex`
- **Motivation:** Introduces geometric phases and adiabatic evolution, which underpin topological invariants and quantized transport.
- **Key takeaways & conclusions:**
  - Adiabatic evolution accumulates Berry phases with measurable effects.
  - Berry curvature and connections provide the geometric language used in topological classifications.

### 4) Bloch Theorem
- **Navigate:** `Bloch theorem.tex`
- **Motivation:** Connects periodic potentials to band structure, preparing the conceptual link between lattice models and topological phases.
- **Key takeaways & conclusions:**
  - Crystal periodicity leads to Bloch states and energy bands.
  - Band structure is the setting where topological invariants emerge in later chapters.

### 5) Tight Binding Model
- **Navigate:** `Tight Binding Model.tex`
- **Motivation:** Provides a concrete lattice-model framework for electronic structure, useful for understanding topological band models.
- **Key takeaways & conclusions:**
  - Tight-binding approximations capture essential hopping physics on lattices.
  - Simple lattice models offer intuition for edge states and band topology.

### 6) Classical Hall Effect
- **Navigate:** `Classical Hall Effect.tex` (related PDF: `Classical Hall effect.pdf`)
- **Motivation:** Establishes the classical baseline (Drude model and Hall response) before quantization is introduced.
- **Key takeaways & conclusions:**
  - The Hall voltage arises from Lorentz forces on charge carriers.
  - Classical transport highlights why quantum effects are surprising and significant.

### 7) Landau Levels
- **Navigate:** `Landau levels.tex` (related PDFs: `Landau levels IQHE.pdf`, `Density of states and Landau levels.pdf`)
- **Motivation:** Develops the quantization of cyclotron motion—central to the IQHE.
- **Key takeaways & conclusions:**
  - Magnetic fields quantize orbital motion into highly degenerate Landau levels.
  - The density of states becomes discrete, enabling quantized transport features.

### 8) Integer Quantum Hall Effect
- **Navigate:** `Integer Quantum Hall Effect.tex` (related PDF: `Intro to IQHE.pdf`)
- **Motivation:** Synthesizes prior concepts to explain quantized Hall conductance, robustness to disorder, and topological interpretation.
- **Key takeaways & conclusions:**
  - Hall conductance is quantized in integer multiples of \(e^2/h\).
  - Robustness arises from topological invariants and localized bulk states with conducting edges.
  - The IQHE exemplifies a topological phase insensitive to smooth perturbations.

---

## Helpful supporting visuals
Several standalone figures and PDFs provide additional intuition:
- `Classical vs Quantum Hall effect.pdf`
- `Edge states.pdf`
- `Localised states.pdf`
- `Confinement potential and external potentials.pdf`
- `Single particle orbitals in Landau gauge.pdf`
- `Filled states in Landau level.pdf`

## Building the report (optional)
If you want to rebuild the full PDF locally (requires LaTeX + biber):
```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```
