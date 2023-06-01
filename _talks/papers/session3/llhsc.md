---
speakers:
  - Vitor Rodrigues
  - André Matos Pedro 
name: 'llhsc: A Devicetree Syntax and Semantic Checker'
categories:
  - Session 3
---


Feature models are a common technique for modeling software variability and representing the possible configurations of a system. This paper presents the llhsc tool, a tool that enables the generation of valid  Devicetree specifications for custom hardware based on the constraints specified in a feature model. 

The form of these constraints is a set of logical formulas, which enables product line model validation by means of off-the-shelf satisfiability solvers. In this context, a new set of constraints is defined that specifies both syntax and semantic correctness of a delta-oriented software product line for Devicetree bindings.

This approach provides a more general and flexible solution for static-partitioning hypervisors configuration, but can also be used in systems without virtualization support, enabling the tool to be used in various contexts without sacrificing its generality.

The authors showcase the effectiveness of their approach by means of an empirical running example, which provides evidence supporting the construction of customized configurations for systems that run static-partitioning hypervisors.

