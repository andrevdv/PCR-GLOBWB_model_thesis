# PCR-GLOBWB — BMI/eWaterCycle adaptation

This repository contains a modified version of the PCR-GLOBWB model developed for use in the eWaterCycle framework.

This is a fork of the original PCR-GLOBWB repository. For the original model, documentation, and source code, please refer to the links below.

- **Original repository:** [PCR-GLOBWB model on GitHub](https://github.com/UU-Hydro/PCR-GLOBWB_model)
- **Original documentation:** [`documentation.md`](Original_documentation.md)

For implementation using BMI in ewatercycle:

- **EWC:** [ewatercycle on GitHub](https://github.com/eWaterCycle)

## Modifications

The main modifications made in this fork are:

- Updated the BMI implementation to the current version
- added set_channel storage (and template to add more model state interaction) using the updated BMI
- added parameter multipliers for calibration etc. (yet to be ported from WIP version)


## Purpose

This version was developed as part of my TU Delft Masters' thesis project to model the Aral Sea.

The original PCR-GLOBWB model2 and its documentation remain the reference for the underlying model methodology. This repository documents the modifications and adaptations made for this version of the model in order for my research and for possible ewatercycle integration.


## Miscellaneous

WSL and Docker: Use WSL together with the Docker CLI to build (and run) containers. Docker Desktop for Windows is not recommended, as the original model was developed and tested in a Linux environment and may not work reliably with Docker Desktop for Windows.