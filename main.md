---
author:
    - L. Mingari$^1$
institute:
    - $^1$Geosciences Barcelona
title: SO2 sumlat
description: Internal group meeting
date: 15 September 2022
---

# Modelling SO2 dispersion during the 2021 eruption of Fagradalsfjall, Iceland

## References
Pfeffer, Melissa A., et al. "SO2 emission rates and incorporation into the air pollution dispersion forecast during the 2021 eruption of Fagradalsfjall, Iceland." Journal of Volcanology and Geothermal Research 449 (2024): 108064.
https://doi.org/10.1016/j.jvolgeores.2024.108064

## Numerical simulations - Configuration
We performed 70-member ensemble simulations of SO2 transport using the FALL3D model. Different source term parameters were perturbed.

| Parameter | Reference | Perturbation range |
| --------  | -------- | -------- |
| Suzuki-A  | 4     | 3           |
| Suzuki-λ  | 2     | 1.5         |
| Wind componentes | CARRA | 20%  |
| Column height | Measurements (see plot below) | 20% |
| Emission rate | Fixed (100 kg/s) | No perturbed |

### Meteorological dataset
Carra reanalysis at 2.5-km resolution on pressure levels. Use model levels in the future!

### Vertical distribution
We explored different vertical distributions:

![](figs/vertical_distribution.png)

