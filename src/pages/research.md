---
layout: ../layouts/ResearchLayout.astro
title: Research

vision: |
  A molecular motor stepping forward, a noisy electronic component, a cellular signaling cascade, a swarm of interacting particles, a set of chemical reactions, and a quantum-dot junction; these are all instances of stochastic systems that have been largely studied, in particular its fluctuating quantities and energetics. Using the powerful toolbox of stochastic thermodynamics, we can understand the behavior of these fluctuating nonequilibrium systems through energy dissipation, currents, thermodynamic forces and information flows across scales, from single biomolecules to emergent collective phenomena. The observation of all its degrees of freedom or the establishment of an accurate microscopic model would in principle reveal a system's complete dynamics and energy budget. Yet, we often only partially monitor such systems as a lower dimensional projection of the complete dynamics. For example, we only observe the mechanical displacement of the motor while its chemistry is hidden, and we only measure the in/out currents of the device while its internal representation is unavailable. When we cannot microscopically resolve observables, information content drops and thermodynamic quantities get scrambled.
  
  Inspired by what is actually measured in real experiments, I strive to develop (i) inference methods for hidden properties and thermodynamic quantities, (ii) a universal understanding of the role played by information, and (iii) fundamental relations between the available quantities. These are achieved by working at the crossroads between stochastic processes, information theory, and nonequilibrium thermodynamics, grounded by a strategic dose of application awareness.

pillars:
  - icon: ♨
    color: red
    title: Inference of Entropy Production
    description: >
      Inferring the value of entropy production or a nonzero lower bound reveals a violation of
      detailed balance, indicating that resources are being consumed to sustain
      the nonequilibrium state, even if hidden. Moreover, it quantifies energy dissipation, as
      entropy production measures the wasted heat. A suite of other results apply once entropy
      production is estimated, such as speed limits or precision bounds. I develop estimators for
      entropy production based on realistic trajectories: grained, downsampled, and/or
      restricted to a handful of visible transitions. In particular, I consider molecular motors,
      electronic systems, and chemical reactions.
    questions:
      - What are the tightest lower bounds on entropy production for a given time series?
      - How does coarse-graining distort the apparent irreversibility of a process?
      - Are there universal classes of systems where the bound saturate?
      - Between efficiency, speed or others, what are the criteria for molecular motor selection? 
    tags:
      - Entropy Production
      - Coarse-Graining
      - Thermodynamic Inference
      - Irreversibility
    papers:
      - label: "Harunari, Dutta, Polettini, Roldán · PRX (2022)"
        url: https://journals.aps.org/prx/abstract/10.1103/PhysRevX.12.041026
      - label: "Harunari · PRE (2024)"
        url: https://arxiv.org/abs/2402.00837

  - icon: ⊗
    color: blue
    title: Information Theory of Inference & Communication
    description: >
      Information is physical. Its quantification through information theory is fundamental
      to grasp how it flows between degrees of freedom, allowing energy transduction and communication.
      The interplay between dissipation, information content, and accuracy sheds light into
      the behavior of any system that processes information, from cells to intricate chips.
      I explore thermodynamic limits of communication, and the capacity to infer models from noisy
      sparse trajectories.
    questions:
      - How biological and artificial devices differ in information processing efficiency?
      - What are the signatures of hidden variables in real trajectories?
      - How does the inference capacity scale with number of points and sampling frequency?
      - How does measurement noise affects inference?
    tags:
      - Information Theory
      - Inverse problems
      - Channel Capacity
      - Fisher Information
    papers:
      - label: "In preparation."

  - icon: ⟳
    color: yellow
    title: Fundamental Properties of Markov Chains
    description: >
      Markov chains are the mathematical backbone of stochastic thermodynamics. Their dynamical and
      topological properties
      (cycle decompositions, stationary distributions, spectral gaps, etc.) govern everything
      from relaxation timescales to the structure of fluctuation theorems.
      Even though they have been used to model systems in numerous disciplines for many decades, 
      some fundamental properties are still being uncovered.
      A striking example is mutual linearity: When a single edge's transition rates are controlled,
      any two stationary currents in the network respond in strict proportion to one another. This is
      a rare instance of an exact result valid arbitrarily far from equilibrium. One immediate
      application is that the ATP consumption (typically hidden) of Myosin-V grows linearly with its
      speed (visible in experiments) when the concentration of phosphate changes.
    questions:
      - Can mutual linearity aid model inference?
      - Are there simple relations between the finite-time responses of observables?
      - What else can it reveal about biophysical systems modelled by Markov chains?
    tags:
      - Markov Chains
      - Network Theory
      - Spanning trees
    papers:
      - label: "Harunari, Dal Cengio, Lecomte, Polettini · PRL (2024)"
        url: https://arxiv.org/abs/2402.13193
      - label: "Dal Cengio, Harunari, Lecomte, Polettini · SciPost Phys. (2025)"
        url: https://scipost.org/SciPostPhys.19.4.111
---
