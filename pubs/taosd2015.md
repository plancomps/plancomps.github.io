---
title: Reusable Components of Semantic Specifications (Extended Version)
---

# Reusable Components of Semantic Specifications (Extended Version)

By Martin Churchill, Peter D. Mosses, Neil Sculthorpe, and Paolo Torrini

## Abstract

> Semantic specifications of programming languages typically have poor modularity. This hinders reuse of parts of the semantics of one language when specifying a different language – even when the two languages have many constructs in common – and evolution of a language may require major reformulation of its semantics. Such drawbacks have discouraged language developers from using formal semantics to document their designs.
>
> In the PLanCompS project, we have developed a component-based approach to semantics. Here, we explain its modularity aspects, and present an illustrative case study: a component-based semantics for [Caml Light](https://caml.inria.fr/caml-light/index.en.html). We have tested the correctness of the semantics by running programs on an interpreter generated from the semantics, comparing the output with that produced on the standard implementation of the language.
>
> Our approach provides good modularity, facilitates reuse, and should support co-evolution of languages and their formal semantics. It could be particularly useful in connection with domain-specific languages and language-driven software development.

In Transactions on Aspect-Oriented Software Development XII, pages 132 – 179, LNCS 8989, Springer, 2015.

## Accompanying material

- **[Authors’ version of the paper](/files/2015/03/reusable-semantic-components.pdf)**. The final publication is available at [Springer](https://dx.doi.org/10.1007/978-3-662-46734-3_4).

- A [ZIP archive ](/files/2015/02/PLCS-caml-light.zip) containing:

  - the full specification of Caml Light using funcons;
  - Caml Light test programs, together with funcon terms generated from them;
  - I-MSOS specifications for funcons and value operations, together with Prolog code generated from them; and
  - the tools for generating and running the funcon terms and Prolog code.
