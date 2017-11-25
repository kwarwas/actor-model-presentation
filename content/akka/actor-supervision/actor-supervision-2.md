## Akka.NET - Supervision

### Fault Tolerance

> WIKI: **Fault tolerance** is the property that **enables a system to continue operating properly in the event of the failure of (or one or more faults within) some of its components**.

Each actor is the supervisor of its children, and as such each actor defines fault handling supervisor strategy. This strategy cannot be changed afterwards as it is an integral part of the actor system’s structure.

https://pasoft-share.gitbooks.io/akka-net-docs/content/Fault%20tolerance.html
