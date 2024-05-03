---
name: 'Virtual Evaluation of Dependability Attributes for Mission-Critical Cyber-Physical Systems'
speakers:
  - Adam Bachorek
  - Benedikt Lüken-Winkels
  - Iron Prando Da Silva
  - Stefan Schwenk
  - Markus Damm
  - Pablo Oliveira Antonino
room: 'DSN2024'
categories:
  - Short papers
---


Assuring dependability of complex mission-critical cyber-physical systems in various domains including automotive and agriculture is becoming an increasingly demanding challenge. This is due to the ongoing evolution of land vehicles and machinery such as tractors and implements from mainly electro-mechanical devices towards software-driven and interconnected processing units enabling highly automated applications like smart farming. In particular, the underlying communication infrastructure of the involved distributed subsystems is subject to high demands in view of functional but also quality aspects like security and safety. And, testing the countless component interactions against associated criteria is not feasible without sophisticated techniques and tooling support, which continuous engineering solutions tackle with experimental evidence based on virtual evaluation environments. While these facilitate advanced practices for handling system complexity, formal verification of specific system properties remains a complementary and effective part of modern product development.
In this paper, we present a generic methodical concept which combines virtual experimentation with formal analysis to substantiate decisions regarding the design and implementation of reliable CPS. We validate our approach by means of a case study on a common evaluation problem with regard to weighing up competing quality attributes in the context of resource-constraint communication. To this end, we instantiate a virtual testbed based on the established VCIP reference architecture and FERAL simulation framework and we conduct empirical trials using systematic fault-injection combined with analytical proofing in terms of a trade-off evaluation. Specifically, we generate different CAN data frame variants during back-to-back tests for assessing the impact of cyclic redundancy checks and message authentication codes on the level of functional safety and security, respectively. The results show the viability of our approach in conjunction with the capabilities of the evaluation platform for the continuous verification and validation of dependability-related aspects of a CPS under development.

