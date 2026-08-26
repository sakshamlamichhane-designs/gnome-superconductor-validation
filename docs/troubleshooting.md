# Troubleshooting Notes

## MgB2: Large negative phonon frequencies

### Observation
DFPT phonon calculation for MgB2 produced large negative branches
in the dispersion plot.

### Initial hypothesis
Numerical/convergence or setup issue.

### Tests performed
- SCF convergence: checked (converged to -130.58 Ry)
- Cutoff variation: not yet systematically tested
- q-grid variation: pending
- Pseudopotential variation: pending
- Acoustic sum rule: checked

### Current status
Unresolved.

### Important note
This result is not interpreted as physical evidence of an unstable
MgB2 structure until the calculation and post-processing are
independently validated.

### Next steps
On the target HPC system, test:
1. Higher wavefunction cutoffs (e.g., ecutwfc = 80 Ry)
2. Denser q-point grid (e.g., 4×4×4)
3. Alternative pseudopotentials

## EPW: Version/path/filesystem errors

### Observation
EPW calculations in Colab failed due to version/path/filesystem errors.

### Current status
Under debugging. Will be resolved in a stable HPC environment.

### Resolution plan
On the target HPC system, use a consistent QE build for SCF, ph.x, and EPW.
