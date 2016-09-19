# Software Development Readings

My personal compilation of online texts about software development.

***

## Table of Contents

- [Java](#java)
  - [Javadoc](#javadoc)
- [Open Source Software](#open-source-software)
  - [Best Practices](#best-practices)
- [Software Design and Architecture](#software-design-and-architecture)
  - [Inversion of Control and Dependency Injection](#inversion-of-control-and-dependency-injection)
  - [Object-Oriented Programming](#object-oriented-programming)
  - [Software Design](#software-design)
- [Software Development](#software-development)
  - [Technical Debt](#technical-debt)
- [Testing](#testing)
  - [Unit Testing and Test-Driven Development](#unit-testing-and-test-driven-development)

## Java

### Javadoc

- Stephen Colebourne, [Javadoc coding standards](http://blog.joda.org/2012/11/javadoc-coding-standards.html). A blog post about how to write good Javadoc.

## Open Source Software

### Best Practices

- Michael Klishin, [How to Make Your Open Source Project Really Awesome](http://blog.clojurewerkz.org/blog/2013/04/20/how-to-make-your-open-source-project-really-awesome/). Many best practices for open source projects.
- Michael Klishin, [How to Make Your Open Source Project Really Awesome, Part 2](http://blog.clojurewerkz.org/blog/2014/07/20/how-to-make-your-open-source-project-really-awesome/). More best practices for open source projects.

## Software Design and Architecture

### Inversion of Control and Dependency Injection

- J. B. Rainsberger, [Injecting dependencies doesn't have to hurt](http://blog.thecodewhisperer.com/permalink/injecting-dependencies-doesnt-have-to-hurt/). Some guidelines about when to use dependency injection.
- James Shore, [Dependency Injection Demystified](http://www.jamesshore.com/Blog/Dependency-Injection-Demystified.html). An explanation of what is dependency injection, without any libraries.
- Martin Fowler, [Inversion of Control Containers and the Dependency Injection pattern](http://www.martinfowler.com/articles/injection.html). A comparison of dependency injection and service locator.
- Robert Martin, [Dependency Injection Inversion](https://sites.google.com/site/unclebobconsultingllc/blogs-by-robert-martin/dependency-injection-inversion). Robert Martin explains the benefits of manual dependency injection over dependency injection libraries like Guice.

### Object-Oriented Programming

- Robert Martin, [Dance you Imps!](https://8thlight.com/blog/uncle-bob/2013/10/01/Dance-You-Imps.html). A blog post about the differences between relational tables and objects.

### Software Design

- James Shore, [Quality With a Name](http://www.jamesshore.com/Articles/Quality-With-a-Name.html). A blog post about what is good design.

## Software Development

### Technical Debt

- Stephen Freeman, [Bad code isn't Technical Debt, it's an unhedged Call Option](http://higherorderlogic.com/2010/07/bad-code-isnt-technical-debt-its-an-unhedged-call-option/). A blog post about how the unpredictability of technical debt is similar to unhedged call options.

## Testing

### Unit Testing and Test-Driven Development

- J. B. Rainsberger, [How TDD Affects My Designs](http://blog.thecodewhisperer.com/permalink/how-tdd-affects-my-designs/). J. B. Rainsberger explains the impact of TDD on the way he design software.
- J. B. Rainsberger, [What your tests don't need to know will hurt you](http://blog.thecodewhisperer.com/permalink/what-your-tests-dont-need-to-know-will-hurt-you). A blog post about how to avoid irrelevant details in tests.
- J. B. Rainsberger, [When is it safe to introduce test doubles?](http://blog.thecodewhisperer.com/permalink/when-is-it-safe-to-introduce-test-doubles/). A blog post that explains when to use mocks with the Domain-Driven Design concepts of service, entity and value.
- James Carr, [TDD Anti-Patterns](http://blog.james-carr.org/2006/11/03/tdd-anti-patterns/). A short catalog of unit testing anti-patterns.
- James Shore, [Testing Private Methods](http://www.jamesshore.com/Blog/Testing-Private-Methods.html). An explanation of why private methods should not be tested directly.
- Jason Gorman, [Squaring The Circle of "Tell, Don't Ask" vs. Test As Close To Implementation As Possible](http://codemanship.co.uk/parlezuml/blog/?postid=1379). A blog post about how to find balance between testing the internal state of objects and Tell, Don't Ask.
- Martin Fowler, [Mocks Aren't Stubs](http://martinfowler.com/articles/mocksArentStubs.html). An article about the difference between mocks and stubs. Also compares the classical and mockist TDD styles.
- Robert Martin, [The Frenzied Panic of Rushing](https://8thlight.com/blog/uncle-bob/2013/03/11/TheFrenziedPanicOfRushing.html). A blog post about why TDD does not slow down development.
- Robert Martin, [The Pragmatics of TDD](https://8thlight.com/blog/uncle-bob/2013/03/06/ThePragmaticsOfTDD.html). A blog post about when TDD should be used.
- Robert Martin, [When Should You Think?](https://8thlight.com/blog/uncle-bob/2014/03/11/when-to-think.html). A blog post about TDD and thinking before coding.
- Robert Martin, [When to Mock](https://8thlight.com/blog/uncle-bob/2014/05/10/WhenToMock.html). A blog post about when mocks should be used.
