---
layout: post
title: "IEEE Conference RO-MAN2018 paper accepted"
date: 2018-06-14 13:32:20 +0300
description: Recovering from External Disturbances in Online Manipulation through State-Dependent Revertive Recovery Policies
img: spai_no_reco.jpg # Add image post (optional)
fig-caption: Our introspective system # Add figcaption (optional)
tags: [HDP-HMM, Recovery, Introspection] # add tag
---
## Abstract
Robots are increasingly entering uncertain and unstructured environments. Within these, robots are bound to face unexpected external disturbances like accidental human or tool collisions. Robots must develop the capacity to respond to unexpected events. That is not only identifying the sudden anomaly, but also deciding how to handle it. In this work, we contribute a recovery policy that allows a robot to recovery from various anomalous scenarios across different tasks and conditions in a consistent and robust fashion. The system
organizes tasks as a sequence of nodes composed of internal modules such as motion generation and introspection. When an introspection module flags an anomaly, the recovery strategy is triggered and reverts the task execution by selecting a target node as a function of a state dependency chart. The new skill allows the robot to overcome the effects of the external disturbance and conclude the task. Our system recovers from accidental human and tool collisions in a number of tasks. Of particular importance is the fact that we test the robustness of the recovery system by triggering anomalies at each node in the task graph showing robust recovery everywhere in the task. We also trigger multiple and repeated anomalies at each of the nodes of the task showing that the recovery system can consistently recover anywhere in the presence of strong and pervasive anomalous conditions. Robust recovery systems will be key enablers for long-term autonomy in robot systems

### Two examples (pick-and-place and open-and-close-drawer) in which a human collaborator accidentally collides the robot. The introspection system identifies an anomaly (see bottom left plots) and triggers a recovery behavior (see the fluorescent node in the graph on the right)
![pick-and-place]({{site.baseurl}}/assets/img/pnp.jpg)
![open-and-close-drawer]({{site.baseurl}}/assets/img/open_drawer.jpg)
This work showed the ability of a system to recover from unmodeled and accidental external disturbances that can’t
be anticipated. Such disturbances will be more common in shared human-robot workspaces. Our work demonstrated
that our recovery strategy in connection with our previous introspection framework recovered 88% of the time from accidental human and tool collisions under single-anomaly and multiple-anomaly scenarios per node. The results indicate the
system can recover at any part of the task, even when it is abused and multiple anomalies occur consecutively. From the
experiments, we can see that even when in cases where the robot is in constant duress, the robot recovers consistently.
Such robustness will play a role in enabling robots have increasing levels of long-term autonomy.

