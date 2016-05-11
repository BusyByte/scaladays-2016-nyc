@kellyrobinson
gh - robinske
monad - computation builder
 - pure
 - flatMap

makes side effects explicit

free as in not restricted - freedom

Free monoids
 - append & identity

don't loose data
addition looses inputs once computed
list maintains data

trait Free

case class Return
case class Suspend
case class FlatMap extends Free

- defer side effects
- muliple interpreters
- stack safety

every function call is in stack

trampoline expresses it in a loop

FunctorTransformer or NaturalTransformer
  - inline or recursive

apply transformation on suspend

multiple interpreter allow testing without mocks

#BlueSkyScala
The path to learning is broken

- boilerplate
- learning curve
- alternatives

ScalaZ or Cats have build in
Doobie or ScalaZ Task

