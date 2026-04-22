# Mike Draugelis

Building simulation and causal-inference tooling for healthcare AI.
AVP of AI at [Geisinger Health System](https://www.geisinger.org/). Previously Chief Data Scientist at Penn Medicine.

---

## What I work on

Most of my open-source work circles one question: **how do we know an AI intervention actually helped a patient?** You never see the counterfactual in real data — the patient either got the intervention or didn't. The tools I build try to close that gap: controlled simulations with known ground truth, model-performance generators, and scenarios you can test causal-inference methods against before anything touches a clinical workflow.

Governance as engineering, not compliance.

## Currently building

**[healthcare-sim-sdk](https://github.com/mdraugelis/healthcare-sim-sdk)** — a simulation SDK for evaluating healthcare AI interventions before real-world deployment. Five-method scenario contract (population, step, predict, intervene, measure), branched counterfactual trajectories, controlled ML model simulation, RNG stream partitioning, and analysis exports for ITS, DiD, and RDD. Ships with replications of three published studies (Chong et al. 2020 MRI no-shows, Rosen et al. 2023 equity, Adams et al. 2022 sepsis EWS) as validation. Apache 2.0.

If you work in healthcare ML, causal inference, or AI governance — take a look. Issues and discussions welcome.

## Background

Led the Penn Medicine Predictive Healthcare team for eight years. During COVID we built **[CHIME](https://github.com/CodeForPhilly/chime)** — the COVID-19 Hospital Impact Model for Epidemics — an SIR-based hospital-capacity planning model that was open-sourced through Code for Philly and used by thousands of hospitals during the early surge. Published in [*Annals of Internal Medicine*](https://www.acpjournals.org/doi/10.7326/M20-1260).

Before that: built **Penn Signals**, the orchestration layer behind Penn's deployed predictive apps — sepsis early warning, heart failure decompensation, high-risk pregnancy, and oncology triage.

Now at Geisinger, leading an AI department across governance, delivery, and platform.

## Selected repos

- **[healthcare-sim-sdk](https://github.com/mdraugelis/healthcare-sim-sdk)** — simulation SDK for healthcare AI evaluation *(current focus)*

## Selected publications & press

- Weissman, Crane-Droesch, Chivers, Luong, Hanish, Levy, Lubken, Becker, Draugelis, et al. *Locally Informed Simulation to Predict Hospital Capacity Needs During the COVID-19 Pandemic.* Annals of Internal Medicine, 2020. [[paper]](https://www.acpjournals.org/doi/10.7326/M20-1260)
- Penn Medicine Predictive Healthcare — [publications and press archive](http://predictivehealthcare.pennmedicine.org/press-publications/)

## Elsewhere

- LinkedIn — [michaeldraugelis](https://www.linkedin.com/in/michaeldraugelis/)
