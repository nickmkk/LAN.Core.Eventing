LAN.Core.Eventing
=================

The ethos of this project is to create a productivity platform for C# developers, looking to build web applications with a native feel.
To this end, we provide strong typing from Server to Client using C# and TypeScript with t4 templates to generate the later from the former.
We have also tried to model our API to feel similar to MVC in C# and to simple delegates tied to events in JavaScript.

License
---
[The MIT License (MIT)](https://github.com/G3N7/LAN.Core.Eventing/blob/master/LICENSE)

Docs
---
* [Setup Dependencies (Composition Root)](https://github.com/G3N7/LAN.Core.Eventing/wiki/Setup-Dependencies-(Composition-Root))
* [Getting notified when an exception occurs in the hub or in a handler](https://github.com/G3N7/LAN.Core.Eventing/wiki/SignalREventHub.ExceptionOccurred)

Core Types
---
* [Event Names](https://github.com/G3N7/LAN.Core.Eventing/wiki/EventName) - [EventName](https://github.com/G3N7/LAN.Core.Eventing/blob/master/LAN.Core.Eventing/EventName.cs)
* [Event Types](https://github.com/G3N7/LAN.Core.Eventing/wiki/Event-Types) - [RequestBase](https://github.com/G3N7/LAN.Core.Eventing/blob/master/LAN.Core.Eventing/RequestBase.cs) / [ResponseBase](https://github.com/G3N7/LAN.Core.Eventing/blob/master/LAN.Core.Eventing/ResponseBase.cs) / [PushBase](https://github.com/G3N7/LAN.Core.Eventing/blob/master/LAN.Core.Eventing/PushBase.cs)
* [Handlers](https://github.com/G3N7/LAN.Core.Eventing/wiki/Event-Handlers) - [HandlerBase](https://github.com/G3N7/LAN.Core.Eventing/blob/master/LAN.Core.Eventing/HandlerBase.cs) / [IHandler](https://github.com/G3N7/LAN.Core.Eventing/blob/master/LAN.Core.Eventing/IHandler.cs)
* [Responding to Clients](https://github.com/G3N7/LAN.Core.Eventing/wiki/Responding-to-Clients) - [IMessageContext](https://github.com/G3N7/LAN.Core.Eventing/blob/master/LAN.Core.Eventing/IMessagingContext.cs)

Core Services
---
todo