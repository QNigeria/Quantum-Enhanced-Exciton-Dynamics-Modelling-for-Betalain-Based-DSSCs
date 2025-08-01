# Quantum-Enhanced-Exciton-Dynamics-Modelling-for-Betalain-Based-DSSCs
Dye-Sensitised Solar Cells (DSSCs) represent a promising alternative to conventional photovoltaics, combining low-cost fabrication with tuneable optoelectronic properties [1]. Among natural sensitizers, betalain dyes—derived from plants such as beetroot—have gained attention for their broad light absorption spectra, environmental sustainability

https://github.com/QNigeria/xprize-dev/tree/main

## Project Contents

i. Project Title

ii. Names of Team Members

iii. Challenge overview

iv. Challenge Duration

v. Challenge Tasks/ Deliverables

vi. Resources (That is Source documents)

###  Project Title
 **Quantum-Enhanced Exciton Dynamics Modelling for Betalain-Based DSSCs**

### Names of Team Members
> (1) Ini Ekpenyong Ukut

> (2) Dr. Thomas Ojonugwa Daniel

> (3) Kenenth Isamade

> (4) Segun Oguntunnbi

> (5) Ibukunoluwa Adisa

> (6) Aniekan Afangide

> (7) Otene

> (8) Gospel Aigbodekheme Egeruan

> (9) Paul O Onoja

> (10) Tiamiyu Afees Olamilekan

### Challenge overview
Dye-Sensitised Solar Cells *(DSSCs)* represent a promising alternative to conventional photovoltaics, combining low-cost fabrication with tuneable optoelectronic properties [1]. Among natural sensitizers, betalain dyes—derived from plants such as beetroot—have gained attention for their broad light absorption spectra, environmental sustainability, and compatibility with titanium dioxide *(TiO₂)* semiconductors [2-3]. The efficiency of betalainbased DSSCs hinges on exciton dynamics at the dye-semiconductor interface, particularly the processes of exciton generation, dissociation, and charge transfer [4]. However, classical computational methods, such as Density Functional Theory *(DFT)* and Time-Dependent DFT (TDDFT), struggle to model these phenomena accurately due to their inability to scale efficiently for large systems and capture long-range electron correlations [5]. Quantum computing, with its inherent capacity to simulate quantum-mechanical systems exponentially faster, offers a transformative solution [6]. This proposal introduces a quantum-enhanced framework to model exciton dynamics in betalain-TiO₂ interfaces, leveraging algorithms like the **Variational Quantum Eigensolver (VQE)** and **Quantum Phase Estimation (QPE)** to overcome classical limitations and advance DSSC design.

### Challenge Duration
For the pass six month now the project 

### Challenge Tasks/ Deliverables
 _Statement of the Problem🏹_: The development of efficient betalain-based DSSCs is hindered by two critical challenges:
> 1. Computational inefficacy of classical methods: DFT and TDDFT, while foundational in quantum chemistry, exhibit poor scalability for modelling large-scale dye-semiconductor interfaces. Their approximations fail to capture long-range charge transfer dynamics, interfacial exciton dissociation mechanisms, and electron-hole interactions, leading to inaccurate predictions of charge injection efficiency.
> 2. Experimental complexity: Direct experimental observation of ultrafast exciton dynamics (e.g., femtosecond-scale charge transfers) is technically demanding and resource-intensive, creating a reliance on theoretical models that lack precision.
These limitations impede the optimisation of betalain-TiO₂ systems, restricting the development of high-efficiency DSSCs. A paradigm shift toward quantum computing is essential to resolve these bottlenecks and enable atomistic precise simulations of exciton behaviour.

_Aim and Objectives🛰️_: This study is focus on developing a quantum computing approach to enhance the modelling of exciton dynamics in betalain-TiO₂ interfaces which will be achieved via the following specific objectives:
> 1. To investigate the inefficacy of classical DFT/TDDFT in simulating large-scale betalain-TiO₂ interactions in regards to their failure to capture interfacial exciton dynamics and long-range charge transfer phenomena.
> 2. To develop a VQE-based quantum algorithm to model exciton generation and charge transfer mechanisms at the betalain-TiO₂ interface, with explicit focus on ground-state energy estimation.
> 3. Benchmarking quantum-derived data against classical TDDFT calculations

### Resources (That is Source documents)
The project was run on **Classical Computation** and **Quantum Computing**
> i. **Classical Computation**: Make use of ORCA and Avogadro

> ii. **Quantum Computing**: It was run on _Qiskit_ and _PennyLane_

   **Report on the Variational Quantum Eigensolver (VQE) Approach for an Oxygen Atom**

  _This report details the implementation of the Variational Quantum Eigensolver (VQE) algorithm for calculating the ground state energy of a single oxygen atom. The approach is a hybrid quantum-classical method that leverages the strengths of both a quantum computer for expectation value calculations and a classical computer for optimization. This analysis is performed on a single oxygen atom as a proxy for the larger betalain molecule, with the understanding that the approach can be generalized to more complex systems_

> Let’s plot the values of the ground state energy of the molecule and the gate parameter θ as a function of the optimization step.

<img width="1018" height="576" alt="image" src="https://github.com/user-attachments/assets/fef23cff-df22-48a3-90f5-7d5c2c4094d8" />
