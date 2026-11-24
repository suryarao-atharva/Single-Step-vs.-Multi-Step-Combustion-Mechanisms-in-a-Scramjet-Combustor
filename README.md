# Single-Step vs. Multi-Step Reaction Mechanisms in a Scramjet Combustor

## Overview
This project investigates the effect of chemical reaction mechanisms on hydrogen-air combustion in a strut-injected scramjet combustor using ANSYS Fluent.

A comparative analysis is performed between a simplified single-step reaction mechanism and the detailed 10-species, 21-reaction hydrogen-oxygen mechanism proposed by O'Connaire et al. (2004).

## Objectives
- Implement multi-step hydrogen-oxygen reaction kinetics in ANSYS Fluent.
- Compare single-step and multi-step combustion models.
- Evaluate flame temperature distributions and combustion efficiency.
- Validate numerical results against published experimental and computational benchmarks.

## Key Results

| Parameter | Single-Step | Multi-Step |
|---|---:|---:|
| Flame Temperature | 2660 K | 2204 K |
| Exit Combustion Efficiency | 65.4% | 87.9% |

The multi-step mechanism provides significantly better agreement with published benchmark results.

## Tools & Technologies
- ANSYS Fluent
- Computational Fluid Dynamics (CFD)
- RANS Simulations
- CHEMKIN Reaction Mechanisms
- Hydrogen Combustion Kinetics

## Reference
O'Connaire, M., et al. (2004). A Comprehensive Modeling Study of Hydrogen Oxidation. International Journal of Chemical Kinetics, 36, 603–622.
2
