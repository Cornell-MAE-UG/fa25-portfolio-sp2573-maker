---
layout: project
title: Thermodynamic Analysis of a Piston Engine
description: Thermodynamic Analysis of the Engine
technologies: [Autodesk Fusion 360]
image: /assets/images/car-engine-CAD.png
---

In November 2025, as part of a homework for a thermodynamics class I had to analyze a real thermodynamic system and consider ways to improve it.

<br>
<br>
<br>


### The Model of the Engine

A piston-cylinder engine is a mechanical system that converts energy from a working fluid into reciprocating motion. It consists of a cylindrical chamber in which the piston moves back and forth (up and down) as pressure within the cylinder changes. In this analysis, the engine is modelled as an **Otto Cycle**, which consists of the following steps:

- **1 → 2:** Isentropic compression  
- **2 → 3:** Constant-volume heat addition  
- **3 → 4:** Isentropic expansion  
- **4 → 1:** Constant-volume heat rejection  

In this ideal case, all processes are assumed to be internally reversible, and there is no heat transfer between the system and the surroundings.

### The P-v Diagram

![P-v Diagram]({{ "/assets/images/Pv_diagram.jpeg" | relative_url }}){: style="width: 500px"}

### The T-s Diagram

![T-s Diagram]({{ "/assets/images/Ts_diagram.jpeg" | relative_url }}){: style="width: 500px"}

### Work and Heat for Each Process

![Work and Heat Eqs]({{ "/assets/images/QandW_Transfer.jpeg" | relative_url }}){: style="width: 500px"}

The net work of the cycle is obtained by subtracting the work input during process **1 → 2** from the work output during process **3 → 4**. The net work can also be evaluated as the net heat added, which is found by subtracting the heat rejected during process **4 → 1** from the heat added during process **2 → 3**. Therefore, the area enclosed by both the **p–v diagram** and the **T–s diagram** represents the net work output of the ideal **Otto Cycle**.

Since air is assumed to behave as an ideal gas, the work and heat transfer for each process can be expressed in terms of the specific heat at constant volume. The work done or heat transferred during a process from state a → b is given by the specific heat at constant volume multiplied by the temperature difference between the two states.

### Control Mass Drawings for the System

![First Two Steps]({{ "/assets/images/FirstTwoSteps.jpeg" | relative_url }}){: style="width: 500px"}
![Last Two Steps]({{ "/assets/images/LastTwoSteps.jpeg" | relative_url }}){: style="width: 500px"}