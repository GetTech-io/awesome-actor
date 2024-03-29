# Awesome Actor Model [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This is an awesome list of actor model resources.

Inspired by [awesome](https://github.com/sindresorhus/awesome), [awesome-dotnet](https://github.com/quozd/awesome-dotnet), [awesome-dotnet-core](https://github.com/thangchung/awesome-dotnet-core).

Contributions are always welcome!

Thanks to all [contributors](https://github.com/GetTech-io/awesome-actor/graphs/contributors), you're awesome and wouldn't be possible without you!

Say hi on twitter to [HerbaPeter](https://twitter.com/HerbaPeter) or [GetTechio](https://twitter.com/GetTechio)!

## Contents

- [Awesome Actor Model](#awesome-actor-model)
  - [Contents](#contents)
  - [General](#general)
  - [Awesome lists](#awesome-lists)
  - [Frameworks, Libraries and Tools](#frameworks-libraries-and-tools)
    - [Application Frameworks](#application-frameworks)
    - [Application Templates](#application-templates)
  - [Sample Projects](#sample-projects)
  - [Articles](#articles)
  - [Books](#books)
  - [Videos](#videos)
  - [Podcasts](#podcasts)
  - [Research](#research)
  - [Community](#community)
  - [License](#license)

## General

[Wiki: Actor model](https://en.wikipedia.org/wiki/Actor_model)

## Awesome lists

[Awesome Akka](https://github.com/homerquan/awesome-akka)

## Frameworks, Libraries and Tools

### Application Frameworks

- [Actix](https://github.com/actix/actix) - Actor framework for Rust
- [Akka](https://github.com/akka/akka) - Build highly concurrent, distributed, and resilient message-driven applications on the JVM [akka.io](https://akka.io)  
- [Akka.Net](https://github.com/akkadotnet/akka.net) - Akka.NET is a professional-grade port of the popular Java/Scala framework Akka distributed actor framework to .NET. [getakka.net](https://getakka.net/)  
- [CAF: C++ Actor Framework](https://github.com/actor-framework/actor-framework) - CAF is an open source C++11 actor model implementation featuring lightweight & fast actor implementations, pattern matching for messages, network transparent messaging, and more.  
- [Comedy](https://github.com/untu/comedy) - Node.js actor framework.
- [Microsoft Orleans](https://github.com/dotnet/orleans) - Orleans is a cross-platform framework for building robust, scalable distributed applications  
- [Microsoft Service Fabric Reliable Actors](https://github.com/microsoft/service-fabric-services-and-actors-dotnet) - Reliable Actors is a Service Fabric application framework based on the Virtual Actor pattern. The Reliable Actors API provides a single-threaded programming model built on the scalability and reliability guarantees provided by Service Fabric. [Docs](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-reliable-actors-introduction), [Service Fabric](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-reliable-actors-introduction)  
- [Microsoft Dapr Actors](https://github.com/dapr/docs/blob/master/concepts/actor/actor_overview.md) - Dapr runtime provides an actor implementation which is based on Virtual Actor pattern. The Dapr actors API provides a single-threaded programming model leveraging the scalability and reliability guarantees provided by underlying platform on which Dapr is running. [Dapr](https://github.com/dapr/dapr)  
- [Orbit](https://github.com/orbit/orbit) - Distributed systems framework for the JVM by @electronicarts. [www.orbit.cloud](http://www.orbit.cloud)  
- [Orleankka](https://github.com/OrleansContrib/Orleankka) - Orleankka is a functional extension for Microsoft Orleans framework. It provides a message-based API similar to Akka/ProtoActor, carefully layered on top of the Orleans (that's what in a name). Orleankka is an excellent choice for use-cases which can benefit from composable, uniform communication interface, such as CQRS, event-sourcing, FSM, etc.    
- [ProtoActor](https://github.com/AsynkronIT) - Ultra fast distributed actors for Go, C# and Java/Kotlin [proto.actor](http://proto.actor)  
- [Pykka](https://github.com/jodal/pykka) - Pykka is a Python implementation of the actor model, which makes it easier to build concurrent applications [www.pykka.org](https://www.pykka.org)  
- [Quasar](https://github.com/puniverse/quasar) - Fibers, Channels and Actors for the JVM. [docs](http://docs.paralleluniverse.co/quasar/)  
- [Riker](https://github.com/riker-rs/riker/) - Easily build efficient, highly concurrent and resilient applications. An Actor Framework for Rust. [riker.rs](https://riker.rs)  
- [Rotor](https://github.com/basiliscos/cpp-rotor) - Event loop friendly C++ actor micro-framework  
- [SObjectizer](https://github.com/Stiffstream/sobjectizer) - SObjectizer is one of a few cross-platform and OpenSource "actor frameworks" for C++. But SObjectizer supports not only Actor Model, but also Publish-Subscribe Model and CSP-like channels. The goal of SObjectizer is significant simplification of development of concurrent and multithreaded applications in C++.  
- [Tarant](https://github.com/tarantx) - Fullstack composable actor system for Typescript/Javascript implementing an extensible framework that allows to focus in domain logic and delegate the rest to the platform.

### Application Templates

## Sample Projects

## Articles

- [Introducing Orleans 3.0](https://devblogs.microsoft.com/dotnet/orleans-3-0/)
- [Introductory hands on series for Tarant](https://dev.to/kanekotic/series/22701)

## Books

## Videos

- [Distributed Transactions are dead - Sergey Bykov](https://www.youtube.com/watch?v=epOLEdaPSLQ)  
- [Distributed Transactions are dead, long live distributed transaction! - Sergey Bykov](https://www.youtube.com/watch?v=8A5bRdyZXJw)  
- [Building distributed applications with Orleans - Sergey Bykov](https://www.youtube.com/watch?v=rlfnmyTEujA)  
- [How to build real-world applications with Orleans - John Azariah and Sergey Bykov](https://www.youtube.com/watch?v=7OVU9Mqqzgs)  
- [Orleans Architecture Patterns - Sergey Bykov and John Azariah](https://www.youtube.com/watch?v=dxwkYp4Fg3g)  
- [Building personalization with Orleans and Actor Modelling - Harald Schult Ulriksen](https://www.youtube.com/watch?v=3NT7uMV8GhQ)
- [Reactive Distributed Microservices on .NET - Reuben Bond](https://www.youtube.com/watch?v=Cj_jUHCXE3U)  
- [Actor Model Explained](https://www.youtube.com/watch?v=ELwEdb_pD0k)  
- [An Introduction To The Actor Model And Akka .NET - Sean Killeen](https://www.youtube.com/watch?v=4Afz-cdL7HU)  

## Podcasts

## Research

- [Microsoft Research - Orleans Virtual Actors](https://www.microsoft.com/en-us/research/project/orleans-virtual-actors/) - Project “Orleans” invented the Virtual Actor abstraction, which provides a straightforward approach to building distributed interactive applications, without the need to learn complex programming patterns for handling concurrency, fault tolerance, and resource management.    

## Community

- [Orleans Contrib](https://github.com/OrleansContrib/) - Orleans Community Contributions  

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)  
