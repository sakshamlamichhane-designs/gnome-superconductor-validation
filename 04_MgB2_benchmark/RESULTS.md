# MgB2 Benchmark Results

## SCF

**Status:** Completed

**Parameters:**
- QE version: 7.3 (compiled from source)
- Pseudopotentials: mg_pbe_v1.4.uspp.F.UPF, B_pbe_v1.01.uspp.F.UPF
- Cutoff (ecutwfc): 60 Ry
- Cutoff (ecutrho): 480 Ry
- k-grid: 8×8×8
- Smearing: Marzari-Vanderbilt, 0.02 Ry
- Convergence threshold: 1.0e-8

**Result:**
! total energy = -130.58372141 Ry
estimated scf accuracy < 2.2E-13 Ry

## DFPT

**Status:** Diagnostic/development stage

**Parameters:**
- q-grid: 2×2×2
- fildyn: mgb2.dyn
- ASR: simple

**Current issue:**
The current phonon plot contains large negative-frequency branches.

**Hypotheses being investigated:**
1. Structure/lattice parameters
2. Pseudopotentials
3. k-point convergence
4. Smearing
5. DFPT convergence
6. Acoustic sum rule
7. q-path construction
8. Frequency conversion / plotting

**Resolution plan:**
On the target HPC system, I will test higher wavefunction cutoffs and
a denser q-point grid to establish a clean phonon dispersion.

## EPW

**Status:** Under debugging

No final Tc is claimed.
