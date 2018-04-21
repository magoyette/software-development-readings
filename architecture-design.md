# Software Architecture & Design

## Anti-Patterns & Code Smells

- James Shore, [Primitive Obsession](http://www.jamesshore.com/Blog/PrimitiveObsession.html).
- Martin Fowler, [AnemicDomainModel](http://www.martinfowler.com/bliki/AnemicDomainModel.html).
- Nat Pryce, [Message Obsession](http://www.natpryce.com/articles/000816.html).

## API Design

- Danilo Sato, [ParallelChange](http://martinfowler.com/bliki/ParallelChange.html).
- Jason Gorman, [How To Backwards Compatibility (And Why For)](http://codemanship.co.uk/parlezuml/blog/?postid=1482).
- Martin Fowler, [TolerantReader](https://martinfowler.com/bliki/TolerantReader.html).
- Michael Feathers, [Breaking and Mending Compatibility](https://michaelfeathers.silvrback.com/breaking-and-mending-compatibility).

## Design Patterns

- Robert Martin, [The Little Singleton](https://8thlight.com/blog/uncle-bob/2015/06/30/the-little-singleton.html).

## Design Principles

- J. B. Rainsberger, [Modularity. Details. Pick One.](http://blog.thecodewhisperer.com/permalink/modularity-details-pick-one/)
- James Shore, [Quality With a Name](http://www.jamesshore.com/Articles/Quality-With-a-Name.html).
- Jason Gorman, [S.T.O.L.I.D. OO Design Principles](http://codemanship.co.uk/parlezuml/blog/?postid=1267).
- Jeff Atwood, [Curly's Law: Do One Thing](https://blog.codinghorror.com/curlys-law-do-one-thing/).
- Martin Fowler, [BeckDesignRules](http://martinfowler.com/bliki/BeckDesignRules.html).
- Martin Fowler, [TellDontAsk](http://martinfowler.com/bliki/TellDontAsk.html).
- Martin Fowler, [Yagni](http://martinfowler.com/bliki/Yagni.html).
- Robert Martin, [The Open Closed Principle](https://8thlight.com/blog/uncle-bob/2014/05/12/TheOpenClosedPrinciple.html).
- Robert Martin, [The Single Responsibility Principle](https://8thlight.com/blog/uncle-bob/2014/05/08/SingleReponsibilityPrinciple.html).
- Sandro Mancuso, [Balanced Abstraction Principle](https://codurance.com/2015/01/27/balanced-abstraction-principle/).

## Domain-Driven Design

- Alberto Brandolini, [Introducing Event Storming](http://ziobrando.blogspot.ca/2013/11/introducing-event-storming.html).
- Martin Fowler, [BoundedContext](http://martinfowler.com/bliki/BoundedContext.html).
- Martin Fowler, [CQRS](https://martinfowler.com/bliki/CQRS.html).
- Martin Fowler, [EvansClassification](http://martinfowler.com/bliki/EvansClassification.html).
- Martin Fowler, [ValueObject](http://martinfowler.com/bliki/ValueObject.html).

## Evolutionary Design and Up-Front Design

- James Shore, [Design Mindsets](http://www.jamesshore.com/Blog/Design%20Mindsets.html).
- James Shore, [Drawing the Line on Continuous Design](http://www.jamesshore.com/Blog/DrawingTheLineOnContinuousDesign.html).
- James Shore, [The Other Side of Design](http://www.jamesshore.com/Blog/The-Other-Side-of-Design.html).
- Jason Gorman, [Stepping Back to See The Bigger Picture](http://codemanship.co.uk/parlezuml/blog/?postid=1285).
- Martin Fowler, [AssetCapture](http://martinfowler.com/bliki/AssetCapture.html).
- Martin Fowler, [Is Design Dead?](http://martinfowler.com/articles/designDead.html).
- Martin Fowler, [StranglerApplication](http://martinfowler.com/bliki/StranglerApplication.html).
- Robert Martin, [The Scatology of Agile Architecture](https://sites.google.com/site/unclebobconsultingllc/home/articles/the-scatology-of-agile-architecture).

## Inversion of Control and Dependency Injection

- J. B. Rainsberger, [Keep Dependency Injection Simple](http://blog.thecodewhisperer.com/permalink/keep-dependency-injection-simple).
- J. B. Rainsberger, [Injecting dependencies doesn't have to hurt](http://blog.thecodewhisperer.com/permalink/injecting-dependencies-doesnt-have-to-hurt/).
- James Shore, [Dependency Injection Demystified](http://www.jamesshore.com/Blog/Dependency-Injection-Demystified.html).
- Martin Fowler, [Inversion of Control Containers and the Dependency Injection pattern](http://www.martinfowler.com/articles/injection.html).
- Nat Pryce, [Dependency "Injection" Considered Harmful](http://www.natpryce.com/articles/000783.html).
- Robert Martin, [Dependency Injection Inversion](https://sites.google.com/site/unclebobconsultingllc/blogs-by-robert-martin/dependency-injection-inversion).

## Microservices

- Kristof Adriaenssens, [Synchronous communication for microservices: current status and learnings](https://developers.soundcloud.com/blog/synchronous-communication-for-microservices-current-status-and-learnings).
- Lukasz Plotnicki, [BFF @ SoundCloud](https://www.thoughtworks.com/insights/blog/bff-soundcloud).
- Martin Fowler, [Microservice Trade-Offs](https://martinfowler.com/articles/microservice-trade-offs.html).
- Matt Stine, [What’s Your Decomposition Strategy?](https://builttoadapt.io/whats-your-decomposition-strategy-e19b8e72ac8f).
- Michael Nygard, Keep 'Em Separated:
  - [Keep ‘Em Separated](http://www.michaelnygard.com/blog/2017/11/keep-em-separated/)
  - [The Entity Service Antipattern](http://www.michaelnygard.com/blog/2017/12/the-entity-service-antipattern/)
  - [Services by Lifecycle](http://www.michaelnygard.com/blog/2018/01/services-by-lifecycle/)
- Neal Ford and Rebecca Parsons, [Microservices as an Evolutionary Architecture](https://www.thoughtworks.com/insights/blog/microservices-evolutionary-architecture).
- Phil Calçado, Building Products at SoundCloud:
  - [Building Products at SoundCloud — Part I: Dealing with the Monolith](https://developers.soundcloud.com/blog/building-products-at-soundcloud-part-1-dealing-with-the-monolith)
  - [Building Products at SoundCloud — Part II: Breaking the Monolith](https://developers.soundcloud.com/blog/building-products-at-soundcloud-part-2-breaking-the-monolith)
  - [Building Products at SoundCloud — Part III: Microservices in Scala and Finagle](https://developers.soundcloud.com/blog/building-products-at-soundcloud-part-3-microservices-in-scala-and-finagle)
- Simon Brown, [Distributed big balls of mud](http://www.codingthearchitecture.com/2014/07/06/distributed_big_balls_of_mud.html).
- Tom Stuart, [Microservices and the monolith](https://developers.soundcloud.com/blog/microservices-and-the-monolith).

## Object-Oriented Analysis and Design

- Jason Gorman, [The Big Giant Object Oriented Analysis & Design Blog Post](http://codemanship.co.uk/parlezuml/blog/?postid=1304).

## Object-Oriented and Functional Programming

- Michael Feathers, [Tell Above, and Ask Below - Hybridizing OO and Functional Design](http://michaelfeathers.typepad.com/michael_feathers_blog/2012/03/tell-above-and-ask-below-hybridizing-oo-and-functional-design.html).

## Object-Oriented Programming and Relational Databases

- Robert Martin, [Dance you Imps!](https://8thlight.com/blog/uncle-bob/2013/10/01/Dance-You-Imps.html).

## Refactoring

- J. B. Rainsberger, [Rescuing Legacy Code by Extracting Pure Functions](http://blog.thecodewhisperer.com/permalink/rescuing-legacy-code-by-extracting-pure-functions/).
- J. B. Rainsberger, [Your Constructors are Completely Irrational](http://blog.thecodewhisperer.com/permalink/your-constructors-are-completely-irrational/).
- Jay Fields, [Refactoring Motivations](http://blog.jayfields.com/2007/12/refactoring-motivations.html).
- Martin Fowler, [OpportunisticRefactoring](http://martinfowler.com/bliki/OpportunisticRefactoring.html).
- Michael Feathers, [When A Method Can Do Nothing](https://michaelfeathers.silvrback.com/when-it-s-okay-for-a-method-to-do-nothing).
- Nat Pryce, [Complaining about Other People's Code](http://www.natpryce.com/articles/000756.html).
- Ron Jeffries, [Refactoring -- Not on the backlog!](http://ronjeffries.com/xprog/articles/refactoring-not-on-the-backlog/).

## Risk Management

- Simon Brown, [Risk-storming: A collaborative and visual technique for identifying risk](http://www.codingthearchitecture.com/2012/07/11/risk_storming.html).

## Serverless Architecture

- Gojko Adzic, [Serverless architectures: game-changer or a recycled fad?](https://gojko.net/2016/08/27/serverless.html).
- Mike Roberts, [Serverless Architectures](https://martinfowler.com/articles/serverless.html).

## Software Architecture

- Martin Fowler, [InternalReprogrammability](http://martinfowler.com/bliki/InternalReprogrammability.html).
- Martin Fowler, [SacrificialArchitecture](http://martinfowler.com/bliki/SacrificialArchitecture.html).
- Martin Fowler, [What do you mean by “Event-Driven”?](https://martinfowler.com/articles/201701-event-driven.html).
- Michael Feathers, [Moving Past the Scaling Myth: Discontinuous Transition in Process and Architecture](https://michaelfeathers.silvrback.com/the-myth-of-scaling).
- Michael Feathers, [Negative Architecture: Guiding software by flipping figure and ground](https://michaelfeathers.silvrback.com/negative-architecture).
- Michael Nygard, [Architecting for Latency](http://www.michaelnygard.com/blog/2007/11/architecting-for-latency/).
- Michael Nygard, [Documenting Architecture Decisions](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions).
- Michael Nygard, Fault, Error, Failure, Availability and Stability:
  - [Fault, Error, Failure](http://www.michaelnygard.com/blog/2016/11/fault/)
  - [Availability and Stability](http://www.michaelnygard.com/blog/2016/11/availability-and-stability/)
- Michael Nygard, [The Perils of Semantic Coupling](http://www.michaelnygard.com/blog/2015/04/the-perils-of-semantic-coupling/).
- Neal Ford, [Why Everyone (Eventually) Hates (or Leaves) Maven](http://nealford.com/memeagora/2013/01/22/why_everyone_eventually_hates_maven.html).
- Patrick Kua, [The Well Rounded Architect](https://www.thekua.com/atwork/2016/11/the-well-rounded-architect/).
- Robert Martin, [Service Oriented Agony](https://8thlight.com/blog/uncle-bob/2012/02/01/Service-Oriented-Agony.html).
- Robert Martin, [The Clean Architecture](https://8thlight.com/blog/uncle-bob/2012/08/13/the-clean-architecture.html).

## Technical Debt

- Bill Clark, [A Taxonomy of Tech Debt](https://engineering.riotgames.com/news/taxonomy-tech-debt).
- Erik Dietrich, [The Human Cost of Tech Debt](http://www.daedtech.com/human-cost-tech-debt/).
- Henrik Kniberg, [Good and Bad Technical Debt (and how TDD helps)](http://blog.crisp.se/2013/10/11/henrikkniberg/good-and-bad-technical-debt).
- Michael Feathers, [Toward a Galvanizing Definition of Technical Debt](https://michaelfeathers.silvrback.com/toward-a-galvanizing-definition-of-technical-debt).
- Michael Nygard, [The Fear Cycle](http://www.michaelnygard.com/blog/2015/07/the-fear-cycle/).
- Tom Grant, [Technical Debt Is A Systemic Problem, Not A Personal Failing](http://www.netobjectives.com/blogs/technical-debt-systemic-problem-not-personal-failing).
