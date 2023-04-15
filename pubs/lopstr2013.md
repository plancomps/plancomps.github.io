---
title: Generating Specialized Interpreters for Modular Structural Operational Semantics
---

# Generating Specialized Interpreters for Modular Structural Operational Semantics

By Casper Bach Poulsen and Peter D. Mosses

## Abstract

> Modular Structural Operational Semantics (MSOS) is a variant of Structural Operational Semantics (SOS). It allows language constructs to be specified independently, such that no reformulation of existing rules in an MSOS specification is required when a language is extended with new constructs and features.
>
> Introducing the Prolog MSOS Tool, we recall how to synthesize executable interpreters from small-step MSOS specifications by compiling MSOS rules into Prolog clauses. Implementing the transitive closure of compiled small-step rules gives an executable interpreter in Prolog. In the worst case, such interpreters traverse each intermediate program term in its full depth, resulting in a significant overhead in each step.
>
> We show how to transform small-step MSOS specifications into corresponding big-step specifications via a two-step specialization by internalizing the rules implementing the transitive closure in MSOS and ‘refocusing’ the small-step rules. Specialized specifications result in generated interpreters with significantly reduced interpretive overhead.

Presented at [LOPSTR 2013](https://www.utdallas.edu/~gupta/lopstr/).

## Accompanying material

- [Authors’ version of the paper](https://plancomps.csle.cs.rhul.ac.uk/files/2015/01/lopstr13.pdf)
- [Benchmarks and generated Prolog prototype interpreters](https://plancomps.csle.cs.rhul.ac.uk/files/2015/01/lopstr13_benchmarks.zip)
