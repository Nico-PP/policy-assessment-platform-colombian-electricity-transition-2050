# Policy Assessment Platform for the Colombian Electricity Transition to 2050

## Overview

This repository contains the system dynamics model and supporting datasets used in the study:

> **Policy Assessment Platform for the Colombian Electricity Transition to 2050**

The platform was developed to analyze the long-term dynamics of the Colombian electricity generation system and to evaluate alternative policy pathways toward a fully renewable electricity matrix by 2050.

The model incorporates technological, operational, hydrological, political, and social dynamics affecting the electricity transition process. It enables the assessment of different transition scenarios, including the gradual phase-out of fossil-fuel technologies while maintaining system reliability and energy security.

The platform allows exploring:
- Renewable energy penetration scenarios
- Hydrological variability impacts
- Fossil fuel phase-out strategies
- Battery storage deployment
- Geothermal and biomass integration
- Electricity supply reliability under transition conditions

---

## Abstract

This paper presents a platform designed to understand the dynamics of the Colombian electricity generation industry, which also facilitates assessing alternative policies for the sustainable electricity transition by 2050. The platform is based on a system dynamics model that enables evaluating alternative power policies to attain a 100% renewable matrix under different scenarios.

It aims to overcome the limitations of traditional alternative approaches by incorporating elements such as the complexities inherent in political and social environments that affect electricity systems, mental models, feedback processes that influence policy adoption, and iterative decision-making improvements.

With this platform support, it is possible to explore phasing out fossil technologies while maintaining security of supply by incorporating geothermal, biomass, and batteries, as well as making efficient use of system reservoirs.

The results indicate that the robustness of the current system may decrease with the eventual phase-out of fossil technologies, highlighting the need to develop technologies such as geothermal and biomass. Additional findings include the identification of scheduling deficits caused by the seasonality of renewable energy sources and how small- and large-scale battery systems can effectively mitigate these issues.

---

## Software Requirements

The model was developed using:

- iThink / Stella Architect 1.8.2
- isee systems

The model file is provided in '.itmx` format.

---

## Repository Structure

```text
├── model/
│   └── Renewable Model 2024-2050 - VH vPaper.itmx
│
├── data/
│   ├── input_data/
│   │   └── DDE_import.xlsx
│   │
│   ├── hydrological_series/
│   │    └── hydrological_series.xlsx
│   │
│   └── output_data/
│        └── DDE_export.xlsx
│
├── equations/
│   └── equations.txt
│
└── README.md
```

## Description of Data Files

### input_data/

Contains input datasets used to initialize and parameterize the simulation model.

### hydrological_series/

Contains hydrological time series employed in the simulation.

### output_data/

Contains exported simulation results used for post-processing, visualization, and figure generation.


---

## Simulation Configuration

| Parameter | Value |
|---|---|
| Simulation Horizon | 2021–2050 |
| Numerical Method | Euler |
| Model Type | System Dynamics |
| File Format | '.itmx' |

---

## Running the Model

1. Open the '.itmx' model file using:
   - iThink
   - Stella Architect

2. Load the required datasets located in the `data/` directory if necessary.

3. Run the simulation using the default model configuration.

4. Export simulation outputs for analysis and visualization.

---

## Reproducibility

This repository is intended to support transparency and reproducibility of the results presented in the associated publication.

All relevant model structures, equations, datasets, and simulation files required to reproduce the experiments are included in this repository.

---

## Citation

If you use this repository or the associated model, please cite the corresponding publication.

---

## License

This repository is provided for academic and research purposes.
