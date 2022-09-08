---
title: Start here
description: Learn everything related to concurrent engineering, its method, facility, procedure, workflow, etc.
published: true
date: 2022-09-08T08:42:08.997Z
tags: 
editor: markdown
dateCreated: 2022-05-27T10:10:11.211Z
---

# Concurrent Engineering
## Definition {#definition}


There are many definitions of the meaning of “Concurrent Engineering” (CE) the following one is used at European Space Research and Technology Centre (ESTEC): 
> "**Concurrent Engineering**  is a systematic approach to integrated product development that emphasizes the response to customer expectations. It embodies team values of co-operation, trust and sharing in such a manner that decision making is by consensus, involving all perspectives in parallel, from the beginning of the product life-cycle."

There are also many other simpler definitions like this one:
> “**Concurrent engineering**, also known as simultaneous engineering, is a method of designing and developing products, in which the different stages run simultaneously, rather than consecutively. It decreases product development time and also the time to market, leading to improved productivity and reduced costs.”


Essentially, CE provides a collaborative, co-operative, collective and simultaneous engineering working environment.

![image.png](/ce_.png){.align-center}


More about history of Concurrent Engineering: https://www.researchgate.net/publication/229509759_Concurrent_Engineering 

## Concurrent design {#concurrent_design}
> Concurrent design is a system engineering technique for design, development and technical management of a “product” based on: 

- Real-time/simultaneous, co-located interactions of several specialists/disciplines
- Complete sharing of “product” data
- Team work and decision by consensus
- Active participation of the customer/user

> For space systems the “product” is the space mission design or the spacecraft or any of its components (incl. payload)
{.is-info}

The concurrent design approach is based on five key elements:
- **a process**: Processes are the mechanisms used to run design sessions, such as the system development processes being considered and their specific implementation in facility operations. Projects may follow spiral development processes, waterfall development processes, combinations of these two, and any other development process of choice.

- **an infrastructure**: is the physical embodiment of the facility, in terms of rooms and space used to facilitate the succession of interaction, concurrency, design work, and discussion, with processes running in parallel and oftentimes distributed in space and time – with study participants that are potentially also spread through the globe (Concurrent Design Facility (CDF)). An article about establishing [Concurrent Design Facility](https://bit.ly/3QbXpBl). Below an image showing the layout of the [CDF](/glossary#c) at ESA/ESTEC (M. Bandecchi et alli, "The ESA/ESTEC Concurrent Design Facility", In: Proceeding of EuSEC (2000).). See [our adaptations for the eSpace CDF](/cdf).

![esa_cdf_layout.png](/images/esa_cdf_layout.png =700x){.align-center}

- **a multidisciplinary team**: is a core subsystem of a concurrent facility and represents one of the elements of major value and major source of complexity at the same time. The team includes experts leading design sessions, whom are educated in operating a [CE](/glossary#c) environment as systems engineers, and experts that work in design teams and bring in disciplinary knowledge from their departments of origin. The figure above shows the types of experts that are expected during the desing of a space mission.

- **Software/hardware infrastructure:** includes hardware and software installed in a CE facility. These include infrastructure for data storage, data processing, data sharing, visualization tools, specialist design software, collaboration tools, videoconferencing, and other means.
- **A Concurrent Design Tool** - a software program that enables engineering teams in the concurrent design facility to efficiently exchange data and conduct research.

> More about using Concurrent Engineering approach at ESA/ESTEC: https://bit.ly/3MAKVAc
{.is-info}

## CE Workflow {#ce_workflow}

Below you will find details as to what to do [before](#before), [during](#during), and [after](#after) a new concurrent design study. 

### Before {#before}

### Step 0: Roles {#roles}

The very first thing to do in preparation for an upcoming concurrent design study is to clarify the **roles** of the staff members overseeing it. These roles tend to include: study coordinators, session facilitators, system engineers, and technical or logistical support.   

At times, multiple roles will be given to the same person. For example, session facilitators may act as systems engineers if their expertise lie within the scope of the mission or system to be designed. The list below defines the main responsibilities for each of these roles. Other roles beyond the ones listed can be defined based on the specific needs of the study. 

- **Study coordinators**: top-level managers or initiators of a concurrent design study; in charge of identifying the need for a study, organizing it, assigning roles, and defining expected outcomes and constraints. 
- **Session facilitators**: in charge of overseeing the development of each session with the objective of maintaining an effective and efficient flow of information between subsystems. 
- **System engineers**: in charge of the technical coordination of a study.
- **Technical support**: in charge of providing specific *ad hoc* expertise  based on the needs and requirements of the mission or system to be designed.
- **Logistical support**: in charge of assisting with the logistics of a study (booking of rooms, external communications, infrastructure, etc.) 


#### Step 1: Preparation {#prep}

Before starting the design cycle, system engineers (SEs) and session facilitators (SFs) shall prepare and perform a preliminary analysis on their own based on a request by a study coordinator (SC). The goal of this step is to define a **starting point** or a baseline for the study.  

This analysis includes defining the main **top-level requirements and constraints** for the mission and/or system to be designed. It is also necessary as part of defining a starting point to declare a set of **assumptions** that will be provided to the team and that will act as a baseline for the design (e.g., some subsystems or mission components may be considered out of scope and therefore treated as black boxes or dummy objects). 

In essence, a good starting point should define the **mission or system architecture**.

> Architecture drivers (often): trajectory and propulsion. But can also be the main goals of the mission (scientific, commercial, others).
{.is-info}

> Whenever possible it is good practice to refer to previous missions with similar characteristics or initial requirements! Check the list of [previous CE studies](/ce_studies).
{.is-info}

> Also, before the session starts, you need to create a mission/system model in the Concurrent Design Tool.
{.is-warning}

The SC must make sure that the relevant **experts** and **subsystem specialists** will attend the concurrent engineering sessions. The list of relevant experts/specialist is defined with input from the SFs/SEs of which roles are required.

In addition, SEs/SFs should define a timeframe for the study: when it will take place and how many session they deem the study requires. 

> Providing a **timeframe** for the study is critical. How long a study should be is always a bit random. At ESA, concurrent design studies often end after 8 sessions (each session being 4 hours long). Avoid falling into the trap of the never-ending refinement cycle by defining a hard end-date for your study. 
{.is-warning}

All the information gathered and details defined as part of this step shall be put together in a slide deck to be used during the [kick-off](#kickoff) of the study. 

#### Step 2: Setup

To set up the infrastructure for the CE sessions, SF/SEs, together with logistical support if needed, shall follow the [preparation checklist](/cdf#preparation_checklist) for how to setup the CDF. Beware that some actions are required several days/weeks prior to the start of the study.

The previous checklist includes material and equipment, as well as additional furniture (table, etc.), software installation, and logistics recommendations.

### During {#during}

#### Step 3: Kick-off {#kickoff}

A kick-off meeting is held in which SEs/SFs and often the customer presents to the rest of the team the rationale for the study; i.e., they describe why the mission/system is relevant, provide context and scope about mission goals, requirements and constraints, and introduce the results of a potential first system analysis conducted during [peparation](#prep).

#### Step 4: Start the design

Definition of [ConOps](/glossary#c), timeline, [modes](/glossary#m) of operations and changes in mission analysis.

#### Step 5: First iteration

Calculation of first budgets based on starting points.
Overall System synthesis is based on the following budgets:
•	Mass budget
•	Delta-V and Propellant budget
•	Power and Energy budget
•	Data budget
•	Link budget
•	Pointing error budget
•	Cost

> Mass budget is managed by System Engineers.
{.is-info}

> It is necessary to implement contingencies to cover the uncertainties. The contingency will depend on the confidence in the (sub)system you are designing and the readiness level of the technology used. 
{.is-info}

#### Step 6: Further iterations and refinement

After the first iteration, the engineers responsible for each of the subsystems make improved calculations on their own subsystem design based on the new values received from other subsystems (e.g., subssytem masses, power, volume, new lower-level requirements, new constrainsts, etc). 

This process becomes an iterative loop.

Depending on the study, sometimes the customer may require to study multiple options. 

> This is the moment when Concurrent Engineering magic happens.
Specialists exchange data. They [push](/glossary#p) data to Central Repository (Concurrent Design Tool). This data becomes available for the other specialists after system engineers review it and [publish](/glossary#p) it for everyone. Each specialist can then [pull](/glossary#p) this data to perform calculations and share their results.
{.is-info}

> The looping process can happen at the request of the specialists or the systems engineers, when new data is available in all subsystems, and they have reached a new step of design refinement. A loop **shall** happen at the end of each [session](/glossary#s), to make sure the changes are saved on the CE software and all subsystems can start with the most up-to-date values at the beginning of the next session. The end of a session is also a good milestone to take a moment for a post-session debriefing with the team (see below).
{.is-info}

> Iterations may lead to the changes in the mission/system architecture. 
{.is-warning}

> The number of iterations required is determined by system engineers. You can finish the process when the difference between the values obtained during the last iterations is covered by margin.
{.is-success}

6.1 **Post-session debriefing**

A CE session generally last half a day or a full day. A lot of progress can be achieved by a team in this amount of time. Also the gap in between two sessions can vary from one night, to several days or weeks. It is thus important to alocate time for a post-session debriefing (PSD) with all participants involved to disseminate information about the design decisions made during the previous session. It is recommended to allow each subsystem to present their progress in a few minutes. Having every participants prepare one slide with visuals to support their talk can also be beneficial. 

The PSD keeps everyone up-to-date with the current status of the study and can trigger questions to be tackled during the next session. It can also help in building up the [final report](#after) by keeping track of the work, the assumptions taken, and the trade-offs made during the study.

#### Step 7: Final Presentation/ Final check

At the end of the study, once the end-date for the study is reached, asking every subsystems to compile and present their final designs to the rest of the team is a good way to close the project. It also allows systems engineers to present a final mass budget with data from the subsystems (with relevant contingencies added). This is all useful information for the [final report](#after).

The final check shall include a screening of the [requirements](#before) to verify that the designed mission fulfills them. The customer(s), having commissioned the study, shall then validate that the design indeed answer their needs.

### After {#after}
#### Step 8: Post-study activities

The last step of a study is the report writing. A [report template](/study_report_template) is available to eSpace staff to create a new page on the wiki. The report helps structure the outcomes of the study, provides lessons learned, assumptions, and data for future studies, and might be a required deliverable under a project contract.

> Creating a clean and understandable report is worth it ! For yourselves and for future studies.
{.is-success}

> Make sure to block some time also with the participants at the end of the study to synthetize their results and include them in the report.
{.is-warning}

## CE Software {#ce_sw}

- **COMET** - open-source concurrent design platforms. It’s used at ESTEC. https://bit.ly/3O2lKbq

- **Valispace** - a digital productivity tool that helps your engineering team share up to date dynamic data quickly and easily. Some companies, for example OHB and Skoltech, use Valispace for Concurrent Design Sessions. www.valispace.com

- Many others can be available.



