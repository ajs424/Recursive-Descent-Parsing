# Recursive-Descent-Parsing

Considering thhis BNF grammar:

A -> I = E | E
E -> P O P | P
O -> + | - | * | / | **
P -> I | L | UI | UL | (E)
U -> + | - | !
I -> C | CI
C -> a | b | ... | y | z
L -> D | DL
D -> 0 | 1 | ... | 8 | 9

I implemented a recursive descent parser that recognizes the strings in this language. This repository includes both a Java and a C++ implementation.
