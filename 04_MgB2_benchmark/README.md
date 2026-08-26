# MgB2 Benchmark

Validation of the Quantum ESPRESSO workflow on the known superconductor MgB2.

## Purpose

MgB2 is used as a known superconducting material to validate the
Quantum ESPRESSO workflow before applying it to hypothetical GNoME
structures.

## Status

| Component | Status | Notes |
|-----------|--------|-------|
| SCF | [x] Completed | Converged to -130.5837 Ry |
| DFPT | [x] Diagnostic stage | Negative branches present |
| EPW | [ ] Under debugging | Not yet validated |

## Files

- `inputs/` – Input files for SCF, ph.x, and EPW
- `scripts/` – Post-processing scripts (to be added)
- `figures/` – Plots and visualizations
- `RESULTS.md` – Detailed results and analysis

## Important note

The current phonon plot contains large negative-frequency branches.
This result is not treated as a successful reproduction until the
calculation and post-processing are independently validated.
