---
layout: project
title: Spotted Lantern Fly Engineering Solution
description: 60 Hz Frequency-Based Spotted Lanternfly Deterrent
technologies: [Fusion 360, Arduino, Bambu]
image: /assets/images/HertzTrap_Figure.png
---

## Table of Contents

- [Client Pitch](#client-pitch)
- [Functional Prototype](#functional-prototype)

## Client Pitch {#client-pitch}

# HertzTrap: Frequency-Based Spotted Lanternfly Deterrent


**Team:** Newton's Nightmares  
**Client(s):** Cornell CALS Extension / E\&J Gallo Winery / National Grape


## Problem statement


Farmers in vineyards are trying to continue growth and production of their vineyards. However, the growing population of Spotted Lanternflies (SLFs) puts significant pressure on farmers as these insects feed off grapevines, lowering yield and significantly damaging or killing the plants. The SLF is an exceptionally harmful pest because there are no natural predators and regular pest control does not work effectively. When harvesting, if more than 2 SLFs are found in a 1 kg sample of harvest, the entire section must be discarded per health code—a devastating loss for farmers already running on thin margins. Our team is aiming to take advantage of the SLF's documented attraction to 60 Hz frequencies and create a product that draws SLFs away from grapevines.


## Impact


SLF infestations prevent farms from passing health code inspections, forcing the discard of otherwise viable harvests. This directly threatens farm profitability and viability. A product that removes SLFs from grapevines before harvest can prevent yield loss, help farms meet health codes, and significantly increase both productivity and profit margins.


## Proposed direction(s)


### Concept A: HertzTrap


**What it is:** A modified electric insect trap designed to attract adult SLFs using a 60 Hz vibrational stimulus, based on published observations of SLF responsiveness to specific frequency cues.


**How it would be used:**
- Traps are installed along vineyard perimeters or near vine canopies before harvest
- Device emits 60 Hz stimulus to attract SLFs away from grape vines
- SLFs fly into an electrified grid and are neutralized before entering vineyard
- Device operates continuously during migration window


**Why it's better than the status quo:**
- Targets SLFs before they enter vineyards and have access to grapes
- Avoids pesticide application and associated labor
- Uses simple electrical components instead of a high-precision sorting system


**End-of-semester proof-of-concept:** We will develop a full CAD model with real-world dimensions and a scaled-down HertzTrap shell built to accurate proportions. The shell will include an internal slot and 60 Hz speaker, plus a PLA or ABS mesh outer layer to represent the electrically charged shock layer.


## Key risks / unknowns


- **Attraction Strength:** SLFs may not respond strongly enough to 60 Hz cues in open vineyard environments. We will test this through outdoor trials to validate effectiveness.
- **Nontarget Effects:** The trap may attract or harm beneficial insects. We will evaluate trap selectivity through observational testing.
- **Environmental Durability:** Outdoor weather and dust may reduce performance. We will evaluate possible materials, durability, and placement strategies.


## Questions


1. **What size trap would be most practical for your operations?** *Decision affected:* Sizing and the number of traps we recommend installing per acre.
2. **Will disposing of dead flies be an issue for your farms?** *Decision affected:* Whether we need to design the trap to minimize aftereffects or provide disposal guidance.
3. **Is harming non-SLF animals and pests of similar size/behavior a major environmental concern?** *Decision affected:* Whether we need to refine trap selectivity or if the current design approach is acceptable.




## References


- Wine Market Value - https://www.grandviewresearch.com/industry-analysis/us-wine-market
- Spotted Lanternfly Information - https://cals.cornell.edu/integrated-pest-management/outreach-education/whats-bugging-you/spotted-lanternfly/spotted-lanternfly-damage
- 60 Hz Research - https://www.usda.gov/about-usda/news/blog/spotted-lanternfly-reveals-potential-weakness

## Functional Prototype {#functional-prototype}

### Purpose of the Prototype

The functional prototype was built to test whether the HertzTrap design could physically support its intended use as a vineyard-deployable spotted lanternfly deterrent. The team focused on three main goals: protecting and housing the electronics, confirming that the box had enough internal space for all planned components, and checking whether the structure could withstand drops and vertical loads likely to occur during handling and outdoor use. The prototype includes an upper electrical box, lid, copper mesh, legs, Arduino Nano, shocker PCB, battery box, speaker, amplifier, and power switch.

### What Was Tested

The prototype was assembled by placing the electrical components inside the upper box, securing them temporarily, mounting the cover with screws, attaching the mesh to the center structure, and gluing on the temporary legs.

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">

  <img src="{{ '/assets/images/Step1.png' | relative_url }}" style="width:100%;">
  <img src="{{ '/assets/images/Step2.png' | relative_url }}" style="width:100%;">
  <img src="{{ '/assets/images/Step3.png' | relative_url }}" style="width:100%;">

  <img src="{{ '/assets/images/Step4.png' | relative_url }}" style="width:100%;">
  <img src="{{ '/assets/images/Step5.png' | relative_url }}" style="width:100%;">
  <img src="{{ '/assets/images/Step6.png' | relative_url }}" style="width:100%;">

</div>

Three main tests were then performed:

#### 1. Drop Test
The trap was dropped legs-up onto grass from heights of 1 foot, 2 feet, and 4 feet to evaluate how well the upper box protected the electronics and whether the overall structure remained intact.

![Drop Test]({{ "/assets/images/DropTest.png" | relative_url }}){: style="width: 500px"}

#### 2. Box Capacity and Electrical Component Fit
The team checked whether the upper electrical box had enough space for the speaker, Arduino Nano, zapper PCB, battery case, and possible future upgrades such as a larger battery or added circuitry.

#### 3. Strength / Sturdiness Test
Weights were added incrementally to the upper lid to determine how much load the prototype could support before buckling, breaking, or tipping. This test focused especially on the temporary legs and the upper box structure.

![Weight Test]({{ "/assets/images/WeightTest.png" | relative_url }}){: style="width: 500px"}

### Outcome

The prototype performed well in the drop tests. At 1 foot, there was no visible damage and the device remained unchanged. At 2 feet, the box tipped over on impact but still showed no visible damage, and the internal components stayed protected. At 4 feet, the temporary legs became unstable and shifted, but they did not break off, and the electronics remained attached inside the box. This showed that the upper box itself was durable, while the legs need reinforcement in the next version.

The box capacity test also gave strong results. The internal box volume was estimated at 96 cubic inches, while the planned electronics occupied only about 10 square inches of area and remained under the 1.5-inch height constraint. This showed that the current design has enough room for all planned electronics and leaves additional space for upgrades or airflow improvements. 

In the strength test, the prototype remained stable under 544 g, 1095 g, and 1654 g. At 2195 g, the box began to tip and the temporary legs showed visible stress. Even so, the prototype demonstrated that it could comfortably handle loads greater than grapevine debris and small animals, which the team estimated at roughly 200–500 g. This suggests that the design is promising, but that the final version should use stronger legs and reinforced joints for long-term durability in field conditions.

### Success Criteria Going Forward
