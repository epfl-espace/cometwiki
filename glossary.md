---
title: Glossary
description: Description of specific words in the context of concurrent engineering
published: true
date: 2022-07-21T14:07:43.494Z
tags: 
editor: markdown
dateCreated: 2022-05-27T12:53:34.844Z
---

# Glossary
## A {#a}
- **AIV** [acr.]: Assembly, Integration, and Verification
## B {#b}

## C {#c}
- **CDF** [acr.]: Concurrent Design Facility.
- **CDHS** [acr.]: Command and Data Handling System.
- **CE** [acr.]: Concurrent Engineering.
- **CE Software** [noun]: Program made to share data during a CE session. Examples: COMET (with Excel extension), ValiSpace, etc.
- **CoG** [acr.]: Center of Gravity, also called center of mass, fictive coordinate where the resulting gravitational force applies 
- **Concurrent** [adj.]: Design done in parallel, at the same time, and with conflicting requirements for all subsystems that force trade-offs and compromises.
- **ConOps** [acr., noun]: Concept of Operations. High-level, visual description of the phases of the mission.
- **COTS** [acr., adj.]: Commercial Off the Shelf (opposite of "developed in house" or [SRAD](#s))
- **Customer** [noun]: Person, or company asking for the session to take place. They bring the needs and high level requirements and can accompagny the experts and SEs during the session to answer questions, validate chocies, refine requirements, etc.
## D {#d}

## E {#e}
- **Element** [noun]: Part of a subsystem. Each element is defined by parameters.
- **Expert** [noun]: Participant to the CE session. Usually assigned to one subsystem.

## F {#f}
- **Facilitator** [noun]: Systems engineer that conduct the CE session, make sure every experts follow the synchronization process, that data is up-to-date, exchanged, and that the team's morale creates an efficient and pleasant working atmosphere.
- **Finite States** [noun]: List of states in which the system, or the subsystems, can be. E.g: mission phases, system modes, etc. Finite states can be combined to create sub classes of states, some of which can be forbidden (impossible). 
## G {#g}
- **GS** [acr.]: Ground Station.
- **GTO** [acr.]: Geostationary Transfer Orbit.
## H {#h}

## I {#i}
- **Isp** [acr., parameter]: Specific Impulse [s]

## J {#j}

## K {#k}

## L {#l}
- **LCROSS** [acr.] Lunar CRater Observation and Sensing Satellite
- **LLO** [acr.] Low Lunar Orbit
- **LOI** [acr.] Lunar Orbit Insertion
- **LRO** [acr.] Lunar Reconnaissance Orbiter
## M {#m}
- **Model** [noun]: The model of a system includes all information used to define it. All the subsystems, elements, parameters, states rules, etc.
- **Modes** [noun]: System modes. State in which an equipment, subsystem, system, can be. E.g: Launch mode, Nominal, Safe, Standby, Active, Passivated, etc.
- **MoI** [acr.] Moment of Inertia [kg*m^2^]

## N {#n}

## O {#o}

## P {#p}
- **Parameter** [noun]: Physical properties of an element that allow to describe it. Each parameter has a unit. E.g: mass [kg], volume [m^3^], power [W]. New parameters can be defined in the CE software.
- **Publish** (onto) [verb]: A task for the systems engineers. Once experts have pushed their newest values, SEs will verify them, make sure they are reasonable (in the expected order of magnitude). SEs can use the values to create budgets estimate and compile them to push the values of the parameters they own. Finally once verified, SEs will publish the values which will in fact share them onto the CE software and allow all experts to satrt a new iteration by pulling the new values.
- **Pull** (from) [verb]: To synchronize from the CE software, to one local, working copy. After pulling, experts can design their subsystems but their newest values are not synchronized with the others.
- **Push** (to) [verb]: Once experts get at the end of one design iteration, they can push their newest values to the CE software. Values are not yet shared with other experts, not until they are published by the SEs.

## Q {#q}

## R {#r}

## S {#s}
- **SE** [acr.]: Systems Engineer(ing).
- **Session** [noun]: A design session is attended by experts, SEs, facilitators, and customers, to design a product/mission/service using concurrent engineering. Sessions have a defined duration, several sessions are usually required to perform a study.
- **SF** [acr.]: Safety Factor (Acceptable value over max value). Not the same as a Margin of Safety.
- **SRAD** [acr., adj.]: Student Researched and Developed (opposite of [COTS](#c))
- **Study** [noun]: Whole concurrent engineering process for one project, with its own objectives. A study lasts several sessions, usually spread on several days.
- **Subscribe** (to) [verb]: For parameters that have an impact on one's subsystem's design, ask the CE software to pull the updated value of the parameter at each synchronization. The subscription process shall be done at the beginning of the session, but experts can subscribe to a parameter at anytime. The value will be updated only after a full round of synchronization: push, publish, pull.
- **Subsystem** [noun]: Part of the system being designed by concurrent engineering. Each subsystem has one or more expert(s) assigned to them to design them. Subsystems are made of elements (equipment level).

## T {#t}
- **TRL** [acr.]: Technology Readiness Level.
## U {#u}

## V {#v}

## W {#w}
- **Workstation** [noun]: Place equipped with a computer, useful software, and communication means, that allow an expert to work during a CE session.
## X {#x}

## Y {#y}

## Z {#z}
