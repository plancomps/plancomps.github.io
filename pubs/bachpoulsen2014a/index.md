---
title: Deriving Pretty-Big-Step Semantics from Small-Step Semantics
nav_exclude: true
---

# Deriving Pretty-Big-Step Semantics from Small-Step Semantics

By Casper Bach Poulsen and Peter D. Mosses

## Abstract

> Big-step semantics for languages with abrupt termination and/or divergence suffer from a serious duplication problem, addressed by the novel ‘pretty-big-step’ style presented by Charguéraud at ESOP’13. Such rules are less concise than the corresponding small-step rules, but they have the same advantages as big-step rules for program correctness proofs.
>
> Here, we show how to automatically derive pretty-big-step rules directly from small-step rules by ‘refocusing’. This gives the best of both worlds: we only need to write the relatively concise small-step specifications, but our reasoning can be big-step as well as small-step. The use of strictness annotations to derive small-step patience rules gives further conciseness.

Presented at [ESOP’14](https://flint.cs.yale.edu/esop2014/).

## Accompanying material

- **[Authors’ version of the paper](/files/2014/01/esop14.pdf)**
- **[Slides from ESOP’14 presentation](/files/2014/01/esop14-presentation.pdf)**
- **[Generated interpreters and test suite](/files/2014/01/esop14_interpreters.zip)**: The correctness of our derivation has been tested by deriving from a small-step semantics its corresponding refocused semantics and pretty-big-step semantics. Using the MSOS Derivation Tool, we have generated prototype interpreters from each of the semantics and verified that the same program executed on each of the interpreters produces the same output. The generated interpreters and accompanying test suite are executable using [SWI-Prolog](https://www.swi-prolog.org/) ≥ 6.2.5.
- **[Coq theories and proofs](/pubs/bachpoulsen2014a/coq/)**: We have formalised our semantics in Coq and proven that the derived pretty-big-step rules in the paper correspond to the small-step rules from which they were automatically derived. The Coq theories and proofs are executable using [Coq](https://coq.inria.fr/) ≥ 8.4pl2
