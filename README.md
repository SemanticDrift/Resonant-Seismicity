# Phase-Dependent Resonance Coupling in Earth's Layered Seismicity
**An Annex to the Earth-Moon Framework**
Series: Harmonic Structures in Natural Systems
Author: Carolina Johnson (CJ) | Date: June 2026 | License: CC BY 4.0, Attribution required
DOI: https://doi.org/10.5281/zenodo.20537965
ORCID: https://orcid.org/0009-0002-8819-3347

---

## What This Does

Derives a deterministic model for Earth's interior layer architecture and deep-focus seismicity from two observed values and zero fitted parameters. A single spatial invariant Λ = 6,960 km is calibrated to the Core-Mantle Boundary. From Λ alone, the complete interior shell ladder is computed. Deep-focus earthquakes at 41 km and 250 km are mapped to rational phase nodes and their failure mechanism is derived from the quadratic strain-rate dependence of the Φ-operator.

---

## The Problem It Solves

Standard geophysical models assign each interior layer an independent equation of state with separately calibrated empirical parameters. These are fitted zone by zone and forced into global coherence through numerical correction terms. The fitting error accumulates across boundaries and must be continuously patched.

This is Representation Drift: the cumulative divergence that results from modeling interrelated boundaries as independent systems.

UHS eliminates this by establishing Λ as a single Tier 0 foundational constraint. All interior shell radii are Tier 1 outputs of that constraint. No layer has independent parameters.

---

## The Two Observed Inputs

| Symbol | Value | Source |
|--------|-------|--------|
| Rₑ | 6,371 km | Mean Earth radius |
| r_CMB | 3,480 km | PREM (Dziewonski & Anderson, 1981) |

No other observed values enter. No parameters are fitted.

---

## The Structural Invariant

The Core-Mantle Boundary is the compositional phase inversion between silicate mantle and metallic core — a true compositional boundary, not a viscosity gradient. For a two-chamber standing wave system, the phase inversion must occur at n = 2: the unique integer partitioning the fundamental field into two symmetric structural chambers.

Λ = r_CMB × 2 = 3,480 × 2 = 6,960 km

---

## The Interior Shell Ladder

| n | rₙ (km) | Depth (km) | Boundary | Observed / Status |
|---|---------|------------|----------|-------------------|
| 2 | 3,480 | 2,891 | Core-Mantle Boundary | 3,480 km — calibration anchor |
| 11/10 = 1.1 | 6,327 | 44 | Lithospheric base | ~35–55 km — within range |
| 11/9 ≈ 1.222 | 5,695 | 676 | Upper/lower mantle transition | 660 km — 2.4% deviation |
| 4 | 1,740 | 4,631 | Mid-lower mantle transition | ~1,700–1,800 km — prediction |
| 6 | 1,160 | 5,211 | F-zone crystallization center | 1,145 km — 1.3% deviation |
| 8 | 870 | 5,501 | Innermost Inner Core (IMIC) | 650–900 km — within range |

The n = 8 node is the absolute structural closure lock for a two-chamber system (k = 2) under the Law of Admissibility: n_lock = 4k = 8.

---

## Deep-Focus Seismicity

The Φ-operator spatial derivative df/dr = −c/r² produces a required strain rate that grows as 1/r². For a descending material element:

ε̇_required ∝ c × v_r / r²

At rational phase nodes n = p/q, the material must undergo a discrete lattice phase reset over a finite crossing interval Δt:

ε̇_required ∝ Δφ / Δt

When Δt is short (rapid slab descent), the required strain rate exceeds the plastic relaxation capacity:

ε̇_required > ε̇_plastic   →   brittle failure

### Hawaiian Lithospheric Flexure (41 km)

r = 6,371 − 41 = 6,330 km
n = 6,960 / 6,330 = 1.0995 ≈ 11/10   deviation: 0.05%

### Calabrian Slab Rupture (250 km, June 2, 2026 M6.1)

r = 6,371 − 250 = 6,121 km
n = 6,960 / 6,121 = 1.13706 ≈ 8/7   deviation: 0.5%

---

## Testable Predictions

**P1.** The IMIC boundary will be observed at r = 870 ± 30 km. Current estimates: 650–900 km.

**P2.** A structural discontinuity near r = 1,740 km (depth ≈ 4,630 km) will be confirmed by long-period body wave analysis.

**P3.** Deep-focus earthquake hypocenters in subduction zones will show statistically elevated frequency at rational nodes n = p/q with small denominators relative to Λ = 6,960 km, verifiable against the ISC global earthquake catalog.

**P4.** The Λ-based shell ladder applied to Mars and Venus, scaled by their respective r_CMB values, will yield interior layer radii consistent with observed seismic and gravity profiles.

---

## Repository Contents

- `README.md` — this file
- `Resonant Seismicity.pdf` — full paper
- `index.html` — interactive web presentation

---

## Dependencies

| Framework | DOI |
|-----------|-----|
| Stratified Axiomatics | https://doi.org/10.5281/zenodo.18227024 |
| Unified Harmonic Shells (UHS) | https://doi.org/10.5281/zenodo.18307184 |
| The Law of Admissibility | https://doi.org/10.5281/zenodo.18223592 |
| Gravity as Resonance Coupling | https://doi.org/10.5281/zenodo.18624298 |
| Deriving Euler's Number from Lunar Cycles | https://doi.org/10.5281/zenodo.18363931 |
| The Phi-Operator (Λ² · Φ) | https://doi.org/10.5281/zenodo.18484603 |

Full publication list: https://www.semanticdrift.net

---

## Citation

```
Johnson, C. (2026). Phase-Dependent Resonance Coupling in Earth's Layered Seismicity:
An Annex to the Earth-Moon Framework. Series: Harmonic Structures in Natural Systems.
SemanticShift.net. DOI: 10.5281/zenodo.20537965
```
---

## License

© 2026 Carolina Johnson (CJ)
Licensed under Creative Commons Attribution 4.0 International (CC BY 4.0).
Attribution required. https://creativecommons.org/licenses/by/4.0/
