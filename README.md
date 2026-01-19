```markdown
# Growth Strategies for Altermagnet Mn₃Ga for Spintronic Applications

## Overview

This repository documents a research project on the synthesis, phase control, and characterization of the altermagnetic material Mn₃Ga. The work focuses on preparing Mn₃Ga alloys using arc melting, followed by controlled thermal treatments to obtain cubic, tetragonal, and hexagonal phases. All descriptions, parameters, and results presented here are directly taken from the project report and presentation contained in this repository.

## Scientific Background

Altermagnetism is a class of magnetic order characterized by zero net magnetization combined with momentum-dependent spin splitting arising from broken parity–time (PT) symmetry. Mn₃Ga is a binary Heusler alloy that exhibits multiple crystallographic phases, each with distinct magnetic ordering, making it a suitable model system for studying altermagnetism and its relevance to spintronic applications.

## Objectives of the Study

The objectives of this project, as stated in the report, are:
- To establish arc-melting protocols for synthesizing Mn₃Ga.
- To study phase transformation pathways through controlled annealing.
- To characterize structural, magnetic, and transport properties of different Mn₃Ga phases.
- To classify the altermagnetic nature of each phase based on symmetry and magnetic behavior.

## Material System

- **Material:** Mn₃Ga (manganese–gallium binary alloy)  
- **Composition:** 75 at.% Mn and 25 at.% Ga  
- **Crystal structures studied:**  
  - Cubic (disordered L1₂-type)  
  - Tetragonal (D0₂₂)  
  - Hexagonal (D0₁₉, β-phase)

## Experimental Methodology

### Materials and Stoichiometry

- High-purity elemental Mn (99.999 wt.%) and Ga (99.999 wt.%) were used.
- Target stoichiometry corresponds to Mn₃Ga (75:25 at.%).
- A small excess of Ga (2–3 wt.%) was used to compensate for evaporation during melting.

### Synthesis Technique

- **Method:** Arc melting under argon atmosphere.
- **Key features:** Water-cooled copper hearth, tungsten electrode, high-vacuum chamber.
- Samples were re-melted multiple times to ensure chemical homogeneity.

![Arc-melting setup for Mn–Ga sample preparation under inert atmosphere. Adapted from Song et al., J. Appl. Phys. 131, 173903 (2022).](figures/synthesis/arc_melting_setup.png)

### Thermal Treatments

- **As-cast:** Cubic phase.
- **350–450 °C annealing:** Tetragonal D0₂₂ phase.
- **600–800 °C annealing:** Hexagonal D0₁₉ β-phase.
- The transformation to the hexagonal phase is reported as irreversible.

![Phase transformation pathways in Mn₃Ga as a function of annealing temperature and time. Adapted from Song et al., J. Appl. Phys. 131, 173903 (2022).](figures/synthesis/phase_transformation.png)

## Characterization Techniques

### Structural

- **X-ray Diffraction (XRD):** Cu Kα radiation, 2θ range 20–80°, Rietveld refinement used for lattice parameters.
- **Electron microscopy:** STEM with HAADF imaging and SAED for phase identification.

![Crystal structures of Mn₃Ga: cubic, tetragonal, and hexagonal phases. Adapted from Song et al., J. Appl. Phys. 131, 173903 (2022).](figures/crystal_structures/mn3ga_phases.png)

### Magnetic

- **Magnetometry:** MPMS (Quantum Design) and VSM (Lake Shore).
- **Temperature range:** 2–800 K.
- **Field range:** up to 70 kOe.
- **DSC:** Used to identify magnetic and structural transition temperatures.

### Transport

- **PPMS measurements:** Hall resistivity, temperature-dependent resistivity, and magnetoresistance.
- Transport measurements are reported for the hexagonal phase.

## Key Results

### Phase Formation

- As-cast samples predominantly form the cubic phase.
- Controlled annealing yields tetragonal or hexagonal phases depending on temperature.

### Structural Properties

- **Cubic phase:** Space group *Pm*3̄*m*, lattice parameter a = 3.7786 Å.
- **Tetragonal phase:** Space group *I4/mmm*, a = 3.9098 Å, c = 7.1011 Å.
- **Hexagonal β-phase:** Space group *P6₃/mmc*, a = 5.4084 Å, c = 4.3547 Å.

![XRD patterns of Mn₃Ga phases. Adapted from Song et al., J. Appl. Phys. 131, 173903 (2022).](figures/xrd/xrd_patterns.png)

### Magnetic Properties

- **Cubic:** Collinear antiferromagnetic, Néel temperature ≈ 420 K.
- **Tetragonal:** Ferrimagnetic, high perpendicular anisotropy, coercivity up to 21.4 kOe.
- **Hexagonal β-phase:** Non-collinear antiferromagnetic with 120° in-plane spin ordering and Néel temperature ≈ 490 K.

![Temperature-dependent magnetization and hysteresis behavior of Mn₃Ga phases. Adapted from Song et al., J. Appl. Phys. 131, 173903 (2022).](figures/magnetic_properties/magnetization.png)

### Altermagnetic Classification

Based on symmetry and magnetic analysis reported in the project:
- Cubic phase: S-type altermagnet.
- Tetragonal phase: M-type altermagnet.
- Hexagonal β-phase: M-type altermagnet.
All three phases are classified as strong altermagnets.

## Figures and Schematics

All figures included in this repository are either adapted from the literature cited in the report and presentation or generated as part of this project. Each figure file includes a caption indicating its source.

## Repository Structure

```

Altermagnets/
│
├── README.md
│
├── docs/
│   ├── report/
│   │   └── CP302_final_report.pdf
│   │
│   ├── presentation/
│   │   └── CP302_ppt.pdf
│   │
│   └── references/
│       ├── references.bib
│       └── references.md
│
├── figures/
│   ├── crystal_structures/
│   ├── synthesis/
│   ├── xrd/
│   ├── magnetic_properties/
│   └── transport/
│
├── data/
│   ├── xrd/
│   ├── magnetization/
│   └── transport/
│
├── notes/
│   └── experimental_log.md
│
├── LICENSE
│
└── .gitignore

```

## How to Use This Repository

- The full project report and presentation are available in the `docs/` directory.
- Figures referenced in the report are organized by category under `figures/`.
- Raw or processed datasets, where available, are stored in `data/`.
- Experimental observations and procedural notes are recorded in `notes/experimental_log.md`.
- Literature references are listed in `docs/references/` without including copyrighted full texts.

## References

A complete list of references cited in the report and presentation is provided in:
- `docs/references/references.md` (human-readable)
- `docs/references/references.bib` (BibTeX format)

Full texts of cited articles are not included due to copyright restrictions.

## Acknowledgments

This project was carried out in the Department of Physics, Indian Institute of Technology Ropar.  
Academic supervision and guidance were acknowledged in the project presentation.
```
