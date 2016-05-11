akka cluster
asobu
kanaloa
 - little law
 - optimal concurrency
 - circuit breaker
centralized swagger doc -> yml as comments in routes file
play-swagger plugin
monitor from muuki88
 events monitor
 job monitor/commander
sbt utils

cats
shapeless
kittens

keislc
validateUser andThen getUserName
- function composition
- monadic composition
   def getUser: K[Id, User] = 
     for {
       name <- getUserName
       age <- getUserAge
     } yield User(...)
   need sbt compiler plugin
- generic composition
   gen(getUserName, getUserAge)
redundancy of api also
4k per second per service and have about 20 of them
