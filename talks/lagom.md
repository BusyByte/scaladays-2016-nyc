Micro Dotta
@mircodotta

Lagom - just right

uniform reactive services - just different domain

akka + play
event sourcing + CQRS

hot reloading

interservice communication built in

Cassandra default datastore

Jackson

Google Guice

Architectural Concepts: immutability, Event Sourcing/CQRS, circuit breakers

api and impl project

Source of String for streaming

http right now, adding more later

interservice use @Inject

only service has direct access to DB

event handler must be side-effect free so don't 'send emails' on replay of events

lightbend ConductR* 

possibly use Kubernetes

lightbend reactive plat
 - split brain resolver
 - lightbend monitoring

scala api in progress

swagger in future so no binary coupling

[Greg Young on why you should use Event Sourcing](https://www.youtube.com/watch?v=JHGkaShoyNs)

[Slides](http://www.slideshare.net/mircodotta/lightbend-lagom-microservices-just-right)
