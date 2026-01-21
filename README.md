# 2.4 GHz CMOS Low Noise Amplifier Design (180 nm)

This repository contains the design and simulation study of a **2.4 GHz CMOS Low Noise Amplifier (LNA)** implemented using **180 nm CMOS technology**.  
The work focuses on analyzing gain, noise figure, linearity, and stability using **cascode** and **folded-cascode** topologies combined with the **Modified Derivative Superposition (MDS)** technique.

This project was carried out as part of an academic study and is based on circuit-level simulations.

---

## Overview

Low Noise Amplifiers are a critical part of RF receiver front-ends, directly affecting receiver sensitivity and overall system performance.  
This work investigates linearity improvement techniques for LNAs operating at 2.4 GHz by applying Modified Derivative Superposition (MDS) to:

- Cascode LNA
- Folded Cascode LNA

The designs are evaluated through simulation using standard RF performance metrics.

---

## Key Design Aspects

- Technology: CMOS 180 nm
- Operating Frequency: 2.4 GHz
- Topologies Studied:
  - Cascode LNA with MDS
  - Folded Cascode LNA with MDS
- Linearity Enhancement Technique:
  - Modified Derivative Superposition (MDS)
- Input/Output Matching:
  - LC matching networks
  - Inductive source degeneration

---

## Performance Metrics Analyzed

The following parameters are evaluated through simulation:

- Gain (S21)
- Noise Figure (NF)
- Stability Factor (K)
- Input Third-Order Intercept Point (IIP3)
- 1 dB Compression Point (P1dB)
- S-parameters

A comparative analysis is performed between cascode and folded-cascode architectures.

---

## Results Summary

- Both architectures achieve gain above 30 dB at 2.4 GHz
- Noise figure is maintained below 0.6 dB
- Folded cascode with MDS shows improved linearity (higher IIP3)
- A trade-off is observed in P1dB for enhanced linearity
- Stability conditions are satisfied across the operating band

Detailed plots, schematics, and numerical results are provided in the project paper.
