---
name: 'Decompositional Branching Bisimulation Minimisation of Monolithic Processes'
speakers:
  - Mark Bouwman
  - Maurice Laveaux
  - Bas Luttik
  - Tim Willemse
categories:
  - Logics & Semantics
links:
  - name: https://link.springer.com/chapter/10.1007/978-3-031-20872-0_10
    absolute_url: https://link.springer.com/chapter/10.1007/978-3-031-20872-0_10
    icon: newspaper
---

**Presenter**: Mark Bouwman  
**Session Chair**: Clemens Dubslaff

One of the biggest challenges in model checking complex systems is the state space explosion problem. A well known technique to reduce the impact of this problem is compositional minimisation. In this technique, first the state spaces of all components are computed and minimised modulo some behavioural equivalence (e.g., some form of bisimilarity). These minimised transition systems are subsequently combined to obtain the final state space.

In earlier work a compositional minimisation technique was presented tailored to mCRL2: it provides support for the multi-action semantics of mCRL2 and allows splitting up a monolithic linear process specification into components. Only strong bisimulation minimisation of components can be used, limiting the effectiveness of the approach. In this paper we propose an extension to support branching bisimulation reduction and prove its correctness. We present a number of benchmarks using mCRL2 models derived from industrial SysML models, showing that a significant reduction can be achieved, also compared to compositional minimisation with strong bisimulation reduction.
