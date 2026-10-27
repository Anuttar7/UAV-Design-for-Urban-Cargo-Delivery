# Hybrid VTOL UAV for Urban Cargo Delivery

**Conceptual UAV Design Project**  
**Institution:** Samara University — Winter School / Project  
**Team:** ASIANS  
**Date:** December 2025  
**Team members:** Lin Hanxi, Li Jingxuan, Mujib, Anuttar Jain

## Overview

This project presents a conceptual design for a hybrid vertical take-off and landing (VTOL) unmanned aerial vehicle intended to transport cargo in urban environments. The design combines the vertical take-off and landing capability of rotor-based propulsion with the cruise efficiency of a fixed-wing aircraft.

The stated design goals are to carry a **10 kg payload** over a **5 km radius** and return to base. The project covers concept selection, aircraft configuration, preliminary sizing calculations, component selection, operational safety, and a proposed development roadmap.

## Design concept

The selected configuration combines a fixed wing with three motors and a tilting/rotating propulsion arrangement. The concept is intended to support vertical take-off and landing, transition to forward flight for longer-distance travel, and cargo delivery at a designated location.

Key design choices presented in the project:

- **Hybrid rotor–fixed-wing configuration:** combines VTOL capability with fixed-wing cruise.
- **Primary structure:** predominantly carbon-fibre composite, with smaller quantities of metal and general consumables.
- **Propulsion and control:** three motors and two ailerons are proposed. The presentation describes pitch control through the tail motor, roll control through the ailerons, and yaw control through differential motor action and roll.
- **Delivery sequence:** vertical take-off, transit to the delivery area, cargo drop, and return to base.
- **Cargo bay:** intended to accommodate a payload that can be released at the designated delivery location.

The conceptual appearance and flight phases are illustrated in the presentation, including the vertical take-off configuration and the long-distance flight configuration (pages 3–5).

## Preliminary design targets

| Parameter | Value stated in the presentation |
|---|---:|
| Payload | 10 kg |
| Mission radius | 5 km |
| Gross weight | 20 kg |
| Cruise speed used in calculations | 30 m/s |
| Airfoil | MH115 |
| Lift-to-drag ratio, \(C_L/C_D\) | 90 |
| Motors | 3 |
| Battery mass | 3 kg |
| Battery rating | 22.2 V, 36,500 mAh |
| Battery energy stated in presentation | 600 Wh |
| Flight controller | Axisflying Argus Pro |

These are preliminary presentation values, not verified performance specifications. They should be reconciled and validated through detailed aerodynamic, propulsion, structural, and energy calculations before being used for engineering decisions.

## Preliminary calculations and component selection

The presentation includes first-order estimates for mission energy, component masses, and selected hardware. It states an energy requirement of approximately **20 kJ (5.55 Wh) per round trip**, and **55.55 Wh for ten round trips**. A battery with a stated energy of 600 Wh is listed.

The preliminary component list includes:

- Carbon-fibre composite structural material.
- Metal and general consumables.
- Three motor–propeller units.
- One battery.
- A flight-control board and navigation/airspeed sensors.
- Servo motors and rotating mechanisms.

A preliminary cost table gives a **total estimated cost of USD 3,005**. This is a conceptual estimate based on the components and quantities listed in the presentation; it is not a supplier-quoted or validated bill of materials.

## Operational workflow and safety

The project proposes a three-level safety management structure:

1. **Decision-making level:** a safety committee establishes operating standards and approves flight plans.
2. **Execution level:** flight-control, operations, and maintenance teams carry out procedures and equipment inspections.
3. **Supervisory level:** safety inspectors monitor operations and conduct post-flight audits.

Additional safety measures described in the presentation include:

- A standby battery and backup flight-control system.
- Predefined emergency landing locations and emergency contacts.
- Fault-simulation training for events such as motor failure and signal interruption.
- Fire-extinguishing equipment in battery charging areas.
- Battery lifecycle tracking and a proposed retirement limit after 200 charge–discharge cycles.

These measures are proposed concepts from the project presentation and would require a detailed safety case and applicable regulatory review before operational deployment.

## Development roadmap

The presentation identifies the following next steps:

- Detailed structural design, including load-bearing optimisation.
- Further aerodynamic refinement.
- Design of a comprehensive autonomous flight-control system.
- Selection and design of the propulsion-system rotating mechanism.
- Construction of a physical prototype and flight-verification testing.
- Iterative improvements based on flight-test results.

## Project deliverable

The accompanying `Presentation.pdf` documents the concept selection, conceptual appearance, company workflow and safety approach, preliminary cost estimates, sizing calculations, force diagrams, and future development plan.

## Team

- Lin Hanxi
- Li Jingxuan
- Mujib
- Anuttar Jain

## Disclaimer

This repository documents a **conceptual design study**. The performance targets, energy estimates, component specifications, control strategy, and cost figures are reproduced as presented in the project material and have not been independently validated here. They should not be treated as evidence of a flight-ready or certified aircraft design.
