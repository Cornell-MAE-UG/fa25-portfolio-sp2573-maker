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

###The Model of The Piston Engine

* The piston moves up and down inside the cylinder.
* A connecting rod links the piston to the crankshaft, converting the piston’s reciprocating motion into shaft rotation.
* Intake and exhaust valves in the cylinder head control the flow of air–fuel mixture into the cylinder and exhaust gases out.
* A spark plug ignites the compressed mixture near top dead center (TDC).
* Combustion gases exert high pressure on the piston crown, doing work on the piston and turning the crankshaft.

###The Engine Cycle

#### Intake Stroke
* Piston moves from TDC to bottom dead center (BDC).
* Intake valve open, exhaust valve closed.
* Cylinder pressure slightly below ambient; fresh air–fuel mixture flows in.

#### Compression Stroke
* Piston moves BDC → TDC.
* Both valves closed.
* Mixture is compressed; temperature and pressure rise (roughly adiabatically).

#### Power (Combustion/Expansion) Stroke
* Near TDC, spark plug ignites the mixture.
* Rapid combustion raises pressure and temperature.
* High-pressure gas pushes the piston TDC → BDC, producing most of the useful work.

#### Exhaust Stroke
* Exhaust valve opens.
* Piston moves BDC → TDC, pushing exhaust gases out to the surroundings.

###Mass and Energy Balance

####Mass Balance

mass rate in = mass rate out

####Energy Balance

Power of shaft = hat transfer through walls of engine + mass flow rate(enthalpy in - enthalpy out)

###Performenace Metrics

For a piston engine cylinder operating in steady periodic cycles, the thermal efficiency can be written in the simplest form as:

\[
\eta_{th} = \frac{W_{\text{shaft}}}{Q_{\text{in}}}
\]

**Where:**

* **\( W_{\text{shaft}} \)** — useful shaft work produced by the piston during one cycle  
* **\( Q_{\text{in}} \)** — heat added from combustion (fuel chemical energy per cycle)