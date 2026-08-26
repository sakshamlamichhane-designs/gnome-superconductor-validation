# Candidate validation

DFT validation of the shortlisted GNoME candidates.

## Status

| Candidate | Role | vc-relax | SCF | Phonons | EPW |
|-----------|------|----------|-----|---------|-----|
| Gd3Re3MoRuN12 | Primary | [ ] | [ ] | [ ] | [ ] |
| Gd3NbRe3RuN12 | Primary | [ ] | [ ] | [ ] | [ ] |
| Gd3Cr2(ReN4)3 | Primary | [ ] | [ ] | [ ] | [ ] |
| Gd12Nb8ZnW11N48 | Reserve | [ ] | [ ] | [ ] | [ ] |

## Workflow

Each candidate will undergo:
1. vc-relax – variable-cell relaxation
2. SCF + DOS/bands – electronic structure
3. DFPT phonons – dynamical stability
4. EPW – electron-phonon coupling (if metallic and stable)

## Stopping rules

A candidate is discarded if:
- It relaxes to an unrelated structure
- It is robustly insulating
- It remains dynamically unstable
- The magnetic ground state invalidates the assumed mechanism
- Electron-phonon coupling is too weak

## Contact

Saksham Lamichhane – sakshamlamichhane456@gmail.com
