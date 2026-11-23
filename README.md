# Living the Baltic: An agent-based model of human-animal-environment interaction through changing climatic scenarios in the Baltic sea basin

[![DOI](https://zenodo.org/badge/1448132380.svg)](https://doi.org/10.5281/zenodo.24008075)

## Overview

This project develops an exploratory agent-based model (ABM) that investigates human communities, marine mammals, and environmental change in the prehistoric Baltic Sea Basin.  
I created it as part of the MA course *Agent-based Modelling for Archaeologists* taught at the University of Cologne, within my doctoral studies at Stockholm University.
Due this is an ongoing project, most of the following is under development and it will be updated together with the model.

## Concept and objectives

The overall project focuses on human-animal-environment relationships in the context of the environmental transformations that shaped the Baltic Sea Basin following the last glaciation.
Its main interest is to explore how changing environmental conditions and human practices of marine mammal exploitation may have interacted over time, and how these interactions could  
have contributed to patterns observed in the archaeological record.  
In particular, this ABM project pretends to investigate how variability in ice conditions during the breeding season and hunting pressure exerted by humans influence the population 
abundance and spatial distribution of harp seals through their effects on reproduction, survival, mobility and mortality, in the prehistoric Baltic Sea.

## Conceptual Model  
<img width="1918" height="1080" alt="{8671988D-5C84-44D1-9FE1-9C7B6DB38A34}" src="https://github.com/user-attachments/assets/3c628e86-1cdf-4799-a55e-aede0e85ba55" />  

The conceptual model has been updated, aiming for a more direct cause-and-effect approach. This version of the model is intended to represent an initial level of  
complexity regarding the subject of study (complexity level 1).
Beyond the scope of level 1, there are various parameters and variables intended to complement future versions of the model.  

### Parameters and variables  

For this version (<code>v0.3</code>), the following parameters and variables have been defined:  

#### Parameters:
- Climate scenario;
- Initial seal population
- Initial human population
#### Variables:
- Temperature;
- Ice quality;
- Pup survival rate;
- Human-seal encounters;
- Hunting (as a decision);
- Successful hunt.

#### Agents
- <code>Seals</code>
- <code>Humans</code>

### State Machine
The present state-machine diagram has been developed to represent how an agent (<code>seals</code>) operates under different model inputs.  

<img width="1918" height="1080" alt="{FDC0DD35-60D7-464F-BF1F-5CE633D51460}" src="https://github.com/user-attachments/assets/7a578edb-5822-4063-bd20-771d7fb066cb" />

## Repository structure
[Work in progress]
\`\`\`

model/       → NetLogo model files (.nlogo)
data/        → Input datasets (CSV, shapefiles, etc.)
results/     → Simulation outputs
analysis/     → R scripts for analysis
docs/        → Documentation and notes

\`\`\`

## Usage
[Work in progress]
### Requirements
- [NetLogo](https://ccl.northwestern.edu/netlogo/)
- [R](https://www.r-project.org/) (optional, for analysis)

### How to run
[Work in progress]
## Results

Simulation results include different patterns and comparisons with available archaeological data.

## License

This template uses the MIT License.

## Citation

If you use or adapt this model, please cite:
> Bastias, F. (2026). *Living the Baltic: An agent-based model of human-animal-environment interaction through changing climatic scenarios in the Baltic sea basin*. Version 0.1.
> DOI: https://doi.org/10.5281/zenodo.24008075

## Acknowledgements

This repository was forked from: Angourakis, A. (2025). *CoDArchLab/Project2025_Template: Course repository template for Agent-based Modelling for Archaeologists.*  
This work was developed as part of the MA course *Agent-based Modelling for Archaeologists: From Concept to Application and Publication*,
taught by Andreas Angourakis at the University of Cologne.

---
