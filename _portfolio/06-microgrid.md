---
title: "Microgrid Simulation with Intentional Islanding"
excerpt: "Simulink model of a neighbourhood microgrid with solar, battery, and generator supply that keeps power on when the main grid fails.<br/><img src='/images/microgrid-dashboard.jpg' width='300'>"
collection: portfolio
---

**Course:** EEE 306 Power System I Laboratory, BUET (team project)  
**Tools:** MATLAB/Simulink

## Overview

When the main grid goes down, connected neighbourhoods lose power. This microgrid supplies a locality on its own when that happens.

## Design

- **Generation:** a photovoltaic system, battery storage, and a backup generator.
- **Islanding:** both automatic and manual disconnection from the main grid.
- **Monitoring:** a dashboard showing battery charge, grid voltage, frequency, and load power.

![Control and monitoring dashboard](/images/microgrid-dashboard.jpg)

## Outputs

Simulations showed the microgrid supplying the locality without interruption during grid outages.

![Power flow during islanding](/images/microgrid-power.jpg)
