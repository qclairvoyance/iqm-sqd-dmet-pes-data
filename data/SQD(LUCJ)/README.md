# SQD(LUCJ) Dataset

## Description
This dataset contains SQD simulation results for H2, LiH, BeH2, H2O, NH3 molecules in the STO-3G basis.

## Files
- raw.csv  
  Raw sampled data before post-processing.

- final1.csv  
  Results using:
  ε_s = 10^8 (samples_per_batch)

- final2.csv  
  Results using:
  ε_s = sqrt(symmetry_space)

## Notes
- Each molecule includes 3 independent runs.
- Energies are reported in [Hartree].
- Bond distances are in [Å].

## Method
- SQD(LUCJ)