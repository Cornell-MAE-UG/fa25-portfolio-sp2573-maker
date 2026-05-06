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
- [Client Report](#client-report)

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

## Client Report {#client-report}

### Problem Overview

During the pre-harvest grape season, vineyards across the Northeast face devastating losses from the Spotted Lanternfly (SLF). With no natural predators and ineffective conventional pest control, SLF populations continue to surge unchecked. These insects feed directly on grapevines, reducing yield and threatening plant health. The challenge is to intercept SLFs before they ever reach the vines, preserving crop quality and keeping farmers profitable.

### Sub-problem and Prototype Application

Our concept was to prevent SLFs from reaching the vines in the first place rather than removing them after harvest, offering a more effective and scalable solution to protecting vineyard yield. To do this, we wanted to create a product that could passively kill the SLFs and draw them away from the vines before doing harm to the plant. We identified a critical weak point in the spotted lanternfly and exploited it by adapting the proven lure-and-kill method of UV bug traps to the USDA's discovery that these insects are uniquely drawn to 60 Hz frequencies. We called this product the HertzTrap.

The HertzTrap is a self-contained electric insect trap that lures and eliminates SLFs before they reach the grapevines. By luring them toward this specific frequency, the trap brings them into contact with an electrified mesh that completes the circuit and neutralizes them instantly. Because it is compact and pesticide-free, it serves as a low-maintenance tool that can be easily deployed across large-scale vineyards without the need for manual insect removal.

### Prototype

The final HertzTrap prototype was built to validate the core concept at a functional scale. The enclosure houses a 60 Hz speaker at its center, surrounded by a dual-layer electrified mesh powered by a bug zapper circuit board. When SLFs are drawn toward the frequency stimulus, they make contact with the charged mesh, complete the circuit, and are eliminated.

The four independently adjustable legs allow the trap to be staked and leveled at grapevine canopy height across uneven terrain. The enclosure was designed to be weatherproof and structurally rigid, withstanding up to 30 lbs of force without deformation. At just 8 lbs total, the final assembly is lightweight enough for rapid single-user deployment across large farm areas. Overall, the final prototype successfully integrates the electrical, acoustic, and structural subsystems into a compact, field-ready package.

### Testing and Results

Three key performance criteria were evaluated through physical testing of the prototype to ensure a successful product.

#### 1. Structural Durability

This was confirmed by applying incremental loads to the top of the enclosure; the trap withstood up to 40 lbs without deformation or failure, meeting the demands of outdoor farm use. We also dropped 5–10 lb weights from a foot high to replicate branches and falling situations.

#### 2. Adjustability

This was verified by extending and locking each leg independently, confirming a maximum stable height of 3 feet suitable for placement near vine canopies. Individual legs were tested to support the trap at angles and rough areas.

#### 3. Portability

This was tested by timing a single user relocating the trap across a simulated farm layout; the trap was consistently moved and reset in under 15 seconds, and at 6 lbs total weight, a single user could feasibly deploy over 100 units within a standard workday.

While these criteria confirmed the trap's physical viability, they did not address some more critical unknowns surrounding the trap's core function. In retrospect, more decision-relevant success criteria would have focused on biological performance: specifically, whether the mesh density and voltage are sufficient to reliably neutralize a Spotted Lanternfly upon contact, and whether the 60 Hz acoustic stimulus attracts SLFs at a meaningful range under field conditions.

In order to simulate a branch falling onto the box, or a drop from a high height, we should have documented weights falling from a height rather than placing them directly on the box. Bench testing confirmed arc discharge across the mesh layers, providing a preliminary indication that the electrical system is functional, but controlled experiments with live insects at measured distances were not conducted.

These tests — verifying kill reliability at the chosen mesh geometry and quantifying attraction range and capture rate in a vineyard environment — represent the most important next steps before the HertzTrap can be evaluated as an effective pest control solution.

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px;">

  <img src="{{ '/assets/images/BugZapperExplodedView.png' | relative_url }}" style="width:100%;">
  <img src="{{ '/assets/images/SixFtZapper.png' | relative_url }}" style="width:100%;">
  <img src="{{ '/assets/images/AnyTerainZapper.png' | relative_url }}" style="width:100%;">

</div>

### Prototype and Testing Details

The HertzTrap enclosure measures approximately 8 × 8 × 2 inches and was fabricated using 3D printing, chosen for its ability to produce a rigid, weatherproof housing at low cost with rapid iteration. The electrical system consists of a repurposed handheld bug zapper circuit board powered by two AA batteries, which steps up the input voltage to a level sufficient to arc across the mesh gap.

In parallel with the trapping system, an acoustic subsystem was developed, consisting of a 57 mm diameter speaker driven by an amplifier and controlled by an Arduino Nano to generate a 60 Hz signal. The trap uses a dual-layer mesh configuration: a higher-density inner copper mesh and a lower-density outer metal mesh, with the two layers held at opposite polarities.

When an insect bridges the gap between layers, it completes the circuit and is eliminated. The outer mesh has larger gaps so that the SLF can effectively bridge the two meshes. Successful arc discharge between the mesh layers was confirmed during bench testing, validating that the electrical system functions as intended at the chosen mesh spacing and density.

<div style="display: flex; justify-content: center; margin-top: 15px; margin-bottom: 15px;">

  <img src="{{ '/assets/images/CircuitSchematic.png' | relative_url }}" style="width:60%;">

</div>

### Conclusion and Recommendations

The Hertz Trap offers significant scalability. Future iterations will integrate solar arrays atop the enclosure for continuous field operation, eliminating the need for manual recharging. Furthermore, optimizing mesh density specifically for Spotted Lanternfly geometry will ensure a more reliable circuit completion. These advancements aim to maximize capture rates and long-term durability in agricultural environments.

The Hertz Trap is a promising solution to the continuous strain the SLFs put on the vineyard industry.

According to our clients, E\&J Gallo Winery, they stated that another company they have been working with has provided a similar product, a form of “Bug Zapper” that can be placed around the vineyard and passively kills all of the SLFs. The Hertz Trap’s next step in development would be to verify its efficiency, discovering its ideal frequency range and volume to attract the largest number of SLFs.

Once that field experiment is concluded and the data drawn, the Hertz Trap will need to be optimized. The electrical components can be compacted into a custom circuit board, fueled by one rechargeable battery by the solar panels. Additionally, there would be a benefit for an additional low-density mesh on the outermost legs to ensure only the SLFs get in without debris accidentally activating the zap.

Future iterations should also investigate selectivity, ensuring the trap does not harm beneficial insects, as well as long-term weatherproofing for extended outdoor operation.