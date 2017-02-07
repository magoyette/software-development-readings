# Software Development Readings

My personal compilation of online texts about software development.

***

<!-- Table of contents is generated with doctoc -->
<!-- sudo npm install -g doctoc -->
<!-- doctoc README.md -->
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Agile](#agile)
  - [Agile in General](#agile-in-general)
  - [Agile Methodologies](#agile-methodologies)
  - [Agile Practices](#agile-practices)
  - [Agile Tips](#agile-tips)
  - [Continuous Improvement](#continuous-improvement)
  - [Scrum](#scrum)
- [BDD and Specification by Example](#bdd-and-specification-by-example)
  - [BDD](#bdd)
  - [Cucumber](#cucumber)
  - [Gherkin and Given-When-Then](#gherkin-and-given-when-then)
  - [Stories in BDD](#stories-in-bdd)
- [Business](#business)
  - [Business Transformations](#business-transformations)
  - [Company Culture](#company-culture)
- [Career and Productivity](#career-and-productivity)
  - [Career and Hiring](#career-and-hiring)
  - [Leadership](#leadership)
  - [Productivity, Creativity and Focus](#productivity-creativity-and-focus)
- [Coding](#coding)
  - [Bugs](#bugs)
  - [Clean Code](#clean-code)
  - [Coding in General](#coding-in-general)
  - [Coding Tips](#coding-tips)
  - [Documentation](#documentation)
  - [Fun Stuff](#fun-stuff)
  - [Logging](#logging)
- [Continuous Delivery and DevOps](#continuous-delivery-and-devops)
  - [Antifragility and Embracing Failure](#antifragility-and-embracing-failure)
  - [Continuous Delivery Infrastructure](#continuous-delivery-infrastructure)
  - [DevOps Culture](#devops-culture)
  - [Monitoring](#monitoring)
- [Continuous Integration](#continuous-integration)
  - [Continuous Integration Coding Techniques](#continuous-integration-coding-techniques)
  - [Git](#git)
  - [Version Control](#version-control)
- [Databases](#databases)
  - [Database Design](#database-design)
- [Java](#java)
  - [Javadoc](#javadoc)
- [Open Source Software](#open-source-software)
  - [Best Practices](#best-practices)
  - [GitHub](#github)
- [Software Architecture and Technical Leadership](#software-architecture-and-technical-leadership)
  - [Domain-Driven Design](#domain-driven-design)
  - [Microservices](#microservices)
  - [Microservices at SoundCloud](#microservices-at-soundcloud)
  - [Risk Management](#risk-management)
  - [Serverless Architecture](#serverless-architecture)
  - [Software Architecture](#software-architecture)
  - [Software Architecture Anti-Patterns](#software-architecture-anti-patterns)
  - [Tech Leads](#tech-leads)
- [Software Craftsmanship](#software-craftsmanship)
  - [Code Reviews](#code-reviews)
  - [Collective Code Ownership and Pair Programming](#collective-code-ownership-and-pair-programming)
  - [Software Craftsmanship in General](#software-craftsmanship-in-general)
- [Software Design](#software-design)
  - [API Design](#api-design)
  - [Code Smells](#code-smells)
  - [Design Patterns](#design-patterns)
  - [Design Principles](#design-principles)
  - [Design Tips](#design-tips)
  - [Evolutionary Design and Up-Front Design](#evolutionary-design-and-up-front-design)
  - [Inversion of Control and Dependency Injection](#inversion-of-control-and-dependency-injection)
  - [Object-Oriented Analysis and Design](#object-oriented-analysis-and-design)
  - [Object-Oriented and Functional Programming](#object-oriented-and-functional-programming)
  - [Object-Oriented Programming and Relational Databases](#object-oriented-programming-and-relational-databases)
  - [Refactoring](#refactoring)
  - [Refactoring Legacy Code](#refactoring-legacy-code)
  - [Technical Debt](#technical-debt)
- [Technical Writing](#technical-writing)
- [Testing](#testing)
  - [Acceptance Testing](#acceptance-testing)
  - [Automated Tests in General](#automated-tests-in-general)
  - [Contract Tests](#contract-tests)
  - [End-to-End Testing](#end-to-end-testing)
  - [Exploratory Testing](#exploratory-testing)
  - [Mutation Testing](#mutation-testing)
  - [QA environment](#qa-environment)
  - [Test Doubles](#test-doubles)
  - [Test-Driven Development](#test-driven-development)
  - [Types of Tests](#types-of-tests)
  - [Unit Testing](#unit-testing)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Agile

### Agile in General

- Dave Thomas, [Agile is Dead (Long Live Agility)](https://pragdave.me/blog/2014/03/04/time-to-kill-agile/).

### Agile Methodologies

- Ben Linders, [Don't Copy the Spotify Model](https://www.infoq.com/news/2016/10/no-spotify-model).

### Agile Practices

- Chelsea Komlo and Maria Gomez, [Incorporating Security Best Practices into Agile Teams](https://www.thoughtworks.com/insights/blog/incorporating-security-best-practices-agile-teams).
- Jason Yip, [It's Not Just Standing Up: Patterns for Daily Standup Meetings](http://martinfowler.com/articles/itsNotJustStandingUp.html).
- Mattias Skarin, [12 seemingly normal things Agile people do](http://blog.crisp.se/2016/04/04/mattiasskarin/12-seemingly-normal-things-agile-people-do).
- Michael Nygard, [A Dozen Levels of Done](http://www.michaelnygard.com/blog/2007/11/a-dozen-levels-of-done/).

### Agile Tips

- Jason Gorman, [The Small Teams Manifesto](http://codemanship.co.uk/parlezuml/blog/?postid=1322).
- Martin Fowler, [FrequencyReducesDifficulty](http://martinfowler.com/bliki/FrequencyReducesDifficulty.html).

### Continuous Improvement

- Michael Nygard, [In Love With Your Warts](http://www.michaelnygard.com/blog/2016/04/in-love-with-your-warts/).

### Scrum

- Mike Cohn, [Choose Backlog Items That Serve Two Purposes](http://www.mountaingoatsoftware.com/blog/choose-backlog-items-that-serve-two-purposes).
- Mike Cohn, [User Stories, Epics and Themes](https://www.mountaingoatsoftware.com/blog/stories-epics-and-themes).
- Ralph Jocham and Henk Jan Huizer, [Gone are Release Planning and the Release Burndown](https://www.scrum.org/About/All-Articles/articleType/ArticleView/articleId/17/Gone-are-Release-Planning-and-the-Release-Burndown).

## BDD and Specification by Example

### BDD

- Aslak Hellesøy, [Aslak's view of BDD](https://cucumber.io/blog/2015/03/27/aslaks-view-of-bdd).
- Lisa Crispin, [Experiment with Example Mapping](http://lisacrispin.com/2016/06/02/experiment-example-mapping/).
- Dan North, [Introducing BDD](https://dannorth.net/introducing-bdd/).
- Matt Wynne, [Introducing Example Mapping](https://cucumber.io/blog/2015/12/08/example-mapping-introduction).
- Liz Keogh, [Step Away from the Tools](https://lizkeogh.com/2011/03/04/step-away-from-the-tools/).

### Cucumber

- Theo England, Cucumber anti-patterns:
  - [Cucumber anti-patterns (part one)](https://cucumber.io/blog/2016/07/01/cucumber-antipatterns-part-one)
  - [Cucumber anti-patterns (part two)](https://cucumber.io/blog/2016/08/31/cucumber-anti-patterns-part-two)
- Steve Tooke, [The Cucumber Test Trap](http://tooky.co.uk/the-cucumber-test-trap/).

### Gherkin and Given-When-Then

- Gojko Adzic, [Focus on key examples](https://gojko.net/2014/05/05/focus-on-key-examples/).
- Gojko Adzic, [How to get the most out of Given-When-Then](https://gojko.net/2015/02/25/how-to-get-the-most-out-of-given-when-then/).

### Stories in BDD

- Dan North, [What’s in a Story?](https://dannorth.net/whats-in-a-story/).
- Gojko Adzic, [Throw user stories away after they are delivered](https://gojko.net/2014/03/25/throw-user-stories-away-after-they-are-delivered/).
- Gojko Adzic, [User stories should be about behaviour changes](https://gojko.net/2014/02/12/user-stories-should-be-about-behaviour-changes/).
- Matt Wynne, [Features != User Stories](http://blog.mattwynne.net/2010/10/22/features-user-stories/).

## Business

### Business Transformations

- Jurgen Appelo, [How to Save Your Business](http://noop.nl/2016/04/how-to-save-your-business.html).
- Michael Nygard, [Beyond the Village](http://www.michaelnygard.com/blog/2008/07/beyond-the-village/).

### Company Culture

- Brian Chesky, [Don’t Fuck Up the Culture](https://medium.com/@bchesky/dont-fuck-up-the-culture-597cde9ee9d4#.ol8414xuy).

## Career and Productivity

### Career and Hiring

- Dan Luu, [We only hire the best means we only hire the trendiest](http://danluu.com/programmer-moneyball/).
- Jay Fields, [Be Your Start-Up](http://blog.jayfields.com/2008/08/be-your-start-up.html).
- Michael Lopp, [Shields Down](http://randsinrepose.com/archives/shields-down/).

### Leadership

- Michael Lopp, [Five Leadership Hacks](http://randsinrepose.com/archives/five-leadership-hacks/).

### Productivity, Creativity and Focus

- Jay Fields, [Is Productivity Killing Your Creativity?](http://blog.jayfields.com/2012/05/is-productivity-killing-your-creativity.html).
- Joel Spolsky, [Human Task Switches Considered Harmful](https://www.joelonsoftware.com/2001/02/12/human-task-switches-considered-harmful/).
- Jason Fried, [Restoring Sanity to the Office](https://m.signalvnoise.com/restoring-sanity-to-the-office-d9d35dd8689e#.962qamz2m).
- Paul Graham, [Great Hackers](http://www.paulgraham.com/gh.html).
- Paul Graham, [Maker's Schedule, Manager's Schedule](http://www.paulgraham.com/makersschedule.html).

## Coding

### Bugs

- Joel Spolsky, [Hard-assed Bug Fixin’](https://www.joelonsoftware.com/2001/07/31/hard-assed-bug-fixin/).

### Clean Code

- Martin Fowler, [FunctionLength](https://martinfowler.com/bliki/FunctionLength.html).

### Coding in General

- Dan Luu, [Normalization of deviance in software: how broken practices become standard](https://danluu.com/wat/).
- David Cassel, [Hype-Driven Development, from Frameworks to Microservices](http://thenewstack.io/programmers-react-warning-hype-driven-development/).
- James Hague, [Recovering From a Computer Science Education](http://prog21.dadgum.com/123.html).
- James Hague, [You Can't Sit on the Sidelines and Become a Philosopher](http://prog21.dadgum.com/197.html).
- James Hague, [You Don't Want to Think Like a Programmer](http://prog21.dadgum.com/190.html).
- Joel Spolsky, [Five Worlds](https://www.joelonsoftware.com/2002/05/06/five-worlds/).
- Joel Spolsky, [In Defense of Not-Invented-Here Syndrome](https://www.joelonsoftware.com/2001/10/14/in-defense-of-not-invented-here-syndrome/).
- Joel Spolsky, [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets (No Excuses!)](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/).
- Joel Spolsky, [The Law of Leaky Abstractions](https://www.joelonsoftware.com/2002/11/11/the-law-of-leaky-abstractions/).
- Paul Graham, [Holding a Program in One's Head](http://www.paulgraham.com/head.html).

### Coding Tips

- Dariusz Pasciak, [Alternatives to boolean parameters](https://8thlight.com/blog/dariusz-pasciak/2015/05/28/alternatives-to-boolean-parameters.html).

### Documentation

- Tom Preston-Werner, [Readme Driven Development](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html).

### Fun Stuff

- Luke Maciak, [What does your favorite text editor say about you?](http://www.terminally-incoherent.com/blog/2007/08/14/what-does-your-favorite-text-editor-say-about-you/).

### Logging

- Alexander Tarlinder, [Think twice before logging](http://blog.crisp.se/2015/06/21/alexandertarlinder/think-twice-before-logging).

## Continuous Delivery and DevOps

### Antifragility and Embracing Failure

- Michael Nygard, The New Normal:
  - [The New Normal: Failure is a Good Thing](http://blog.cognitect.com/blog/2016/2/3/the-new-normal-failure-is-a-good-thing)
  - [The New Normal: From Resilient to Antifragile](http://blog.cognitect.com/blog/2016/2/18/the-new-normal-from-resilient-to-antifragile)
  - [The New Normal: No Silver Bullet](http://blog.cognitect.com/blog/2016/2/25/the-new-normal-no-silver-bullet)
  - [The New Normal: Minimize Risk by Maximizing Change](http://blog.cognitect.com/blog/2016/3/3/the-new-normal-minimize-risk-by-maximizing-change)
  - [The New Normal: Protected Asset or Disposable Inventory?](http://blog.cognitect.com/blog/2016/3/17/the-new-normal-protected-asset-or-disposable-inventory)
  - [The New Normal: Embracing Failure with Netflix, the Chaos Monkey, and Chaos Kong](http://blog.cognitect.com/blog/2016/3/24/the-new-normal-embracing-failure-with-netflix-the-chaos-monkey-and-chaos-kong)
  - [The New Normal: The Art of War, Maneuverability, and Microservices](http://blog.cognitect.com/blog/2016/3/31/the-new-normal-the-art-of-war-maneuverability-and-microservices)
  - [The New Normal: Everything Relies on Sharp Tools](http://blog.cognitect.com/blog/2016/4/22/the-new-normal-everything-relies-on-sharp-tools)
  - [The New Normal: Team Scale Autonomy](http://blog.cognitect.com/blog/2016/6/16/the-new-normal-team-scale-autonomy)
  - [The New Normal: Data Leverage](http://blog.cognitect.com/blog/2016/6/28/the-new-normal-data-leverage)
  - [The New Normal: Failure Domains and Safety](http://blog.cognitect.com/blog/2016/7/7/the-new-normal-failure-domains-and-safety)
  - [The New Normal: Mean Time To Reaction](http://blog.cognitect.com/blog/2016/8/11/the-new-normal-mean-time-to-reaction)
  - [The New Normal: Tempo, Flow, and Maneuverability](http://blog.cognitect.com/blog/2016/8/18/the-new-normal-tempo-flow-and-maneuverability)
- Michael Nygard, [Quantum Backups](http://www.michaelnygard.com/blog/2009/03/quantum-backups/).
- Steve Freeman, [Test-Driven Development and Embracing Failure](http://higherorderlogic.com/2011/04/tdd-embracing-failure/).

### Continuous Delivery Infrastructure

- Martin Fowler, [InfrastructureAsCode](http://martinfowler.com/bliki/InfrastructureAsCode.html).

### DevOps Culture

- Elisabeth Hendrickson, [I Prefer This Over That](http://testobsessed.com/2015/05/i-prefer-this-over-that/).
- Rouan Wilsenach, [DevOpsCulture](https://martinfowler.com/bliki/DevOpsCulture.html).

### Monitoring

- Flávia Falé and Serge Gebhardt, [SyntheticMonitoring](https://martinfowler.com/bliki/SyntheticMonitoring.html).
- Mathias Meyer, [The Virtues of Monitoring](http://www.paperplanes.de/2011/1/5/the_virtues_of_monitoring.html).

## Continuous Integration

### Continuous Integration Coding Techniques

- Martin Fowler, [FeatureToggle](http://martinfowler.com/bliki/FeatureToggle.html).
- Martin Fowler, [BranchByAbstraction](http://martinfowler.com/bliki/BranchByAbstraction.html).

### Git

- Chris Beams, [How to Write a Git Commit Message](http://chris.beams.io/posts/git-commit/).
- Ryan Tomayko, [The Thing About Git](http://2ndscale.com/rtomayko/2008/the-thing-about-git).
- Vincent Driessen, [A successful Git branching model](http://nvie.com/posts/a-successful-git-branching-model/).
- Zach Holman, [Utter Disregard for Git Commit History](https://zachholman.com/posts/git-commit-history/).

### Version Control

- Dan Luu, [Advantages of monolithic version control](http://danluu.com/monorepo/).
- Martin Fowler, [FeatureBranch](http://martinfowler.com/bliki/FeatureBranch.html).
- Martin Fowler, [SemanticConflict](http://martinfowler.com/bliki/SemanticConflict.html).

## Databases

### Database Design

- Pramod Sadalage and Martin Fowler, [Evolutionary Database Design](https://martinfowler.com/articles/evodb.html).

## Java

### Javadoc

- Stephen Colebourne, [Javadoc coding standards](http://blog.joda.org/2012/11/javadoc-coding-standards.html).

## Open Source Software

### Best Practices

- Michael Klishin, How to Make Your Open Source Project Really Awesome:
  - [How to Make Your Open Source Project Really Awesome](http://blog.clojurewerkz.org/blog/2013/04/20/how-to-make-your-open-source-project-really-awesome/)
  - [How to Make Your Open Source Project Really Awesome, Part 2](http://blog.clojurewerkz.org/blog/2014/07/20/how-to-make-your-open-source-project-really-awesome/)

### GitHub

- Jono Bacon, [10 tips for new GitHub projects](https://opensource.com/business/16/6/10-tips-new-github-projects).

## Software Architecture and Technical Leadership

### Domain-Driven Design

- Alberto Brandolini, [Introducing Event Storming](http://ziobrando.blogspot.ca/2013/11/introducing-event-storming.html).
- Martin Fowler, [BoundedContext](http://martinfowler.com/bliki/BoundedContext.html).
- Martin Fowler, [CQRS](https://martinfowler.com/bliki/CQRS.html).
- Martin Fowler, [EvansClassification](http://martinfowler.com/bliki/EvansClassification.html).
- Martin Fowler, [ValueObject](http://martinfowler.com/bliki/ValueObject.html).

### Microservices

- Martin Fowler, [Microservice Trade-Offs](https://martinfowler.com/articles/microservice-trade-offs.html).
- Neal Ford and Rebecca Parsons, [Microservices as an Evolutionary Architecture](https://www.thoughtworks.com/insights/blog/microservices-evolutionary-architecture).
- Simon Brown, [Distributed big balls of mud](http://www.codingthearchitecture.com/2014/07/06/distributed_big_balls_of_mud.html).

### Microservices at SoundCloud

- Kristof Adriaenssens, [Synchronous communication for microservices: current status and learnings](https://developers.soundcloud.com/blog/synchronous-communication-for-microservices-current-status-and-learnings).
- Lukasz Plotnicki, [BFF @ SoundCloud](https://www.thoughtworks.com/insights/blog/bff-soundcloud).
- Phil Calçado, Building Products at SoundCloud:
  - [Building Products at SoundCloud — Part I: Dealing with the Monolith](https://developers.soundcloud.com/blog/building-products-at-soundcloud-part-1-dealing-with-the-monolith)
  - [Building Products at SoundCloud — Part II: Breaking the Monolith](https://developers.soundcloud.com/blog/building-products-at-soundcloud-part-2-breaking-the-monolith)
  - [Building Products at SoundCloud — Part III: Microservices in Scala and Finagle](https://developers.soundcloud.com/blog/building-products-at-soundcloud-part-3-microservices-in-scala-and-finagle)
- Tom Stuart, [Microservices and the monolith](https://developers.soundcloud.com/blog/microservices-and-the-monolith).

### Risk Management

- Simon Brown, [Risk-storming: A collaborative and visual technique for identifying risk](http://www.codingthearchitecture.com/2012/07/11/risk_storming.html).

### Serverless Architecture

- Gojko Adzic, [Serverless architectures: game-changer or a recycled fad?](https://gojko.net/2016/08/27/serverless.html).

### Software Architecture

- Martin Fowler, [InternalReprogrammability](http://martinfowler.com/bliki/InternalReprogrammability.html).
- Martin Fowler, [SacrificialArchitecture](http://martinfowler.com/bliki/SacrificialArchitecture.html).
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

### Software Architecture Anti-Patterns

- Martin Fowler, [AnemicDomainModel](http://www.martinfowler.com/bliki/AnemicDomainModel.html).

### Tech Leads

- Patrick Kua, [3 Tips for building a Technical Vision](https://www.thekua.com/atwork/2016/03/3-tips-for-building-a-technical-vision/).
- Patrick Kua, [A Tech Lead Paradox: Consistency vs Improvement](https://www.thekua.com/atwork/2014/11/a-tech-lead-paradox-consistency-vs-improvement/).
- Patrick Kua, [A Tech Lead Paradox: Delivering vs Learning](https://www.thekua.com/atwork/2014/11/a-tech-lead-paradox-delivering-vs-learning/).
- Patrick Kua, [A Tech Lead Paradox: Technical Needs vs Business Needs](https://www.thekua.com/atwork/2014/12/a-tech-lead-paradox-technical-needs-vs-business-needs/).
- Patrick Kua, [How do I still write code as a Tech Lead?](https://www.thekua.com/atwork/2014/11/how-do-i-still-write-code-as-a-tech-lead/).
- Patrick Kua, [Tech Lead – Circles of Responsibility](https://www.thekua.com/atwork/2015/06/tech-lead-circles-of-responsibility/).
- Patrick Kua, [The Definition of a Tech Lead](https://www.thekua.com/atwork/2014/11/the-definition-of-a-tech-lead/).
- Patrick Kua, [Top 5 Mistakes for First Time Tech Leads](https://www.thekua.com/atwork/2014/10/top-5-mistakes-for-first-time-tech-leads/).
- Patrick Kua, [You may not need a Tech Lead, but others do](https://www.thekua.com/atwork/2016/12/you-may-not-need-a-tech-lead-but-others-do/).

## Software Craftsmanship

### Code Reviews

- Bruce Johnson, [What we learned from Google: code reviews aren’t just for catching bugs](https://blog.fullstory.com/what-we-learned-from-google-code-reviews-arent-just-for-catching-bugs-b125a13aa292#.pww8lj8nd).

### Collective Code Ownership and Pair Programming

- Daniel Irvine, [The egoless programmer](https://8thlight.com/blog/daniel-irvine/2016/09/30/the-egoless-programmer.html).
- Jay Fields, [Experience Report: Weak Code Ownership](http://blog.jayfields.com/2015/02/experience-report-weak-code-ownership.html).

### Software Craftsmanship in General

- James Gorman, [Why Software Craftsmanship Needs To Stop Worrying About The Colour Of The Bike Shed & Focus On The Big Issues](http://codemanship.co.uk/parlezuml/blog/?postid=1298).
- Jay Fields, [Passionate, Not Dogmatic](http://blog.jayfields.com/2008/09/passionate-not-dogmatic.html).

## Software Design

### API Design

- Danilo Sato, [ParallelChange](http://martinfowler.com/bliki/ParallelChange.html).

### Code Smells

- James Shore, [Primitive Obsession](http://www.jamesshore.com/Blog/PrimitiveObsession.html).
- Nat Pryce, [Message Obsession](http://www.natpryce.com/articles/000816.html).

### Design Patterns

- Robert Martin, [The Little Singleton](https://8thlight.com/blog/uncle-bob/2015/06/30/the-little-singleton.html).

### Design Principles

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

### Design Tips

- Steve Freeman, [Unpack the bag](http://higherorderlogic.com/2008/09/unpack-the-bag/).

### Evolutionary Design and Up-Front Design

- James Shore, [Design Mindsets](http://www.jamesshore.com/Blog/Design%20Mindsets.html).
- James Shore, [Drawing the Line on Continuous Design](http://www.jamesshore.com/Blog/DrawingTheLineOnContinuousDesign.html).
- James Shore, [The Other Side of Design](http://www.jamesshore.com/Blog/The-Other-Side-of-Design.html).
- Jason Gorman, [Stepping Back to See The Bigger Picture](http://codemanship.co.uk/parlezuml/blog/?postid=1285).
- Martin Fowler, [AssetCapture](http://martinfowler.com/bliki/AssetCapture.html).
- Martin Fowler, [Is Design Dead?](http://martinfowler.com/articles/designDead.html).
- Martin Fowler, [StranglerApplication](http://martinfowler.com/bliki/StranglerApplication.html).
- Robert Martin, [The Scatology of Agile Architecture](https://sites.google.com/site/unclebobconsultingllc/home/articles/the-scatology-of-agile-architecture).

### Inversion of Control and Dependency Injection

- J. B. Rainsberger, [Injecting dependencies doesn't have to hurt](http://blog.thecodewhisperer.com/permalink/injecting-dependencies-doesnt-have-to-hurt/).
- James Shore, [Dependency Injection Demystified](http://www.jamesshore.com/Blog/Dependency-Injection-Demystified.html).
- Martin Fowler, [Inversion of Control Containers and the Dependency Injection pattern](http://www.martinfowler.com/articles/injection.html).
- Nat Pryce, [Dependency "Injection" Considered Harmful](http://www.natpryce.com/articles/000783.html).
- Robert Martin, [Dependency Injection Inversion](https://sites.google.com/site/unclebobconsultingllc/blogs-by-robert-martin/dependency-injection-inversion).

### Object-Oriented Analysis and Design

- Jason Gorman, [The Big Giant Object Oriented Analysis & Design Blog Post](http://codemanship.co.uk/parlezuml/blog/?postid=1304).

### Object-Oriented and Functional Programming

- Michael Feathers, [Tell Above, and Ask Below - Hybridizing OO and Functional Design](http://michaelfeathers.typepad.com/michael_feathers_blog/2012/03/tell-above-and-ask-below-hybridizing-oo-and-functional-design.html).

### Object-Oriented Programming and Relational Databases

- Robert Martin, [Dance you Imps!](https://8thlight.com/blog/uncle-bob/2013/10/01/Dance-You-Imps.html).

### Refactoring

- Jay Fields, [Refactoring Motivations](http://blog.jayfields.com/2007/12/refactoring-motivations.html).
- Martin Fowler, [OpportunisticRefactoring](http://martinfowler.com/bliki/OpportunisticRefactoring.html).
- Nat Pryce, [Complaining about Other People's Code](http://www.natpryce.com/articles/000756.html).
- Ron Jeffries, [Refactoring -- Not on the backlog!](http://ronjeffries.com/xprog/articles/refactoring-not-on-the-backlog/).

### Refactoring Legacy Code

- J. B. Rainsberger, [Rescuing Legacy Code by Extracting Pure Functions](http://blog.thecodewhisperer.com/permalink/rescuing-legacy-code-by-extracting-pure-functions/).
- J. B. Rainsberger, [Your Constructors are Completely Irrational](http://blog.thecodewhisperer.com/permalink/your-constructors-are-completely-irrational/).

### Technical Debt

- Erik Dietrich, [The Human Cost of Tech Debt](http://www.daedtech.com/human-cost-tech-debt/).
- Henrik Kniberg, [Good and Bad Technical Debt (and how TDD helps)](http://blog.crisp.se/2013/10/11/henrikkniberg/good-and-bad-technical-debt).
- Michael Nygard, [The Fear Cycle](http://www.michaelnygard.com/blog/2015/07/the-fear-cycle/).
- Stephen Freeman, [Bad code isn't Technical Debt, it's an unhedged Call Option](http://higherorderlogic.com/2010/07/bad-code-isnt-technical-debt-its-an-unhedged-call-option/).
- Tom Grant, [Technical Debt Is A Systemic Problem, Not A Personal Failing](http://www.netobjectives.com/blogs/technical-debt-systemic-problem-not-personal-failing).

## Technical Writing

- Jay Fields, [Example Dilemma](http://blog.jayfields.com/2008/03/example-dilemma.html).

## Testing

### Acceptance Testing

- James Shore, [Alternatives to Acceptance Testing](http://www.jamesshore.com/Blog/Alternatives-to-Acceptance-Testing.html).
- James Shore, [The Problems With Acceptance Testing](http://www.jamesshore.com/Blog/The-Problems-With-Acceptance-Testing.html).

### Automated Tests in General

- Gojko Adzic, [Five ways to reduce the cost of large test suites](https://gojko.net/favourites/testing/agile/2016/05/24/large-test-suites.html).
- J. B. Rainsberger, [Clearing Up the Integrated Tests Scam](http://blog.thecodewhisperer.com/permalink/clearing-up-the-integrated-tests-scam/).
- Jay Fields, [Thoughts on Developer Testing](http://blog.jayfields.com/2009/02/thoughts-on-developer-testing.html).

### Contract Tests

- Martin Fowler, [IntegrationContractTest](https://martinfowler.com/bliki/IntegrationContractTest.html).

### End-to-End Testing

- Adam Bender, [Testing on the Toilet: What Makes a Good End-to-End Test?](https://testing.googleblog.com/2016/09/testing-on-toilet-what-makes-good-end.html).

### Exploratory Testing

- Gojko Adzic, [Explore capabilities, not features](https://gojko.net/2015/03/12/explore-capabilities-not-features/).
- Lisa Crispin, [Pair Testing](http://lisacrispin.com/2016/09/22/pair-testing/).

### Mutation Testing

- Robert Martin, [Mutation Testing](http://blog.cleancoder.com/uncle-bob/2016/06/10/MutationTesting.html).

### QA environment

- Michael Nygard, [QA Instability Implies Production Instability](http://www.michaelnygard.com/blog/2016/07/qa-instability-implies-production-instability/).

### Test Doubles

- J. B. Rainsberger, [When is it safe to introduce test doubles?](http://blog.thecodewhisperer.com/permalink/when-is-it-safe-to-introduce-test-doubles/).
- Martin Fowler, [Mocks Aren't Stubs](http://martinfowler.com/articles/mocksArentStubs.html).
- Robert Martin, [When to Mock](https://8thlight.com/blog/uncle-bob/2014/05/10/WhenToMock.html).

### Test-Driven Development

- J. B. Rainsberger, [How TDD Affects My Designs](http://blog.thecodewhisperer.com/permalink/how-tdd-affects-my-designs/).
- J. B. Rainsberger, [What your tests don't need to know will hurt you](http://blog.thecodewhisperer.com/permalink/what-your-tests-dont-need-to-know-will-hurt-you).
- J. B. Rainsberger, [Your Tests Are Dragging You Down](http://blog.thecodewhisperer.com/permalink/your-tests-are-dragging-you-down/).
- Jason Gorman, [Classic TDD Mistake - Writing Design-Driven Tests](http://codemanship.co.uk/parlezuml/blog/?postid=1375).
- Jason Gorman, [Squaring The Circle of "Tell, Don't Ask" vs. Test As Close To Implementation As Possible](http://codemanship.co.uk/parlezuml/blog/?postid=1379).
- Jason Gorman, [TDD & Mocks - Working Backwards From Expectations](http://codemanship.co.uk/parlezuml/blog/?postid=1159).
- Jason Gorman, [Triangulating Your Test Code](http://codemanship.co.uk/parlezuml/blog/?postid=1315).
- Jason Gorman, [What Not To Do In a TDD Pair Programming Interview](http://codemanship.co.uk/parlezuml/blog/?postid=1324).
- Jay Fields, Some Test Driven Development observations:
  - [Some Test Driven Development observations](http://blog.jayfields.com/2006/06/some-test-driven-development.html)
  - [More Test Driven Development observations](http://blog.jayfields.com/2006/06/more-test-driven-development.html)
- Nat Pryce, [Two Hypotheses per Test](http://www.natpryce.com/articles/000775.html).
- Robert Martin, [Test First](https://8thlight.com/blog/uncle-bob/2013/09/23/Test-first.html).
- Robert Martin, [The Cycles of TDD](http://blog.cleancoder.com/uncle-bob/2014/12/17/TheCyclesOfTDD.html).
- Robert Martin, [The Frenzied Panic of Rushing](https://8thlight.com/blog/uncle-bob/2013/03/11/TheFrenziedPanicOfRushing.html).
- Robert Martin, [The Pragmatics of TDD](https://8thlight.com/blog/uncle-bob/2013/03/06/ThePragmaticsOfTDD.html).
- Robert Martin, [When Should You Think?](https://8thlight.com/blog/uncle-bob/2014/03/11/when-to-think.html).

### Types of Tests

- Nat Pryce, [Visualising Test Terminology](http://www.natpryce.com/articles/000772.html).

### Unit Testing

- Alex Eagle, [Testing on the Toilet: Change-Detector Tests Considered Harmful](https://testing.googleblog.com/2015/01/testing-on-toilet-change-detector-tests.html).
- Andrew Trenk, [Testing on the Toilet: Prefer Testing Public APIs Over Implementation-Detail Classes](https://testing.googleblog.com/2015/01/testing-on-toilet-prefer-testing-public.html).
- Ben Yu, [Testing on the Toilet: Keep Cause and Effect Clear](https://testing.googleblog.com/2017/01/testing-on-toilet-keep-cause-and-effect.html).
- Bill Wake, [3A – Arrange, Act, Assert](http://xp123.com/articles/3a-arrange-act-assert/).
- James Shore, [Testing Private Methods](http://www.jamesshore.com/Blog/Testing-Private-Methods.html).
- Jay Fields, [Tests reflect code quality](http://blog.jayfields.com/2008/02/tests-reflect-code-quality.html).
- Michael Feathers, [A Set of Unit Testing Rules](http://www.artima.com/weblogs/viewpost.jsp?thread=126923).
- Nat Pryce, Test Data Builders:
  - [Test Data Builders: an alternative to the Object Mother pattern](http://www.natpryce.com/articles/000714.html).
  - [Tricks with Test Data Builders: Defining Common State](http://www.natpryce.com/articles/000724.html).
  - [Tricks with Test Data Builders: Combining Builders](http://www.natpryce.com/articles/000726.html).
  - [Tricks with Test Data Builders: Emphase the Domain Model with Factory Methods](http://www.natpryce.com/articles/000727.html).
  - [Tricks with Test Data Builders: Refactoring Away Duplicated Logic Creates a Domain Specific Embedded Language for Testing](http://www.natpryce.com/articles/000728.html).
