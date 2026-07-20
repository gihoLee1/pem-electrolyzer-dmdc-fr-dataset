# pem-electrolyzer-dmdc-fr-dataset
# Experimental PEM Electrolyzer Dataset for Data-Driven Frequency-Regulation Modeling

This repository contains the experimental datasets used to identify and validate the DMDc-based PEM electrolyzer model presented in the associated manuscript.

## Dataset files

- data/step_training.csv
  Step-reference experimental dataset used for DMDc model identification.

- data/sinusoidal_validation.csv
  Independent sinusoidal-reference dataset used for model validation.

- data/regA_validation.csv
  Independent Reg-A dataset used for model validation.

- data/regD_validation.csv
  Independent Reg-D dataset used for model validation.

## Experimental conditions

- PEM electrolyzer rated power: 480 W
- Tested stack-current range: 18–28 A
- Sampling interval: 0.1 s
- Hydrogen-flow unit: mL/s
- Electrical-power unit: W

## Availability

The datasets are released for academic research and reproduction of the model-identification and validation results reported in the associated manuscript.
