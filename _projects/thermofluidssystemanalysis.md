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

## Mass Balance

### General control-volume form
dm_CV/dt = Σ ṁ_in − Σ ṁ_out

### For a piston engine
- Over a full cycle, the engine returns to its initial state
- Therefore, **no net mass accumulation**

Σ ṁ_in = Σ ṁ_out

---

## Energy Balance (First Law of Thermodynamics)

### General control-volume form
dE_CV/dt = Σ Q̇ − Σ Ẇ  
     + Σ ṁ_in (h + V²/2 + gz)_in  
     − Σ ṁ_out (h + V²/2 + gz)_out

### For a piston engine (simplifications)
- Changes in kinetic and potential energy are negligible
- Over a cycle:

dE_CV/dt = 0

Σ Q̇ − Σ Ẇ + Σ ṁ_in h_in − Σ ṁ_out h_out = 0

- This balance governs **engine efficiency and power output**

---

## Entropy Balance (Second Law of Thermodynamics)

### General control-volume form
dS_CV/dt = Σ (Q̇_k / T_k)  
     + Σ ṁ_in s_in  
     − Σ ṁ_out s_out  
     + S_gen

- **Note:** S_gen ≥ 0

### For a piston engine (steady cyclic operation)
Σ (Q̇_k / T_k) + Σ ṁ_in s_in − Σ ṁ_out s_out + S_gen = 0

- The entropy balance quantifies **irreversibility and efficiency limits**

We did this project in a group and the people in my group were Teddy Rauchway and Panashe Neghna.