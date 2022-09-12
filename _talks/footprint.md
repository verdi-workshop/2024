---
name: 'Footprint Logic for Object-Oriented Components'
speakers:
  - Frank de Boer
  - Hans Dieter Hiep
  - Jinting Bian
  - Stijn de Gouw
categories:
  - Logics & Semantics
---

We introduce a new way of reasoning about invariance in terms of footprints in a Hoare logic for object-oriented components. 
A footprint of an object-oriented component is formalized as a monadic predicate that describes which objects on the heap can be affected by the execution of the component. 
Invariance of an assertion is ensured by means of a form of bounded quantification which excludes references to a given footprint.
