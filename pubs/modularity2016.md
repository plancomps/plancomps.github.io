---
title: Tool Support for Component-Based Semantics
---

# Tool Support for Component-Based Semantics

By L. Thomas van Binsbergen, Peter D. Mosses and Neil Sculthorpe

## Abstract

> The developers of a programming language need to document its intended syntax and semantics, and to update the documentation when the language evolves. They use formal grammars to define context-free syntax, but usually give only an informal description of semantics. Use of formal semantics could greatly increase the consistency and completeness of language documentation, support rapid prototyping, and allow empirical validation.
>
> Modularity of semantics is essential for practicality when scaling up to definitions of larger languages. Component-based semantics takes modularity to the highest possible level. In this approach, the semantics of a language is defined by equations translating its constructs (compositionally) to combinations of so-called fundamental constructs, or ‘funcons’. The definition of each funcon is a small, highly reusable component. The PlanCompS project has defined a substantial library of funcons, and shown their reusability in several case studies.
>
> We have designed a meta-language called CBS for component-based semantics, and an IDE to support development, rapid prototyping, and validation of definitions in CBS. After introducing and motivating CBS, we demonstrate how the IDE can be used to browse and edit the CBS definition of a toy language, to generate a prototype implementation of the language, and to parse and run programs.

## Accompanying material

The archive below accompanies the paper:

- Tool Support for Component-Based Semantics.\\
  L. Thomas van Binsbergen, Neil Sculthorpe, Peter D. Mosses.\\
  In MODULARITY Companion’16, ACM, 2016.\\
  http://dx.doi.org/10.1145/2892664.2893464

[CBS-IMP.tar.gz](https://plancomps.csle.cs.rhul.ac.uk/files/2016/03/CBS-IMP.tar.gz) (updated 11/03/2016)

The archive includes:

- A CBS library of funcon definitions;
- A Spoofax editor for CBS files;
- A Haskell-based compiler from CBS funcon definitions to Haskell-embedded funcons;
- A CBS definition of the IMP language;
- A Spoofax editor for IMP programs;
- A collection of IMP test programs, and the corresponding funcon terms.

A Haskell-based interpreter for funcon terms is available on [Hackage](https://hackage.haskell.org/package/funcons-tools).
