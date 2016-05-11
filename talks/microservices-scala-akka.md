@VaughnVernon
implementing domain driven design
reactive mess patt with the actor model
domain driven design distilled (out soon)
Fred George 
 - vimeo page of code
 - doesn't care if unused/unknown running

building microservices book
ubiquitous language
 - gt entity names
 - commands / events

microservice owns database / event journal
query model

actors are async services
don't send request to another microservice
rapids, rivers, ponds
 - Fred George

REST (ATOM)
kafka
rabbitmq

topics -> event -> command to another microservice
12-20ms rest req/resp
supervision and client retry
akka-cluster

Process Manager

class Product(id) extends PersistentActor
  publishes to the river
