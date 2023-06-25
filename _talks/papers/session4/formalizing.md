---
speakers:
  - Carlos Mão de Ferro
  - Tiago Cogumbreiro
  - Francisco Martins 
name: 'Formalizing Model Inference of MicroPython'
categories:
  - 'Session 4 (chair: Stefano Tonetta)'
---


Model checking has often been used for verifying
Cyber-Physical Systems (CPS). A major challenge is how to
capture a model that represents the actually behavior of the software.
Model extraction can introduce errors that can affect the
accuracy of the analysis including loss of precision, inconsistency,
non-conformance, and over- and under-approximations.
In this paper, we formalize and prove the correctness of
extracting a model from a subset of the MicroPython programming
language with respect to a trace-based semantics. The extracted
models capture the order of method calls and can be model
checked using Shelley. We formalize the extraction process from
an intermediate representation of MicroPython codes and prove
that the behavior of our intermediate representation is a regular
language. Our formalization and theoretical results are fully
mechanized using the Coq proof assistant
