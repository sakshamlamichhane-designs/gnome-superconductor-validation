# GNoME screening

Initial filtering of the GNoME dataset to identify candidate structures for superconductivity investigation.

## Files

- `candidate_shortlist.csv` – Final list of 10 candidates after filtering
- `figures/` – Plots and visualizations (to be added)

## Candidate selection criteria

1. Superconductivity-oriented subset from GNoME (381,000+ structures)
2. Remove impractical radioactive elements
3. Cross-check compositions against Materials Project
4. Recover exact GNoME CIF structures
5. Rank by uncorrected energy

## Top 10 candidates

| # | Formula | Energy |
|---|---------|--------|
| 1 | Gd12N48Nb8W11Zn1 | -868.3391 |
| 2 | Gd12Hf8Mo12N48 | -861.9466 |
| 3 | Gd12N48Re12Zr8 | -859.2714 |
| 4 | Mo12N48Nb5Pu12Ta3 | -852.9404 |
| 5 | Cr8Gd12N48Re12 | -846.6232 |
| 6 | Gd12N48Nb4Re12Ru4 | -844.3862 |
| 7 | Gd12Mo4N48Re12Ru4 | -841.1112 |
| 8 | Gd12Ho8N48Re12 | -828.64 |
| 9 | Gd12N48Nb8Tc12 | -827.9175 |
| 10 | Gd12Mg4Mo4N48Re12 | -821.5026 |

## Status

- [x] Screening complete
- [x] Candidate shortlist generated
- [x] 4 candidates selected for CHGNet relaxation

## Notes

The screening did not calculate Tc or claim to prove superconductivity.
It is a structure-discovery step, not a physics prediction.

## Units

- `energy` values are in **eV per formula unit** (from GNoME).
