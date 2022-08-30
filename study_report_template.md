---
title: Study Report Template
description: Add here a short description of the mission or system designed
published: true
date: 2022-07-21T14:05:52.116Z
tags: 
editor: markdown
dateCreated: 2022-07-08T08:57:05.001Z
---

# Study Title
**Subtitle/Mission/Subsystem Name**

### Report Status
**Version**: D0X (for drafts) / I0X (when issued, i.e., already listed)
**Reviewed by**: David
**Review date**: 08/07/2022
**Review status**: ❌TO-DO 🔧DRAFT ✅DONE

---

>Use this template to start gathering information prior to a new planned study and during the facilitation of concurrent design sessions. For this, **duplicate this page** and **add it to the [Previous CE Studies](/ce_studies) list**. For reference on how to fill the different sections of the report, check the [DUMBO mission](/dumbo) study report. 
{.is-info}

>In the 'Page' tab, make sure to add a **short description** and **tags** representative of key features of the study.
{.is-info}

> Avoid as much as possible duplicating information between sections.
{.is-warning}

> The executive summary must be a standalone, self-explanatory section of the report.
{.is-warning}

*[Write here a short abstract describing the context of this study.]*  

The following contains all the relevant informating resulting from this study, from the [context](#background) and [mission objectives](#study_objectives) to [lessons learned](#lessons).

For a list of terms and acronyms often used, check the [Glossary](/glossary) section. 

*[Add mission patch here]*

This study was performed at eSpace Concurrent Design Facility by the following team:

|Name       | Affiliation |  Role |
| --------- | ---------   | ------------- | 
| Name LastName | eSpace | **Team Leader/Facilitator**  |
| Name LastName | eSpace | **Team Leader/Facilitator**  |
| Name LastName  | EPFL | Attitude & Orbit Control (AOC)  |
| Name LastName  | EPFL | Communications & Data Handling (CDH)  |
| Name LastName  | EPFL | *[Add as many disciplines as required]*  |


Under the responsibility of:
N. LastName, eSpace, *Study Coordinator*

With the technical support of:
N. LastName, eSpace, *Systems Engineering Support*
N. LastName, eSpace, *Logistics & Admin Support*

## Introduction {#intro}

### Background {#background}
*[Describe here how this study came about]* 

### Objective
*[Write here a short paragraph on the objective of the mission/system to be designed]* 

### Scope
*[Describe the scope of the mission/system to be designed]* 

## Executive Summary {#executive_summary}

*[The executive summary is a brief compilation of the most relevant aspects of the study]*   

### Study Objectives {#study_objectives}

*[Expand on the objectives of the study]*


### Requirements and Design Drivers

*[Describe here main mission and system requirements as defined prior to the study]*

|Ref       | Requirement
| --------- | ------------   |
| E.g.: MIS-M-001 | E.g.: The mission shall use Ariane 6 or Vega-C | 

*[Describe here main mission and system requirements design drivers and constraints prior to the study]*

### Mission/System Design

*[Summarize here the outcome of the study]*


## Results
> Expand here on the results of the study. Create one subsection per subsystem/discipline. Each subsection shall follow the same structure: 1)list of flowed-down subsystem requirements (what the subsystem needs to do and how well). 2)tradeoffs and justifications, and 3)results
{.is-info}

*[Some sections are written below as a refence]*

### Trajectory Analysis {#trajectory_analysis}
Requirements:
- *E.g.: Shall provide a trajectory to correctly enter the lunar orbit and its duration.*

*[Tradeoffs]*

*[Justifications]*

*[Results]*

- [Link to lessons learned on **trajectory analysis** during this study](#l_trajectory_analysis)
{.links-list}

### Configuration {#configuration}
Requirements: 
- *E.g.: Shall identify and create the configurations of the spacecraft*

*[Tradeoffs]*

*[Justifications]*

*[Results]*

- [Link to lessons learned on **configuration** during this study](#l_configuration)
{.links-list}

### Structures & Mechanisms {#structures_mechanisms}
Requirements:
- *E.g.: Shall estimate the loads applied depending on the configuration and deduce the structural mass*

*[Tradeoffs]*

*[Justifications]*

*[Results]*
 
 - [Link to lessons learned on **structures and mechanisms** during this study](#l_structures_mechanisms)
{.links-list}
 
### Propulsion {#propulsion}
Requirements:
- *E.g.: Shall define the propulsion system and the propellant type*

*[Tradeoffs]*

*[Justifications]*

*[Results]*

- [Link to lessons learned on **propulsion** during this study](#l_propulsion)
{.links-list}


### AOCS {#aocs}
Requirements:
- *E.g.: Shall choose equipment based on required pointing and rotation rate requirements and thrust/ delta-v requirements*

*[Tradeoffs]*

*[Justifications]*

*[Results]*

- [Link to lessons learned on **AOCS** during this study](#l_aocs)
{.links-list}

### CDHS {#cdhs}
Requirements:
- *E.g.:Shall define the equipment needed based on the data rates needed for ground station contact and inter satellite links*

*[Tradeoffs]*

*[Justifications]*

*[Results]*

- [Link to lessons learned on **CDHS** during this study](#l_cdhs)
{.links-list}


### Power {#power}
Requirements:
- *E.g.: Shall gather power needs and operation depending on system modes from all subsystems*

*[Tradeoffs]*

*[Justifications]*

*[Results]*

- [Link to lessons learned on **power** during this study](#l_power)
{.links-list}


### Thermal {#thermal}
Requirements:
- *E.g.: Shall identify operational and survivability temperature range for all equipment*

*[Tradeoffs]*

*[Justifications]*

*[Results]*

- [Link to lessons learned on **thermal** during this study](#l_thermal)
{.links-list}

### Budgets (system level) {#budget}
Requirements:
- *E.g.: Shall support the other disciplines with their design*

*[Summarize system level budgets in the table below]*


| Subsystem | Mass [kg] | Contingency [%] | Mass w/ contingency |
|---|:---:|:---:|:---:|
| Thermal | | 50 | 16,7 |
| Payload | | 20 | |
| Power | | 40 | |
| Propulsion | | 15 | |
| Structure & mechanisms | | 20 | |
| CDHS | | 20 | |
| AOCS |  | 10 | |

- [Link to lessons learned on **systems engineering** during this study](#l_systems_engineering)
{.links-list}

> Based on the scope of the study, other sections shall be added to the report including: customers' specifications, specific payloads, ground segment, operations, [AIV](/glossary#a), risk assessment,  costs, etc.
{.is-warning}


### Post-Study Debrief {#psd}
*[Write here about how the study went, issues and challenges you encountered, how (logistical, ops, technical) problems were solved, warnings about results (what still needs to be investigated deeper, where broad assumptions where made, what were some critical trade-offs impacting the whole design), recommendations for follow-up studies (what to do next),etc.]* 

*[This section could also contain a summary of lessons learned]*

## Technical Lessons Learned {#lessons}

> For general lessons learned about concurrent engineering, go to the [useful_tips](/useful_tips) page (accessible to eSpace staff only).
{.is-info}

*[To complete during and at the end of the study: add below all technical lessons learned associated with the different disciplines/subsections]*

### Trajectory Analysis {#l_trajectory_analysis}
- *Add lessons learned*
### Configuration {#l_configuration}
- *Add lessons learned*
### Structures & Mechanisms {#l_structures_mechanisms}
- *Add lessons learned*
### Propulsion {#l_propulsion}
- *Add lessons learned*
### AOCS {#l_aocs}
- *Add lessons learned*
### CDHS {#l_cdhs}
- *Add lessons learned*
### Power {#l_power}
- *Add lessons learned*
### Thermal {#l_thermal}
- *Add lessons learned*
### Systems Engineering {#l_systems_engineering}
- *Add lessons learned*