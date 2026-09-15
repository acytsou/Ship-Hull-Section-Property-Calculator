# Ship Hull Section Property Calculator

MATLAB-based computational tool for hull girder sectional property evaluation, corrosion assessment and structural damage analysis. Purpose of the app is allowed user to identity the midship section properties change under thickness reduction or members failure. 


## User Interface
![image_alt](https://github.com/acytsou/Ship-Hull-Section-Property-Calculator/blob/8fb78b2cbd927bd4df3da37504e6642ad275f921/App_Interface.jpg)


## Overview

The Ship Hull Section Property Calculator was developed to support rapid assessment of ship cross-sectional properties for longitudinal strength investigations.

The application enables users to model hull cross-sections including shell plating, deck plating, girders, bulkheads and stiffeners, and automatically computes:

- Cross-sectional area
- Neutral axis location
- Moment of inertia
- Section modulus


## Features

### Structural Modelling

- Shell plating
- Arc shell (bilge) modelling
- Deck and girder plates
- T-section stiffeners
- Angle stiffeners

### Corrosion Assessment

- Thickness reduction input
- Uniform percentage reduction
- Corrosion scenario analysis

### Damage Assessment

- Web removal
- Flange removal
- Complete stiffener removal

### Cross-Section Property Evaluation

- Cross-sectional area
- Neutral axis
- Moment of inertia
- Deck section modulus
- Keel section modulus

### User-Friendly Functions

- Automatic unit conversion
- Save/load section files
- Symmetry generation
- Geometry visualisation


## Example Models

Example input files are included:

- Original pre-set example in app
and extra data files
- Example_b.mat
- Example_c.mat

These files can be loaded directly into the application using the Load button.


## Validation

The application was validated against independently generated CAD-based ship sections.

Comparison of:

- Cross-sectional area
- Neutral axis location
- Moment of inertia
- Section modulus

showed excellent agreement, with typical differences below 1%.


## Installation

### MATLAB Source Version

Download:

- HullSectionApp.mlapp

Open directly in MATLAB App Designer.

### Standalone Version

Download the latest release:

[link here](https://github.com/acytsou/Ship-Hull-Section-Property-Calculator/releases)

No MATLAB license is required.

MATLAB Runtime is required (Should automatlly have the exectuable download MATLAB Runtime if needed on the end user's computer, need to confirm).


## Developed MATLAB Version

Developed and tested using:

- MATLAB R2025b (testing)
- MATLAB R2023b (developed)


## Citation

Toolbox citation:

```text
Tsou, A. (2026). Ship Hull Section Property Calculator (Version 1.0) [Computer software]. GitHub. Available at:
https://github.com/acytsou/Ship-Hull-Section-Property-Calculator (Accessed: dd month year).
```


## Author

Andy Tsou

Australian Maritime College (AMC)

University of Tasmania


## Acknowledgements

The author gratefully acknowledges the support and guidance provided by supervisors, AMC students throughout this project.

Artificial intelligence tools were used as supplementary assistants for programming support, troubleshooting, documentation refinement for publish, and software development discussions. All outputs were critically evaluated and verified before being incorporated into the final application and documentation.
