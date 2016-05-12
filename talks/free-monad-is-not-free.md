@kellyrobinson

[github repo](https://github.com/robinske)

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

```scala
case class Return
case class Suspend
case class FlatMap extends Free
```

- defer side effects
- muliple interpreters
- stack safety

every function call is in stack

trampoline expresses it in a loop

FunctorTransformer or NaturalTransformer
  - inline or recursive

apply transformation on suspend

multiple interpreter allow testing without mocks

`#BlueSkyScala on twitter`

The path to learning is broken

- boilerplate
- learning curve
- alternatives

ScalaZ or Cats have build in

Doobie or ScalaZ Task

[Slides](http://www.slideshare.net/KelleyRobinson1/why-the-free-monad-isnt-free-61836547)

[Code](https://github.com/robinske/monad-examples)
