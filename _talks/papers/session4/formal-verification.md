---
speakers:
  - Radouane Bouchekir
  - Michell Guzman Cancimance
  - Cook Alasdair
  - Johannes Haindl
  - Riqaq Woolnough
name: 'Formal Verification for Safe AI-based Flight Planning for UAVs'
categories:
  - 'Session 4 (chair: Stefano Tonetta)'
---


Planning and decision-making, especially the planning of collision-free paths, are an integral part of the operation of Unmanned Aerial Vehicles (UAVs). Formalisms like Temporal Plan Networks (TPN) can be used to provide optimal flight plans for UAVs. However, ensuring that the generated flight plans are safe can be a complex task, depending on the method used to generate the plans. Safe in this context means that
the next planned action for the UAV does not violate safety constraints, for example, no-fly zones (NFZ). In this paper, we investigate the application of formal methods to generate metrics that could be used as assurance evidence in the argumentation of the safety of the planning component. In particular, we make use of Satisfiability Modulo Theories (SMT)-based verification to verify low-level requirements, together with Program Verification System (PVS) to check the design requirements of the AI-based planning component.
