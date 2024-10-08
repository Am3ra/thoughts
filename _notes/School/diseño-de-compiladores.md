---
---

Class taken in my [[8th semester]] of [[university]]

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Topic 1. Basic Concepts of the Compilation Process](#topic-1-basic-concepts-of-the-compilation-process)
    - [Class 1](#class-1)
        - [Classifications of Programming Languages](#classifications-of-programming-languages)
    - [Day 2 - Translation Process](#day-2---translation-process)
    - [Steps of Compilations](#steps-of-compilations)
- [Topic 2. The Analysis Phase](#topic-2-the-analysis-phase)
    - [Lexical Analysis](#lexical-analysis)
    - [Syntax Analysis](#syntax-analysis)
    - [Semantic Analysis](#semantic-analysis)
- [Topic 3. The Translation Process directed by Syntax](#topic-3-the-translation-process-directed-by-syntax)
    - [Directory of Functions and Tables of Variables](#directory-of-functions-and-tables-of-variables)
    - [Intermediate translation styles: Vector Polish, Triples, Quadruple](#intermediate-translation-styles-vector-polish-triples-quadruple)
- [Topic 4. Generation of Intermediate Code](#topic-4-generation-of-intermediate-code)
    - [Translation of Expressions](#translation-of-expressions)
    - [Translation of Linear Elements](#translation-of-linear-elements)
    - [Bylaws with non-linear flow](#bylaws-with-non-linear-flow)
    - [Context changes translation](#context-changes-translation)
    - [Translation of non-atomic elements](#translation-of-non-atomic-elements)
- [Topic 5. Execution and Design Environments for Virtual Machines](#topic-5-execution-and-design-environments-for-virtual-machines)
    - [Execution Memory Map](#execution-memory-map)
    - [Design of a Virtual Processor](#design-of-a-virtual-processor)
- [Topic 6. Advanced Topics (Translators for other programming paradigms)](#topic-6-advanced-topics-translators-for-other-programming-paradigms)

## Topic 1. Basic Concepts of the Compilation Process

### Class 1

What is a programming language?

> Special, defined notation to describe computer processes, in a manner understandable to both humans and computers.

#### Classifications of Programming Languages

- By Abstraction level:
    - Low level

            Direct memory access
    - Medium Level
    - High Level

            Memory Access through operators
    - Very High Level

            No memory access?
    - By historic evolution
    - Machine language
    - Associative language
    - Procedural language
    - Application language
    - Inference language
    - Neural Networks
- By expression of Solution
     Imperative/Procedural
    - Declarative
- By Paradigm
    - Imperative
    - OOP
    - Functional
    - Logical

### Day 2 - Translation Process

Term | Definition
---  | ---
Translation | The process of exchanging equivalents.

Translation takes an input in language A, and either produces an equivalent in language B, or an error.

- Features of a Compiler
    - Translates from source code to object code
    - Can throw errors

### Steps of Compilations

1. Lexical Analysis
    - Determine if elements (tokens) exist in source language
    - Clean source code
        - remove whitespace
        - remove comments
        - (normalize capitalization)
2. Syntactic Analysis
   - Determine if sequence of elements conforms to correct structure
   - Structure is given by the language's grammar
3. Semantic Analysis
   - Determine the congruence of the elements according to meaning established as valid by the language.
   - Basically it's the type-checking system
4. Intermediate Code Generation (Optional)
5. Code optimization (Optional)
   - Step that minimizes time or space requirements of the code.
6. Object code generation


## Topic 2. The Analysis Phase

### Lexical Analysis

### Syntax Analysis

### Semantic Analysis

## Topic 3. The Translation Process directed by Syntax

### Directory of Functions and Tables of Variables
    
### Intermediate translation styles: Vector Polish, Triples, Quadruple

## Topic 4. Generation of Intermediate Code

### Translation of Expressions

### Translation of Linear Elements

### Bylaws with non-linear flow

### Context changes translation

### Translation of non-atomic elements

## Topic 5. Execution and Design Environments for Virtual Machines

### Execution Memory Map

### Design of a Virtual Processor

## Topic 6. Advanced Topics (Translators for other programming paradigms)

[//begin]: # "Autogenerated link references for markdown compatibility"
[university]: ../university "university"
[//end]: # "Autogenerated link references"