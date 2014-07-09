locus
=====

Locus is an experimental (IN PROGRESS) declarative programming language where the distinction between compile-time and run-time code is fluid and manageable. Code can be explicitly declared to be at compile time, run time, or install time, or the availability of the code can be inferred, with a polymorphic 'locum' system. 

Somd of the syntax is similar to Haskell. There are type classes, polymorphic types, and ADTs. Locus has a type, effect, 
coeffect, and locum system, where type signatures are of the form:

        e : C => t => E @ P

where 'C' is a set of constraints (coeffects), 't' is a type, 'E' is a set of effects, 'L' is the locum (place where the code can be run). All of these allow polymorphism (which is implcit when a lower-case name is used, in the style of Haskell).


