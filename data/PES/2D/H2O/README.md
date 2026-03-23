# 2D-PES H2O Dataset

## Description
This dataset contains 2D-PES SQD simulation results for the H2O molecule in the STO-3G basis.

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
- Each configuration includes 1 independent run.
- Energies are reported in [Hartree].
- Bond distances are in [Å].

## Method
- SQD(LUCJ)