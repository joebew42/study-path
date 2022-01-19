*This study path is released under the [**CC BY-SA 4.0**](https://creativecommons.org/licenses/by-sa/4.0/) license*

## Introduction

Welcome to this study path, or if you like, the learning path. Is a path about **software development practices and design principles**. It's open and freely accessible to everyone who wants to dig into topics like _Clean Code_, _Test-Driven Development_, _Refactoring_, _Clean Architecture_, _Legacy Code_, _Domain-Driven Design_, _Microservices_, and much more.

The materials are all organized in sections based on specific topics. There is no order to follow. You can skim through all the sections, look for anything specific, follow only a few sections, or just start reading from the very beginning to the end. It's your choice!

I am willing to keep this study path always updated, and I would invite you to contribute to this project by submitting any material you believe will improve it.

**Why this study path?** Few years ago I worked as a mentor for an intern in Agile Software Development, and I wanted to provide a clear path to follow. At that time, the study was covering Clean Code, Test-Driven Development, and other few topics. By the time, with the support of other people, we enhanced the study path with more and more content!

Enjoy!

## Getting Started

- Get familiar with [the Pomodoro Technique](http://pomodorotechnique.com/) (read the [paper](assets/cirillo-pomodoro-technique.pdf)) 
- Read the [Manifesto for Agile Software Development](http://agilemanifesto.org/)
- Read the [Principles behind the Agile Manifesto](http://agilemanifesto.org/principles.html)
- Read the [Manifesto for Software Craftsmanship](http://manifesto.softwarecraftsmanship.org/)

## Session 1: SOLID and Clean Code

- Watch [Core Design Principles for Software Developers](https://www.youtube.com/watch?v=llGgO74uXMI)
- Read the [SOLID principles](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod)
  - [SRP: Single Responsibility Principle](https://docs.google.com/open?id=0ByOwmqah_nuGNHEtcU5OekdDMkk)
  - [OCP: Open-Closed Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgN2M5MTkwM2EtNWFkZC00ZTI3LWFjZTUtNTFhZGZiYmUzODc1&hl=en)
  - [LSP: Liskov Substitution Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgNzAzZjA5ZmItNjU3NS00MzQ5LTkwYjMtMDJhNDU5ZTM0MTlh&hl=en)
  - [ISP: Interface Segregation Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgOTViYjJhYzMtMzYxMC00MzFjLWJjMzYtOGJiMDc5N2JkYmJi&hl=en)
  - [DIP: Dependency Inversion Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgMjdlMWIzNGUtZTQ0NC00ZjQ5LTkwYzQtZjRhMDRlNTQ3ZGMz&hl=en)
- Exercise: Look at the [Racing Car Katas](https://github.com/emilybache/Racing-Car-Katas)
  - Try to find where the SOLID principles are violated
- Read the [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)
  - Chapter 1: Clean Code
  - Chapter 2: Meaningful Names
  - Chapter 3: Functions
  - Chapter 6: Objects and Data Structures
  - Chapter 7: Error Handling
  - Chapter 10: Classes
- Read [The Pragmatic Programmer](https://pragprog.com/titles/tpp20/the-pragmatic-programmer-20th-anniversary-edition/)
  - Chapter 2: A Pragmatic Approach
  - Chapter 5: Bend or Break
  - Chapter 6: While You Are Coding
- Read [The Art of Enbugging](http://www.ccs.neu.edu/research/demeter/related-work/pragmatic-programmer/jan_03_enbug.pdf): Tell, don't ask / Law of Demeter
- Read [YAGNI](https://martinfowler.com/bliki/Yagni.html)

## Session 2: Test-Driven Development

- Read [TDD by example](http://www.amazon.com/Test-Driven-Development-By-Example/dp/0321146530)
  - Study the `Part I: The Money Example`
  - Exercise: Try to repeat it with a programming language at your choice.
- Read [Growing Object-Oriented Software, guided by tests](https://www.amazon.com/Growing-Object-Oriented-Software-Guided-Tests/dp/0321503627)
  - Chapter 1: What is the point of Test-Driven Development?
  - Chapter 2: Test-Driven Development with Objects
  - Chapter 4: Kick-Starting the Test-Driven Cycle
  - Chapter 5: Maintaining the Test-Driven Cycle
- Unit Tests
  - Read Chapter 9: Unit Tests of [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)
  - Watch [The Clean Code Talks - Unit Testing](https://www.youtube.com/watch?v=wEhu57pih5w)
  - Read [Effective Unit Testing](https://www.amazon.com/Effective-Unit-Testing-guide-developers/dp/1935182579)
    - Part 1: Foundations
    - Part 2: Catalog
- Read [desirable properties of tests](https://medium.com/@kentbeck_7670/test-desiderata-94150638a4b3)
  - Watch [the video playlist](https://www.youtube.com/playlist?list=PLlmVY7qtgT_lkbrk9iZNizp978mVzpBKl)

## Session 3: Refactoring

- Watch [Workflows of Refactoring](https://www.youtube.com/watch?v=vqEg37e4Mkw)
- Read [Refactoring: Improving the design of existing code](http://www.amazon.com/Refactoring-Improving-Design-Existing-Code/dp/0201485672)
  - Chapter 1: Refactoring, a First Example
    - Try to repeat the [example code](https://github.com/joebew42/refactoring-day/tree/master/movie-rental/java)
  - Chapter 2: Principles in Refactoring
  - Chapter 3: Bad Smells in Code
- Exercise: Try to find and refactor the code smells in these Code Katas:
  - [Tennis Refactoring Kata](https://github.com/emilybache/Tennis-Refactoring-Kata)
  - [Gilded Rose Kata](https://github.com/joebew42/GildedRose)
  - What Code Smells you have found?
    - What steps you followed to remove them?
    - What difficulties you have faced?

## Session 4: Working with Legacy Code

- Read [Working Effectively with Legacy Code](http://www.amazon.com/Working-Effectively-Legacy-Michael-Feathers/dp/0131177052)
  - Chapter 1: Changing Software
  - Chapter 2: Working with Feedback
  - Chapter 4: The Seam Model
  - Chapter 8: How Do I Add a Feature ?
  - Chapter 13: I Need to Make Changes, but I Don't Know What Tests to Write
  - Chapter 25: Dependency-Breaking Techniques
- Read [Working Effectively with Legacy Tests](http://natpryce.com/articles/000813.html)
- Exercise: Try the [Gilded Rose Kata](https://github.com/joebew42/GildedRose)
  - Add code coverage
  - Add the new feature
  - Refactor the code
- Watch how other tackled the Gilded Rose Kata:
  - Watch [All the Little Things](https://www.youtube.com/watch?v=8bZh5LMaSmE)
  - Watch "Writing test cases using Approval Tests" ([Part I](https://www.youtube.com/watch?v=zyM2Ep28ED8), [Part II](https://www.youtube.com/watch?v=OJmg9aMxPDI), [Part III](https://www.youtube.com/watch?v=NADVhSjeyJA))
- Watch [Testing and Refactoring Legacy Code](https://www.youtube.com/watch?v=_NnElPO5BU0)
  - Exercise: Try to repeat the [Code Kata](https://github.com/sandromancuso/trip-service-kata)
- Read more about [Approval Testing](http://www.methodsandtools.com/archive/approvaltest.php) and some examples:
  - [Characterization Testing](https://michaelfeathers.silvrback.com/characterization-testing)
  - [Mutation Testing](https://www.guru99.com/mutation-testing.html)
  - [Golden Master and Sampling](https://blog.thecodewhisperer.com/permalink/surviving-legacy-code-with-golden-master-and-sampling)
    - [How Not To Write Golden Master Tests](https://blog.thecodewhisperer.com/permalink/how-not-to-write-golden-master-tests)
  - Exercise: Try to test and refactor the [Ugly trivia game](https://github.com/jbrains/trivia)
    - Which is the approach you prefer to apply? Why?
- Watch [Surviving a legacy codebase: tactics and tools](https://www.youtube.com/watch?v=NGfvguzMjqw)
  - Read the [Slides of the talk](https://www.slideshare.net/pierodibello/surviving-to-a-legacy-codebase-codemotion-berlin-2018-edition)
  - Have access to the [example code](https://github.com/xpepper/fifty-shades-of-legacy-goose-game) for further practice

## Session 5: Testing, Design and Test-Driven Development

- Watch [The deep synergy between testability and good design](https://www.youtube.com/watch?v=4cVZvoFGJTU)
- Watch [How to Write Clean, Testable Code](https://www.youtube.com/watch?v=XcT4yYu_TTs)
- Watch [TDD and Software Design](https://www.youtube.com/watch?v=ty3p5VDcoOI)
- Read [Good Design is Easily-Learned](http://blog.scottbellware.com/2009/01/good-design-is-easily-learned.html)
- Exercise: Try to learn and repeat these Code Kata autonomously
  - [The Bowling Game Kata](http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata)
  - [The Roman Numerals Kata](http://www.codekatas.org/casts/roman-numerals-kata-with-audio-commentary)
- Watch [Unit Testing](https://www.youtube.com/watch?v=wEhu57pih5w)
- Read [Growing Object Oriented Software, Guided by Tests](http://www.growing-object-oriented-software.com/)
  - Chapter 6: Object-Oriented Style
  - Chapter 7: Achieving Object-Oriented Design
  - Chapter 8: Building on Third-Party Code
- Read [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)
  - Chapter 8: Boundaries
- Watch [The Magic Tricks of Testing](https://www.youtube.com/watch?v=URSWYvyc42M)
- Read [Mocks Aren't Stubs](http://martinfowler.com/articles/mocksArentStubs.html)
- Exercises:
  - Try the [String Calculator Kata](http://osherove.com/tdd-kata-1/)
    - With [interactions](http://osherove.com/tdd-kata-2/)
  - Try the [Game Of Life Kata](https://kata-log.rocks/game-of-life-kata)
  - Try the [Tic Tac Toe Kata](https://kata-log.rocks/tic-tac-toe-kata)

## Session 6: Practice with a new Programming Language

Principles and Practices are not dependent on any particular programming language, rather they act as support or enabler to learn and get comfortable with programming languages and tools we never used before.

Now that you have learned something about _the good principles and practices of software development_, try to grab a new programming language which you never used before and try to repeat some of the Code Katas you already have done previously:

- [Fizz Buzz Kata](http://codingdojo.org/cgi-bin/index.pl?KataFizzBuzz)
- [The Bowling Game Kata](http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata)
- [String Calculator Kata](http://osherove.com/tdd-kata-1/)
- [The Roman Numerals Kata](http://www.codekatas.org/casts/roman-numerals-kata-with-audio-commentary)
- [Game Of Life Kata](https://kata-log.rocks/game-of-life-kata)
- [Tic Tac Toe Kata](https://kata-log.rocks/tic-tac-toe-kata)
- [Opening Hours Kata](https://github.com/christian-fei/opening-hours-kata)
- [Racing Car Katas](https://github.com/emilybache/Racing-Car-Katas)
- Repeat the Money Example of TDD by Example
- [Gilded Rose Kata](https://github.com/joebew42/GildedRose)

If you are looking for more Code Katas to learn and practice with your new programming language, try to give a look at [Kata-Log](https://kata-log.rocks/).

## Session 7: The Clean Architecture

- Read [Hexagonal Architecture](https://web.archive.org/web/20090122225311/http://alistair.cockburn.us/Hexagonal+architecture)
- Read [The Onion Architecture](https://jeffreypalermo.com/2008/07/the-onion-architecture-part-1/)
- Read [The Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
- Watch [Clean Architecture and Design](https://www.youtube.com/watch?v=2dKZ-dWaCiU)
- Watch [Lean Agile Scotland "Crafted Design"](https://vimeo.com/107963074)
- Watch [Jax London 2014 "Crafted Design"](https://vimeo.com/128596005)
- Watch [Spring I/O 2019 Clean Architecture](https://www.youtube.com/watch?v=cPH5AiqLQTo)
- Exercises:
  - Try the [Social Networking Kata](https://github.com/sandromancuso/social_networking_kata)
  - Try the [Greeting Service Kata](https://github.com/joebew42/greeting-service-kata)
- Once you have done one of the previous Code Kata, try to build and deploy your application
  - Read [The Twelve-Factor App](http://12factor.net/)
  - Publish the code on a `GitHub` repository
  - Setup a CI environment (e.g. Travis/CircleCI/CodeShip)
  - Deploy your application automatically (e.g. Heroku)
  - Write a suite of tests to check the deployed application is working as expected
- Take a look at this [reference implementation on Clean Architecture](https://github.com/ivanpaulovich/clean-architecture-manga)

## Session 8: Domain-Driven Design

- Watch [Tackling Complexity in the Heart of Software](https://www.youtube.com/watch?v=dnUFEg68ESM)
- Read [Domain-Driven Design Quickly](https://www.infoq.com/minibooks/domain-driven-design-quickly)
  - Chapter 1: What Is Domain-Driven Design
  - Chapter 2: The Ubiquitous Language
  - Chapter 3: Model-Driven Design
  - Chapter 4: Refactoring Toward Deeper Insight
  - Chapter 5: Preserving Model Integrity
- Read [DDD: Putting the Model to Work](https://www.infoq.com/presentations/model-to-work-evans)
- Read [How to write a Repository](http://philcalcado.com/2010/12/23/how_to_write_a_repository.html)
- Watch [DDD and Microservices: At last, some boundaries!](https://vimeo.com/125769142)
- Recommended readings:
  - [Domain-Driven Design: Tackling Complexity in the Heart of Software](https://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215)
  - [Implementing Domain-Driven Design](https://www.amazon.it/dp/0321834577)
  - [Domain-Driven Design Reference: Definitions and Pattern Summaries](https://www.amazon.com/Domain-Driven-Design-Reference-Definitions-Summaries/dp/1457501198)

## Session 9: Microservices

- Read [Microservices: A Definition of This New Architectural Term](https://martinfowler.com/articles/microservices.html)
- Watch [Microservices](https://www.youtube.com/watch?v=wgdBVIX9ifA)
- Watch [Principles Of Microservices](https://www.youtube.com/watch?v=PFQnNFe27kU)
- Read [Microservice Trade-Offs](http://martinfowler.com/articles/microservice-trade-offs.html)
- Read [Microservice Architecture: Aligning Principles, Practices, and Culture](https://www.amazon.com/dp/1491956259)
  - Chapter 1: The Microservices Way
  - Chapter 2: The Microservices Value Proposition
  - Chapter 3: Designing Microservice Systems
  - Chapter 4: Establishing a Foundation
  - Chapter 5: Service Design
- Read [Building Microservices: Designing Fine-Grained Systems](https://www.amazon.com/Building-Microservices-Sam-Newman/dp/1491950358)
  - Chapter 1: Microservices
  - Chapter 2: The Evolutionary Architect
  - Chapter 3: How to Model Services
  - Chapter 4: Integration
  - Chapter 5: Splitting the Monolith
  - Chapter 6: Deployment
  - Chapter 7: Testing
  - Chapter 8: Monitoring
  - Chapter 11: Microservices at Scale
  - Watch the Book Reading Club ([part I](https://www.youtube.com/watch?v=Caj-qCOniXM) - [part II](https://www.youtube.com/watch?v=zS57uYLzF1I) - [part III](https://www.youtube.com/watch?v=DAVMB_Tc00w))
- Watch [Practical Considerations For Microservice Architecture](https://vimeo.com/105751281)
- Watch [Microservices Antipatterns](https://www.youtube.com/watch?v=I56HzTKvZKc)
- Read [Seven Microservices Anti-patterns](https://www.infoq.com/articles/seven-uservices-antipatterns)
- Transactions and consistency in distributed systems
  - Watch [Using sagas to maintain data consistency in a microservice architecture](https://www.youtube.com/watch?v=YPbGW3Fnmbc)
  - Watch [Applying the Saga Pattern](https://www.youtube.com/watch?v=xDuwrtwYHu8)
- Access to more [examples and resources](https://gist.github.com/pdincau/8e6d42dfc44cf158e70293604bae0c17)

## Session 10: Further topics

- Simple Design
  - Read [Beck Design Rules](https://martinfowler.com/bliki/BeckDesignRules.html)
  - Read [Emergent Design](http://ronjeffries.com/xprog/classics/expemergentdesign/)
  - Read [The Four Elements of Simple Design](http://blog.jbrains.ca/permalink/the-four-elements-of-simple-design)
  - Read [Putting An Age-Old Battle To Rest](http://blog.thecodewhisperer.com/permalink/putting-an-age-old-battle-to-rest)
  - Read Chapter 12 of [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882): Emergence
- Watch Outside-in TDD ([part I](https://www.youtube.com/watch?v=XHnuMjah6ps) - [part II](https://www.youtube.com/watch?v=gs0rqDdz3ko) - [part III](https://www.youtube.com/watch?v=R9OAt9AOrzI))
- Read [TDD by example](http://www.amazon.com/Test-Driven-Development-By-Example/dp/0321146530)
  - Patterns for Test-Driven Development
- CQRS and Event Sourcing:
  - Watch [CQRS and Event Sourcing](https://www.youtube.com/watch?v=JHGkaShoyNs)
  - Watch [CQRS with Erlang](https://vimeo.com/97318824)
  - Watch [A Decade of DDD, CQRS, Event Sourcing](https://www.youtube.com/watch?v=LDW0QWie21s)
  - Read [CQRS Journey](http://cqrsjourney.github.io/)
- Exercises:
  - Try the [Salary Slip Kata](https://github.com/sandromancuso/salaryslipkata)
  - Try the [Bank Account Kata](https://github.com/sandromancuso/Bank-kata)
    - Try to implement a variant using a CQRS/ES approach

## Recommended Readings

This section provides a list of recommended books readings that have not been mentioned directly in this study path, but of significant importance.

- [The Nature of Software Development](https://www.amazon.com/Nature-Software-Development-Simple-Valuable/dp/1941222374)
- [Extreme Programming Explained: Embrace Change (2nd Edition)](https://www.amazon.com/Extreme-Programming-Explained-Embrace-Change-ebook/dp/B000OZ0N5S)
- [The Agile Samurai: How Agile Masters Deliver Great Software](https://www.amazon.com/Agile-Samurai-Software-Pragmatic-Programmers/dp/1934356581)
- [Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation](https://www.amazon.com/Continuous-Delivery-Deployment-Automation-Addison-Wesley/dp/0321601912)
- [Release It!: Design and Deploy Production-Ready Software](https://www.amazon.com/Release-Production-Ready-Software-Pragmatic-Programmers/dp/0978739213)
- [Beyond Legacy Code: Nine Practices to Extend the Life (and Value) of Your Software](https://www.amazon.com/Beyond-Legacy-Code-Practices-Software/dp/1680500791)
- [The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win](https://www.amazon.com/Phoenix-Project-DevOps-Helping-Business/dp/0988262509)
