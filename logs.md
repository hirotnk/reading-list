# Microservice Collaboration
2021-02-16 Tue, Sam Newman webinar

## Implementing Microservices
- https://learning.oreilly.com/library/view/building-microservices-2nd/9781492034018/ch04.html#a50-dry
- https://learning.oreilly.com/library/view/building-microservices-2nd/9781492034018/ch07.html#deployment_chapter
- https://martinfowler.com/articles/oss-lockin.html
- https://learning.oreilly.com/library/view/building-microservices-2nd/9781492034018/ch05.html#workflow-chapter

- [Mature Microservices and How to operate them](https://www.infoq.com/presentations/microservices-financial-times/)
- [Enterprise Integration Patterns](https://learning.oreilly.com/library/view/enterprise-integration-patterns/0321200683/)

## Serverless
- [Serverless Fundamentals for Microservices: An Introduction to Core Concepts and Best Practices(video)](https://learning.oreilly.com/videos/serverless-fundamentals-for/9781492039006/)

## Protocols/Interfaces
- Synchronous / Asyncronous <-> Request,Response / Event-based

### gRPC
### Rest
- [Richardson Maturity Model](https://martinfowler.com/articles/richardsonMaturityModel.html)
- [Rest in Practice](https://learning.oreilly.com/library/view/rest-in-practice/9781449383312/)

### HTTP Status Dog
- https://httpstatusdogs.com/

### Interaction between services
- [Orchestrate vs Choreograph](https://solace.com/blog/microservices-choreography-vs-orchestration/)

## DB Transaction

## 2PC
### SAGAS
- [SAGAS paper](https://www.cs.cornell.edu/andru/cs711/2002fa/reading/sagas.pdf)
- https://microservices.io/patterns/data/saga.html


---
#  Microservices Application Decomposition
2021-02-10 Wed, Sam Newman webinar

### Module Boundary
- https://samnewman.io/books/building_microservices_2nd_edition/
    * D. Parnas paper:On the Criteria to Be Used in Decomposing Systems Into Modules” (Communications of the ACM, December 1972)
- https://stevemcconnell.com/articles/missing-in-action-information-hiding/
- DDD Distilled by Vaughn Vernon

- https://learning.oreilly.com/library/view/building-microservices-2nd/9781492034018/ch02.html#modelling-services-chapter
- https://learning.oreilly.com/library/view/building-microservices-2nd/9781492034018/ch09.html#conways-chapter



### API-Gateway vs BFF pattern, GraphQL, Aggregating Gateway
- https://samnewman.io/patterns/architectural/bff/
- https://martinfowler.com/articles/feature-toggles.html

- https://learning.oreilly.com/library/view/building-microservices-2nd/9781492034018/ch08.html#ui-chapter

### Regarding the danger of code sharing
- https://learning.oreilly.com/library/view/building-microservices-2nd/9781492034018/ch04.html#a50-dry

### Strategy for refactoring:
- Migration to microservices should always be incremental/gradual, not a big-bang.
- Scientist https://github.com/github/scientist
- Workikng Effectively with Legacy Code by Michael Feather
    * legacy code is the code  without test
- Some other patterns