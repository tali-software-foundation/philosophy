# Tali Design Philosophy

In its present state, the Tali programming language is a personal
experiment that aims to probe the intersection between:

- Minimalism
- Domain-specific languages (DSLs)
- Distributed computing

## Minimalism

There is something inherently appealing about the idea of a
programmable programming language - such that after encountering
it, it is hard to see the appeal of a general purpose programming
language that lacks such capability.

As a language, Tali is designed to offer a modern programmable
language core upon which additional features can be added or
subtracted as desired.

Yet, Tali is not line-noise. It is intended to be highly
readable to any programmer who can master the few fundamentals
of the language.

## DSLs

Tali is more or less a Lisp - a major motivation for this design
being that Lisps lend themselves to implementing DSLs, and Tali
is intended to explore that design space. Meta-languages and
compilers - code that generates other code - combine automation
with recursion to deliver incredible leverage.

## Distributed Computing

If programmable programming languages and code-generating code
could be said to be missing something, a global delivery
network for securely distributing itself might be it.

To remedy this, Tali is designed to interface well with the IPFS
ecosystem - particularly in the parsing and representation of
hash tables fundamental to modern data interchange, including
IPLD.

## Why a new Lisp?

Well, first off, Tali's more of a HASP (HASh Processing) than a
LISP. Second of all, Tali is a modern Lisp that is not
JVM-dependent. Third of all, and above all else, Tali is a
personal foray into language design and implementation and
constructing a new language and infrastructure, and that
principle object is only really realized by constructing a new
language.
