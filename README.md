# GNoME-derived Superconductivity: Preliminary First-Principles Validation

Independent computational-materials project by Saksham Lamichhane,
Pulchowk Campus, Tribhuvan University, Nepal.

## Project status

This repository documents an ongoing computational investigation of
GNoME-derived crystal structures as candidates for conventional
electron-phonon-mediated superconductivity.

**The candidates are hypotheses, not established superconductors.**

Current status:

- [x] GNoME structure screening
- [x] CIF recovery
- [x] CHGNet preliminary structural relaxation
- [x] Quantum ESPRESSO SCF workflow
- [x] MgB2 DFPT test
- [ ] MgB2 phonon validation (diagnostic stage)
- [ ] EPW / electron-phonon coupling
- [ ] DFT validation of GNoME candidates

## Scientific question

Can selected GNoME-derived structures survive first-principles
electronic, magnetic and dynamical stability tests and exhibit
electron-phonon coupling consistent with superconductivity?

## Current primary candidate

**Gd3Re3MoRuN12**

This candidate was selected as the first computational target after
a preliminary CHGNet structural screen.

The CHGNet result is **not** interpreted as proof of thermodynamic
stability or superconductivity.

## Workflow

GNoME → structure recovery → CHGNet screening → DFT relaxation
→ electronic structure → DFPT phonons → EPW / electron-phonon coupling
→ superconducting analysis

## Benchmark

MgB2 is used as the validation system.

The MgB2 workflow has reached SCF and DFPT calculations.
The phonon result is currently being investigated and EPW remains
under development.

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
superconductor.

The current candidate ranking is preliminary.

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

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

## Contact

Saksham Lamichhane – sakshamlamichhane456@gmail.com
