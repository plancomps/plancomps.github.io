---
title: Background
parent: PLanCompS 2011–2016
---

# Background

Software comes in many different shapes and sizes: ranging from games and social networking systems through databases and office software to control system for vehicles and medical instrumentation. Regardless of its purpose, software is almost always written in high-level programming languages, which are significantly easier to use than the low-level machine languages which can be executed directly by computers.

Before a program written in a high-level language can be run on a particular computer, the language needs to have been implemented on that computer. The implementation could be a compiler, which translates high-level programs to machine code; alternatively, it might directly interpret them, simulating their intended behaviour.

{: .text-delta }
PROGRAMMING LANGUAGE EVOLUTION

Many hundreds of programming languages have been designed and implemented since the 1950s, and dozens are currently in widespread use. Major ones introduced since 1995 include Java, C#, Python, Ruby, OCaml, Delphi, VBScript, PHP and JavaScript. Older languages evolve to incorporate new features: new versions of Fortran, Cobol, Ada, C++, Scheme and Haskell appear at intervals ranging from one to 10 years.

New programming languages are continually being designed and implemented, with the aim of making it easier (or at least quicker and cheaper) for programmers to write useful software. So-called domain-specific languages (DSLs) are designed for use in a particular sector, such as banking or engineering, or particular scientific disciplines; they are often obtained by extending general-purpose languages with features that correspond closely to standard concepts or notation in the targeted sector.

{: .text-delta }
LANGUAGE SPECIFICATIONS

The documentation of a language design is called a language specification. This usually consists of a succinct formal grammar, determining the syntax of the language (i.e., which sequences of characters are allowed as programs, and how they are to be grouped into meaningful phrases), together with a lengthy informal explanation of their semantics (i.e., the required behaviour when run), written in a natural language such as English. Unfortunately, such explanations are inherently imprecise, open to misinterpretation, and not amenable to validation.

## Component-based language specifications

This project will employ innovative techniques for specifying the semantics of languages completely formally. The main novelty will be the creation of a large collection of reusable components of language specifications. Each component corresponds to a fundamental programming construct, or funcon, with fixed semantics. Translation of program phrases to combinations of funcons determines the semantics of the programs, and is much simpler than specifying their formal semantics directly. The project will test and demonstrate the advantages of this component-based approach to language specification using case studies involving specification of major programming languages (including C# and Java) and DSLs.

{: .text-delta }
TOOL SUPPORT

Sophisticated tools and an integrated development environment will be implemented by the project to support creation and validation of component-based language specifications. The tools will support automatic generation of prototype implementations directly from specifications, allowing programs to be run according to their formal semantics. This will encourage language designers to experiment with different designs before initiating a costly manual implementation of a particular one, which may lead to development of better languages.

{: .text-delta }
DIGITAL LIBRARY

Funcon and language specifications will be stored in an open-access repository, and a digital library interface will support browsing and searching in the repository, which will contain many hundreds of funcons. The library will also provide access to digital copies of existing language specifications using previous approaches.
