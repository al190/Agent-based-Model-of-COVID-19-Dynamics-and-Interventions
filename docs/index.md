# Agent-based Model of COVID-19 Dynamics and Interventions

A concise, easy-to-read homepage for the project. This page gives an overview of the model, core ideas, and short steps to reproduce results. The design is intentionally simple.

## About

This repository contains an agent-based simulation that models individual-level COVID-19 transmission and evaluates non-pharmaceutical interventions (NPIs) such as social distancing, testing & isolation, and contact tracing. The goal is to explore how combinations of interventions affect outbreak size and healthcare demand.

## How it works

![Compartment model](images/compartments.svg)

The simulation represents agents moving between health states (Susceptible → Exposed → Infectious → Recovered). Transmission occurs through simulated contacts between agents; disease progression and intervention effects are modeled at the individual level.

## Key features

- Individual-level agents with configurable behavior and contact patterns
- Multiple interventions (social distancing, testing & isolation, contact tracing)
- Outputs for cases, hospitalizations, and intervention effectiveness
- Scripts/notebooks to run experiments and produce plots

## Interventions (examples)

- Distancing — reduce number of contacts per agent; configurable compliance and contact reduction.
- Testing & isolation — test symptomatic (and optionally asymptomatic) individuals; positive cases isolate to limit onward transmission. Parameters include test delay and isolation adherence.
- Contact tracing — identify and notify contacts of positive cases; contacts may be quarantined or tested depending on tracing success and delay.

## Conclusion

This project provides a flexible agent-based framework to explore how individual-level behaviors and interventions influence COVID-19 dynamics. Use the code and configuration options to reproduce experiments, compare intervention strategies, and extend the model for different settings.

If you'd like, I can add a short Methodology or Results page, embed the presentation slides, or add screenshots of example outputs.

## Presentation

View the project slides: https://docs.google.com/presentation/d/1SkSFu1Y4YiSsyPA2ts3Nockpy3MPqwsPSvDjXHDOo2I/edit?usp=sharing

## Contact

Maintainer: al190 — https://github.com/al190