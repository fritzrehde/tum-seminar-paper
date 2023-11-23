# Ownership types in theory and practice (in Rust)

This repo contains my work on the topic "Ownership types in theory and practice (in Rust)" for the "Next-Gen Programming Interfaces and Compilers" seminar course I took at the Technical University of Munich (TUM) in the winter semester 22/23.
In this course, we were required to write a 10-page scientific research paper (see [paper.pdf](pdfs/paper.pdf)), and subsequently hold a presentation on its topic, supported by slides (see [slides.pdf](pdfs/slides.pdf)).

This is the abstract of the paper:
```
Object aliasing is the concept of accessing the same
memory through different symbolic names in object-
oriented programming languages. Many programming
bugs are created through unintentional aliases, which
are hard to detect and can lead to unexpected side effects.
Ownership types are one solution that attempts to
prevent many alias-related bugs. The premise of own-
ership types is that not only the fields of an object
are protected from external access, but also all objects
stored in those fields. This is done by allowing objects
to take ownership of other objects.
This paper depicts some of the different kinds of
ownership types, explains how the modern program-
ming language Rust uses ownership types and evalu-
ates Rust's implementation by comparing its use of the
ownership concept to that of another popular systems
programming language, namely C++.
```
