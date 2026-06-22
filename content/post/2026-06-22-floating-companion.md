---
title: "Floating Companion"
subtitle: "Exploring the Design Space for Soft Floating Robots in Indoor Environments"
date: 2026-06-22T10:00:00+09:00
draft: false
---

{{< figure src="/images/floating-companion-teaser.png" title="Five soft floating robots in everyday indoor settings: a fish that circles you with a calming touch, a balloon that follows you across floors, a jellyfish that pulses to guide your breathing, an agile robot for playing with a pet while you are away, and a cloud that drifts over to remind you to take a break." >}}

Our paper *Floating Companion: Exploring Design Space for Soft Floating Robots in Indoor Environments* won the **Best Paper Award** at [DIS 2026](https://dis.acm.org/2026/) in Singapore. I am really happy for the team. Mingyang and Yanheng worked on it a long time, and it is nice to see it recognized.

## Abstract

Soft floating robots (SFRs) represent a shift from rigid machines, offering gravity-defying, compliant, and tactile embodiments for indoor cohabitation. However, their development remains fragmented across isolated prototypes, lacking a coherent design vocabulary. Without a systematic understanding of their interactional capabilities, designers struggle to leverage SFRs' unique affordances, and these systems often remain limited to novelty applications that are difficult to integrate into everyday life. To address this, we propose a design space for interaction with SFRs. Informed by an exploratory study with 12 experts from HCI, Design, and Robotics, we identify ten design dimensions spanning physical, interactive, and behavioral properties, along with a range of application scenarios. We further present proof-of-concept prototypes to demonstrate how this design space can support diverse interaction possibilities. This work contributes a structured framework for understanding and designing interactions with SFRs, supporting their integration into everyday indoor environments.

## Summary

Soft floating robots are lighter-than-air robots with soft, helium-filled bodies. Unlike the drones most people picture, they move through a room quietly, make gentle contact instead of avoiding it, and can hover above you without any downwash or noise. Their inflatable bodies can take almost any shape, from a fish to a cloud. The problem is that the research so far has been a scatter of one-off prototypes. Everyone builds their own thing, and there is no shared language for describing how these robots should move, behave, and interact with people. That makes it hard to get past cute demos.

So we sat down with 12 experts from HCI, HRI, design, and robotics, interviewed them, and worked through the transcripts. Out of that we built a design space with ten dimensions:

1. Spatial mobility scope, from close-up interaction to room-scale and even moving between floors.
2. Vertical floating mobility, changing altitude to meet you wherever your body is.
3. Spherical proxemics, treating personal space as a 3D volume the robot can enter from any direction, including from above.
4. Interaction configuration, from one robot and one person to dense swarms where bumping into each other is fine.
5. Interaction targets, meaning who or what the robot engages: you, the room, other devices, or pets.
6. Relationship roles, such as guide, guardian, assistant, or companion.
7. Physical form, the range of shapes an inflatable body can take.
8. Communication modalities, the channels it uses to express itself.
9. Floating motion dynamics, the slow, drifting, slightly unpredictable quality of buoyant movement.
10. Level of proactiveness, from passively reacting to forces to starting an interaction on its own.

The interviews also gave us a set of application scenarios: emotional support and companionship, helping people communicate, setting an ambient mood in a room, assisting with daily tasks, and providing services in public spaces.

We did not want this to stay abstract, so we tied it back to physics. Helium-filled bodies have hard constraints, and we mapped those out in a Physics-Design Dependency Framework, then pulled three practical design principles from it: lean into soft physical contact, use the full 3D volume around a person, and design for animacy so the robot feels alive rather than mechanical. To show the design space actually produces things, we built proof-of-concept prototypes on a flapping-wing platform that put those principles into practice.

If you want the full argument, the figures, and the prototype details, the paper is the place to go.

## Reference

Mingyang Xu, Yanheng Li, Burcu Nimet Dumlu, RAY LC, Giulia Barbareschi, Matthias Hoppe, Jie Li, Kouta Minamizawa, and Kai Kunze. 2026. Floating Companion: Exploring Design Space for Soft Floating Robots in Indoor Environments. In Proceedings of the 2026 Designing Interactive Systems Conference (DIS '26). Association for Computing Machinery, New York, NY, USA, 3377-3396. [https://doi.org/10.1145/3800645.3813051](https://doi.org/10.1145/3800645.3813051)
