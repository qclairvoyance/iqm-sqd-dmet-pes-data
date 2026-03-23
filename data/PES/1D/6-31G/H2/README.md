# 1D-PES H2 Dataset

## Description
This dataset contains 1D-PES SQD simulation results for the H2 molecule in the 6-31G basis.

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
- Each configuration includes 3 independent runs.
- Energies are reported in [Hartree].
- Bond distances are in [Å].

## Method
- SQD(LUCJ)