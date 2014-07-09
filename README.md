locus
=====

Locus is an experimental (IN PROGRESS) declarative where the distinction between compile-time and run-time code is fluid and manageable.

Soem of the syntax is similar to Haskell. There are type classes, polymorphic types, and ADTs. Locus has a type, effect, 
coeffect, and locum system, where type signatures are of the form:

e : C => t => E @ P

where 'C' is a set of constraints (coeffects), 't' is a type, 'E' is a set of effects, 'L' is the locum (place where the code must be run).
All of these allow polymorphism (which is implcit when a lower-case name is used, in the style of Haskell).


