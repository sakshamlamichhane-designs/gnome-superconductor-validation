# Methods

## Quantum ESPRESSO

**Version:** 7.3 (compiled from source)

**Workflow:**
1. vc-relax – variable-cell relaxation (forces < 10^-4 Ry/au)
2. SCF – self-consistent field calculation
3. DFPT – phonons on q-grid
4. EPW – electron-phonon coupling

## Pseudopotentials

**Family:** SSSP Precision 1.3.0 (PBE)

**Elements used:**
- Gd.paw.z_18.atompaw.wentzcovitch.v1.2.upf
- Re_pbe_v1.2.uspp.F.UPF
- Mo_ONCV_PBE-1.0.oncvpsp.upf
- Ru_ONCV_PBE-1.0.oncvpsp.upf
- N.oncvpsp.upf
- mg_pbe_v1.4.uspp.F.UPF (MgB2)
- B_pbe_v1.01.uspp.F.UPF (MgB2)

## Magnetism

Spin-polarized calculations (nspin=2) will be used for Gd-containing
candidates. DFT+U will be applied if needed.

## Convergence criteria

- Forces: < 10^-4 Ry/au
- Energy: < 10^-5 Ry
- Stress: < 0.5 kbar
- SCF: < 10^-8 Ry

## Stopping rules

Candidates are discarded if:
- Insulating/semiconducting
- Dynamically unstable
- Negligible electron-phonon coupling
