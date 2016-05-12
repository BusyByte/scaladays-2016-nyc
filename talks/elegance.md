John Pretty @propensive

#8 guidelines for library

1.  keep public apis minimal
  - learn
  - compose
  - avoid polluting public api
  - expect wildcard imports
  - favor fewer general methods to more specific ones (use generics)
  - use private/protected
  - use typeclasses instead of overloading
  - hide / nest types
  - classes inside of object

1.  naming
 - familiar concept
 - short names
 - if in doubt use long
 - implicits have names and last ones shadow

1.  type safety
 - avoid primitives
 - avoid pure structural types like option, either, tuples
 - low bar for introducing new types
 - ensure can't represent illegal states
 - value classes
 - macros
   - Rapture example
     - macro prefix to string of css to check content is css

1. user experience
 - have every line matter
 - limit boilerplate
 - optimize for use-site 
 - sample code first

1. accomodate learning
 - library user shouldn't need to be library authors
 - implicits, macros, type theory shouldn't be barrier to use
 - recipies
 - copy paste fine
 
1. modular
 - separate and recomb easily
 - typeclasses
 - chain implicits

1. scope and org code - skipped
1. ..skipped

@implicitNotFound messages help

fix type errors

1. work out what types you want to handle
1. write low-priorty/defaul impl conf from gen source to gen exp type
1. impliment implicit with a macro
1. desconstruct param and return types passed to macro
1. print nice message
1. make the macro fail every time (just give clearer messages than compiler)

