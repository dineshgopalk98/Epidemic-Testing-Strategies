# Epidemic Testing Strategies: SARS-CoV-2

## Project Overview

This project explores the evolution of the SARS-CoV-2 virus within a society, focusing on different testing and containment strategies. The study employs agent-based models, specifically an extended Susceptible-Infected-Recovered (SIR) model, to simulate virus spread considering multiple stages and introducing various containment measures.

## Abstract

The project introduces models for virus containment, including lockdown policies and contact tracing, to mitigate the ongoing COVID-19 pandemic. The extended SIR model incorporates seven stages, addressing the limitations of traditional SIR models. The study evaluates the effectiveness of different strategies, such as symptomatic detection, full lockdown, and contact tracing, based on practical applicability and relevant metrics like the final number of recovered agents and the reproductive number.

## Key Objectives

1. **Model Development:** Construct an agent-based model with seven stages to simulate virus spread accurately, incorporating various containment strategies.

2. **Testing Dynamics:** Introduce testing dynamics, including symptomatic detection and contact tracing, to the epidemic model.

3. **Parameterization:** Define model parameters, such as infection rates, movement probabilities, and testing precision, to reflect realistic scenarios.

4. **Containment Strategies:** Implement and evaluate three primary containment strategies – full lockdown, symptomatic detection, and contact tracing – to assess their impact on virus spread.

5. **Results and Metrics:** Analyze simulation results, focusing on the final number of recovered agents (Rinf) and the effective case reproductive number (Rc(t)), to draw conclusions regarding the efficacy of different strategies.

## Model and Parameters

The extended SIR model involves seven compartments (states): Susceptible, Exposed, Pre-symptomatic, Infectious Asymptomatic, Infectious Symptomatic, Detected, and Recovered. Parameters, such as infection probabilities, durations, and testing rates, are carefully chosen to represent real-world dynamics.
