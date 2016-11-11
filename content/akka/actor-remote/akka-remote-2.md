## Akka.NET - Remote

- **Location transparency** - write code that looks like it's communicating with local actors, but with just a few configuration settings your actors can begin communicating with actors hosted in remote processes in a way that's fully location transparent to your code.
- **Remote deployment** - remotely deploy actors via the ActorOf method onto remote ActorSystem instances, anywhere on the network! The location of your actors on the network becomes a deployment detail in Akka.Remote.
- **Remote messaging** - send messages, transparently, to actors running in remote ActorSystems elsewhere on the network.
- **Remote addressing** - Akka.Remote extends the Address and ActorPath components of Akka.NET to also now include information about how to connect to remote processes via ActorSelection.
