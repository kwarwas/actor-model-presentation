## Remotely Deploying Actors

Deploying an actor means:
- creating an actor instance with specific, explicitly configured properties and
- getting an IActorRef to that actor.

With Akka.Remote we get a new exciting detail:

**the network location to which an actor is deployed becomes a configuration detail**.
