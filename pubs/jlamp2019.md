---
title: Executable Component-Based Semantics
---

# Executable Component-Based Semantics

By [L. Thomas van Binsbergen](http://ltvanbinsbergen.nl/publications), [Peter D. Mosses](https://pdmosses.github.io/) and [Neil Sculthorpe](http://neilsculthorpe.com/)

## Abstract

> The potential benefits of formal semantics are well known. However, a substantial amount of work is required to produce a complete and accurate formal semantics for a major language; and when the language evolves, large-scale revision of the semantics may be needed to reflect the changes. The investment of effort needed to produce an initial definition, and subsequently to revise it, has discouraged language developers from using formal semantics. Consequently, many major programming languages (and most domain-specific languages) do not yet have formal semantic definitions.
>
> To improve the practicality of formal semantic definitions, the PLanCompS project has developed a component-based approach. In this approach, the semantics of a language is defined by translating its constructs (compositionally) to combinations of so-called fundamental constructs, or *funcons*. Each funcon is defined using a modular variant of Structural Operational Semantics, and forms a language-independent component that can be reused in definitions of different languages. A substantial library of funcons has been developed and tested in several case studies. Crucially, the definition of each funcon is fixed, and does not need changing when new funcons are added to the library.
>
> For specifying component-based semantics, we have designed and implemented a meta-language called CBS. It includes specification of abstract syntax, of its translation to funcons, and of the funcons themselves. Development of CBS specifications is supported by an integrated development environment. The accuracy of a language definition can be tested by executing the specified translation on programs written in the defined language, and then executing the resulting funcon terms using an interpreter generated from the CBS definitions of the funcons. This paper gives an introduction to CBS, illustrates its use, and presents the various tools involved in our implementation of CBS.

The full text of this article is available on the authors’ personal webpages.

## Publication info

DOI
: https://doi.org/10.1016/j.jlamp.2018.12.004

Journal
: Journal of Logical and Algebraic Methods in Programming (JLAMP)

Volume
: 103, February 2019, Pages 184-212

Publisher
: Elsevier

## The CBS meta-language

[CBS-beta](https://plancomps.github.io/CBS-beta/)
: beta release of the CBS meta-language (GitHub).

[Funcons-beta](https://plancomps.github.io/CBS-beta/Funcons-beta/)
: beta release of reusable funcons defined in CBS (GitHub).

## Accompanying Haskell tools

- [Tools for building and executing funcon terms, including an extensible interpreter](https://hackage.haskell.org/package/funcons-tools-0.2.0.5)
- [Built-in values and value operations](https://hackage.haskell.org/package/funcons-values-0.1.0.3)
- [Funcon term interpreter for the SIMPLE language](https://hackage.haskell.org/package/funcons-simple-0.1.0.3)
