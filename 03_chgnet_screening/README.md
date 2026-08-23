# CHGNet structural screening

CHGNet variable-cell relaxation of the recovered GNoME structures.

## Files

- `chgnet_relaxation.ipynb` – Notebook used for CHGNet relaxation
- `relaxation_results.csv` – Detailed results from CHGNet
- `varcell_relax_results.csv` – Summary table of energy and volume changes
- `figures/` – Plots and visualizations

## Results summary

| Candidate | ΔE (eV/cell) | ΔV/V | Space group |
|-----------|--------------|------|-------------|
| Gd3Re3MoRuN12 | -0.791 | -2.60% | Ia-3 → Ia-3 |
| Gd3Cr2(ReN4)3 | -0.753 | +3.02% | Ia-3d → Ia-3d |
| Gd3NbRe3RuN12 | -0.671 | -2.24% | Ia-3 → Ia-3 |
| Gd12Nb8ZnW11N48 | -0.282 | +0.12% | I-4 → I-4 |

## Status

- [x] CHGNet relaxation complete for 4 candidates
- [ ] DFT validation pending

## Important note

CHGNet results are **not** DFT formation energies or stability certificates.

They are a low-cost structural pre-screen.
