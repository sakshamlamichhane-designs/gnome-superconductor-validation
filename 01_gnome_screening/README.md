# GNoME screening

Initial filtering of the GNoME dataset to identify candidate structures for superconductivity investigation.

## Files

- `gnome_screening.ipynb` – Notebook used to filter GNoME structures
- `candidate_shortlist.csv` – Final list of candidates after filtering
- `figures/` – Plots and visualizations

## Candidate selection criteria

1. Superconductivity-oriented subset from GNoME
2. Remove impractical radioactive elements
3. Cross-check compositions against Materials Project
4. Recover exact GNoME CIF structures

## Status

- [x] Screening complete
- [x] Candidate shortlist generated
- [ ] Full documentation pending

## Notes

The screening did not calculate Tc or claim to prove superconductivity.
It is a structure-discovery step, not a physics prediction.
