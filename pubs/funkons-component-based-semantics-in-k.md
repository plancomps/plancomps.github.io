---
title: FunKons – Component-Based Semantics in K
---

# FunKons: Component-Based Semantics in K

by Peter D. Mosses and Ferdinand Vesely

## Abstract

> Modularity has been recognised as a problematic issue of programming language semantics, and various semantic frameworks have been designed with it in mind. Reusability is another desirable feature which, although not the same as modularity, can be enabled by it. The K Framework, based on Rewriting Logic, has good modularity support, but reuse of specifications is not as well developed. 
>
> The PLanCompS project is developing a framework providing an open-ended collection of reusable components for semantic specification. Each component specifies a single fundamental programming construct, or `funcon’. The semantics of concrete programming language constructs is given by translating them to combinations of funcons. In this paper, we show how this component-based approach can be seamlessly integrated with the K Framework. We give a component-based definition of CinK (a small subset of C++), using K to define its translation to funcons as well as the (dynamic) semantics of the funcons themselves.

Presented at [WRLA 2014](https://elp.webs.upv.es/workshops/wrla2014/).
Authors’ version of the paper is available [here](/files/2014/03/WRLA2014.pdf).

## Accompanying material

The complete specification of CinF, a case study used in the paper, along with a detailed description, can no longer be browsed online. The complete executable semantics of CinF and the relevant funcons in K can be downloaded as a Zip archive [here](/files/2014/03/cinf.zip).
