# GNoME-derived Superconductivity: Preliminary First-Principles Validation

Independent computational-materials project by Saksham Lamichhane,
Pulchowk Campus, Tribhuvan University, Nepal.

## Project status

This repository documents an ongoing computational investigation of
GNoME-derived crystal structures as candidates for conventional
electron-phonon-mediated superconductivity.

**The candidates are hypotheses, not established superconductors.**

Current status:

- [x] GNoME structure screening (10 candidates → 4 shortlisted)
- [x] CIF recovery and structure validation
- [x] CHGNet preliminary structural relaxation
- [x] Quantum ESPRESSO SCF workflow (MgB2)
- [x] MgB2 DFPT test (diagnostic stage)
- [ ] MgB2 phonon validation (negative frequencies being investigated)
- [ ] EPW / electron-phonon coupling
- [ ] DFT validation of GNoME candidates

## Scientific question

Can selected GNoME-derived structures survive first-principles
electronic, magnetic and dynamical stability tests and exhibit
electron-phonon coupling consistent with superconductivity?

## Current primary candidate

**Gd3Re3MoRuN12** (80 atoms per unit cell)

This candidate was selected as the first computational target after
a preliminary CHGNet structural screen.

The CHGNet result is **not** interpreted as proof of thermodynamic
stability or superconductivity.

## Candidate shortlist

| Candidate | ΔE (eV/cell) | ΔV/V | Space group | Status |
|-----------|--------------|------|-------------|--------|
| Gd3Re3MoRuN12 | -0.791 | -2.60% | Ia-3 → Ia-3 | Primary |
| Gd3NbRe3RuN12 | -0.671 | -2.24% | Ia-3 → Ia-3 | Primary |
| Gd3Cr2(ReN4)3 | -0.753 | +3.02% | Ia-3d → Ia-3d | Primary |
| Gd12Nb8ZnW11N48 | -0.282 | +0.12% | I-4 → I-4 | Reserve |

## Workflow

GNoME → structure recovery → CHGNet screening → DFT relaxation
→ electronic structure → DFPT phonons → EPW / electron-phonon coupling
→ superconducting analysis

text

## Benchmark

MgB2 is used as the validation system.

The MgB2 workflow has reached SCF and DFPT calculations.
The phonon result is currently being investigated and EPW remains
under development.

## Repository structure

| Folder | Contents |
|--------|----------|
| `01_gnome_screening/` | Initial GNoME filtering and candidate selection |
| `02_structures/` | Recovered CIF files and structure manifest |
| `03_chgnet_screening/` | CHGNet relaxation results |
| `04_MgB2_benchmark/` | MgB2 benchmark (SCF, phonons, EPW) |
| `05_QE_workflow/` | Templates for QE calculations |
| `06_candidate_validation/` | DFT validation of GNoME candidates |
| `proposal/` | Scientific hosting proposal |
| `docs/` | Methods, troubleshooting, notes |

## Reproducibility

Every reported result should identify:

- software version
- input file
- pseudopotential family
- convergence parameters
- structure source
- calculation status

## Current limitations

This project has not established that any GNoME candidate is a
superconductor. The current candidate ranking is preliminary.

## License

MIT License – see [LICENSE](LICENSE) for details.

## Contact

Saksham Lamichhane – sakshamlamichhane456@gmail.com
