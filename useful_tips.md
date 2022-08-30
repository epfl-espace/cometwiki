---
title: Useful Tips
description: Useful tips for eSpace staff on how to prepare, conduct, facilitate a CE session. Includes lessons learnt from previous sessions.
published: true
date: 2022-06-17T07:54:20.127Z
tags: tips
editor: markdown
dateCreated: 2022-05-27T10:18:45.471Z
---

# Useful tips
All useful information for eSpace staff on how to prepare, conduct, facilitate a CE session.

## Purpose of this list
Lessons learnt are compiled by facilitators during each CE sessions. They are then sorted and uploaded to the wiki. This section contains general lessons learnt about concurrent engineering, sorted into four categories:
1. Infrastructure
1. CE preparation
1. CE workflow
1. Others

Technical lessons learnt specific to one session are compiled in the session's own mission log. Have a look at them under [the list of previous CE sessions](/ce_studies).

## Infrastructure lessons learnt
- The available wifi network can be pushed to its limit during a CE session. One needs a **good internet connection**, via an ethernet LAN router/switch  if needed, to have enough bandwidth for the whole group. 
- When hosting companies, one needs a more **professional CDF setup**, with better [workstation](/glossary#w) with double screens, more display capabilities, and higher-quality connection to the internet. The configuration of the room has to allow for interactions between the participants.
> The CDF at eSpace can host a maximum number of around 10 participants plus three facilitators.
{.is-info}
- When connected to another CDF room (eg. for [2022 CEC](/dumbo)) : One needs a good **audio system** in the room. , with easy ways to ask questions at each [workstation](/glossary#w). Ideally using equipment the participants are already familiar with (their own).
- Use work stations with **engineering software** already installed (for CAD, FEM, CFD, data handling and plotting, etc.). A list of open source programs that can be installed or used online is available [here](/sw_index).

## Sessions' preparation
- Do not forget the **preparation** (systems engineers’ job), think about the product tree in advance, prepare a high level [ConOps](/glossary#c), make sure to understand the requirements and explain them well to the subsystems’ experts. Visual support is appreciated to convey the information.
- Speaking of visual support, it may be a good idea to have an example of **how does the data flow** during the CE session. Have every [experts](/glossary#e) understand which parameters impact their subsystem (so they shall [subscribe](/glossary#s) to them) and which ones from their subsystem impact others (so they know with whom to speak to if it is modified).
- Anticipate documents **sharing capability** (a folder on a server like google drive or similar) and a way to quickly share links and messages (a group on webex teams, a slack group or any other communication service that could do the job).
- Check that all the **necessary parameters** are on the CE software. Forgetting one means some subsystems could wait on values no one is trying to put online. Also make sure there are no double parameter. Subsystems that are subscribed may be confused and if one is not updated but the other is, it may result in conflicts. For information that is more difficult to model in the CE software (eg. connections between subsystems, position in the spacecraft, etc.), either create new parameters with clear names and units, or iterate directly with the subsystems involved. The latter is manageable only for small numbers of parameters. 
> Quick fix if a parameter was forgotten: add the parameter to the relevant subsystem(s)' element in the CE software and asked best estimates from the subsystem(s). The value will hopefully be already better than what would have been a 1st iteration estimate. Then follow the regular CE workflow. {.is-info}

## CE workflow
- Start with **“top-down” estimations** of mass (and power, and others) budgets and then build the first design iteration upon these values. One can use literature to find good first estimates.
- Make sure there are values for each and every parameters from the first iteration on ! Even very rough estimates: the process has to start somewhere. Values with zeros cannot be used for the design of subsystems. And check that all the **necessary parameters** are on the CE software (see Sessions' preparation).
- The **iteration loop** really starts with everyone sharing the same values (put estimates if needed, do not forget any or leave any at 0 (see above). Then every subsystem iterates and at the end everyone pushes their values and notify the SEs.
- Take the **time** needed for the publication and synchronization steps this loop is really a critical moment during which everyone needs to be focused. At the beginning of an iteration/of a day, experts shall “re-build” their local working file by pulling values from the CE software.
- Once subsystems have shared their values (push), SEs shall take the time needed for the **publication** step: checking the values, building the budgets, entering the values that are based on these budgets and owned by SEs, before publishing. Participants shall not iterate during this time, they shall wait for the publication to be done and only then they can synchronize by pulling the new values.
- For the **dry mass budget margins**, SEs gather the values from each subsystem and add a margin dependent on the confidence they have in the provided values (min 20% but can be as much as 100% margin). Then, add another 20% margin at system level for the total dry mass.
- For the **wet mass budget margins**: add a very little margin on the Delta v value (it is then used in an exponential formula to find the propellant mass). But one can easily add 20% margin on the propellant mass computed from those Delta v.
- Do not rush for a **CAD**. First do a quick functional diagram to understand location requirements and at the end have a CAD to assemble everything. A CAD is only useful for inertia calculation and payload fairing volume check (and for visual motivation of the team). Start with a very basic CAD or reuse an image from a similar mission at first.
- It could happen that iterating does not yield the desired **convergence** of the design in terms of mass, cost, power (all the budgets), but rather the design could start diverging. If this is the case, go back to your assumptions and key driver decisions, adjust them before starting again. 
> For example at CEC 2022, the choice of the launcher was a very important decision to make because it changed the trajectory of the spacecraft, which ultimately had a huge impact on the design. By the middle of the week, we changed from Ariane 6 to Vega C because of the performance required and converged to a solution.

> For general CE Workflow  see [Here](/concurrent_engineering#ce_workflow)
{.is-info}




## Other lessons
- During brainstorms, encourage people to stand up, use white board, discuss more, **interact**, and share their ideas. Avoid the case when only facilitators are talking, and make sure every expert can participate equally.
- Always be consistent with **units** and display them clearly.
- Anticipate food and drinks for the **coffee breaks**. Those are important for the morale and team's spirit.
- Know **when to stop**: to take breaks, have lunch, or end the day, otherwise there is always something to do. Breaks and end of days are good moments to finish an iteration and perform the synchronization process.
- Managing the **morale** of the team and the relationships between participants is crucial for the progress of the design. Avoid conlicts, tensions or bad behaviour, to create an efficient and pleasant working atmosphere.
> Even between students, tensions can arise from simple cause like a delay in the synchronization, or two conflicting views on how to handle a problem. Also, during CE challenges, the team shall not compare itself to other teams, or other experts.
{.is-warning}

