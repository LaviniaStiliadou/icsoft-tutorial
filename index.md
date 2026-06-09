---
title: About
layout: default

navigation_weight: 1
---

# ICSOFT 2026 Tutorial: Collaborative Model-Driven Quantum Software Engineering: A Hands-On Tutorial with Qonstruct

## About
This website hosts the official material for the tutorial **"Collaborative Model-Driven Quantum Software Engineering: A Hands-On Tutorial with Qonstruct"**, which will be held in Porto (Portugal) during the 2026 edition of the International Conference on Software Technologies (ICSOFT).

---

## Abstract
Quantum applications are hybrid by nature, requiring tight integration between classical runtime systems and specialized quantum coprocessors. However, software engineering for these systems is bottlenecked by low-level, hardware-centric development patterns and gate-level circuit granularities. This tutorial introduces **Qonstruct**, an end-to-end research prototype designed to decouple quantum domain logic from hardware execution targets. 

Participants will explore how visual programming, model-driven engineering, and low-code abstractions can scale software design lifecycles without sacrificing system validation capabilities. The presentation covers high-level domain mapping, automated translation matrices into intermediate quantum representations, and cross-platform job orchestration via declarative middleware frameworks.

---

## Motivation
Quantum computers leverage structural mechanics like superposition and entanglement to yield computational advantages for specific algorithmic classes. Because they function as specialized accelerators rather than universal classical computer replacements, real-world deployment requires a hybrid software topology [3]. Unlocking this computational landscape has traditionally demanded exhaustive engineering knowledge of specialized assembly primitives, gate topologies, and individual provider backends. 

To lower this high entry barrier, a modern shift toward abstraction is taking place inside the quantum software stack [1, 2]. By providing visual domain blocks instead of individual gate arrays, a low-code architecture maps complex architectural constructs—such as state-preparation routines, localized oracles, and algorithmic diffusers—into cohesive software artifacts. This tutorial bridges the abstraction gap by mapping multi-domain low-code specifications directly to automatic orchestration layers that compile, validate, and deploy native code seamlessly across cloud nodes.

---

## Intended Audience
Attendees of this tutorial do not require a deep prerequisite background in quantum physics, advanced quantum mechanics, or low-level circuit hardware configurations. This session provides a practical roadmap for software engineers, systems designers, and cloud architects looking to acquire fundamental literacy in modeling, building, compiling, and deploying hybrid quantum application workflows.

---

## Technical Requirements
The practical hands-on tracking portion of this tutorial requires a laptop with the following baseline prerequisites installed:
* **Docker Engine** & **Docker-Compose**
* An active internet connection to clone workspace images.
* A standard modern web browser (Edge, Firefox, or Safari).

---

## Learning Goals
By completing this hands-on session, attendees will gain foundational knowledge on:
1. Core fundamentals governing practical quantum software engineering and systemic layer abstraction.
2. Building abstract quantum domain models visually using standard high-level component blocks.
3. Automatically compiling visual artifacts into valid, standard-compliant OpenQASM intermediate representations.
4. Orchestrating, deploying, and tracking compiled quantum job packages via decentralized cloud middleware infrastructure.

---

## References

[1] Stiliadou, L., Barzen, J., Bühler, F., Georg, D., Stiliadou, S.-N.: Low-Code Quantum Algorithm Modeling and Execution for Hybrid Cloud Environments. In: Proceedings of the 16th International Conference on Cloud Computing and Services Science. SciTePress (2026).

[2] Stiliadou, L., Barzen, J., Bühler, F., Georg, D.: A Multi-Domain Quantum Low-Code Platform. In: Proceedings of the 1st International Conference on Quantum Information, Computing, Communication, and Simulation. Springer (2026).

[3] Weder, B., Barzen, J., Beisel, M., Bühler, F., Georg, D., Leymann, F., Stiliadou, L.: Qunicorn: A Middleware for the Unified Execution Across Heterogeneous Quantum Cloud Offerings. In: Proceedings of the 2025 IEEE/ACM International Workshop on Quantum Software Engineering (Q-SE), pp. 17-24. IEEE (2025).