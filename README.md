# LOGIA: *An Automated Theorem Prover*
---

Logia is my attempt to create an automated theorem prover by combining the widely separate (but not really that distinct :) fields of proof theory, evolutionary algorithms and computer programming. In its current form, it uses genetic programming to create mathematical proofs which are then verified by Coq, a proof assistant for a variant of intuitionistic type theory. I plan to integrate a SAT solver, better genetic algoritms (with natural selection in mind) and machine learning.


## Getting Started

Get Python and the numpy library. I use [Anaconda](https://www.continuum.io/downloads) by Continuum Mechanics.

Next, download [Coq](https://coq.inria.fr/download), a proof assistant for the Calculus of (Inductive) Constructions designed by Thiery Coquand, which is an extension of the [Curry-Howard isomorphism](https://en.wikipedia.org/wiki/Curry–Howard_correspondence).

Clone the repository and add the pathnames in *version_logia.py* accordingly, and you're all set!
