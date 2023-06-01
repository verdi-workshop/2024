---
speakers:
  - Stylianos Basagiannis
  - Ludovico Battista
  - Anna Becchi
  - Alessandro Cimatti
  - Georgios Giantamidis
  - Sergio Mover
  - Alberto Tacchella
  - Stefano Tonetta
  - Vassilios Tsachouridis 
name: 'SMT-Based Stability Verification of an Industrial Switched PI Control Systems'
categories:
  - Session 3
---


The control of complex systems is typically designed describing the physical system with differential equations. The standard approach to their verification employs numerical analysis, which is suitable to prove stability properties, but is susceptible to numerical errors. On the other side, symbolic techniques give precise analysis results but typically do not scale to industrial size problems.

In this paper, we consider the control design of an aircraft engine. The engine model is represented by a linear state space model of 18 internal state variables, 4 outputs, and 3 inputs. The control switches between two PI controllers, one for thrust control and another for low-pressure compressor spool speed control, based on the engine state and pilot commands. After reformulating the PI controllers in terms of differential equations, we obtain a hybrid system with 21 state variables and two modes, for which we want to prove with symbolic techniques the robustness of the stable states to perturbation.

We achieved the verification with standard methods to synthesize quadratic Lyapunov functions and SMT techniques to synthesize neighborhoods of the stable states for which we have symbolic proof of stability.
