_This study path is released under the [**CC BY-SA 4.0**](https://creativecommons.org/licenses/by-sa/4.0/) license_

## Introduction

Welcome to this **Study Path on Software Development**: a curated, open, and ever-evolving learning path focused on practices of software development, principles of software design, and software architecture.

Whether you are interested in **Clean Code**, **Test-Driven Development**, **Refactoring**, **Clean Architecture**, **Legacy Code**, **Domain-Driven Design**, **Microservices**, or other essential topics, I hope you will find structured, high-quality resources here to guide with your growth.

The study path is organized into themed sections. There is no strict order to follow, you are free to:

- Browse through all the sessions
- Dive into topics that interest you most
- Follow the entire path from start to finish

**How you use it is entirely up to you.**

This project started years ago when I mentored an intern in Agile Software Development. At that time I wanted to offer a clear, practical roadmap for learning foundational concepts, like clean code and TDD. Over time, with the support of other people, this study path has grown - and continues to grow - into a broader resource for developers at all levels.

I am committed keeping this path up to date and valuable. If you have suggestions or resources to contribute, your input is more than welcome!

**Enjoy the journey, and happy learning!**

## 🧭 Getting Started

> _Kick off your journey by learning how to stay focused, work iteratively, and embrace the mindset of continuous improvement through Agile values and time management techniques._

- Get familiar with [the Pomodoro Technique](http://pomodorotechnique.com/) (read the [paper](assets/cirillo-pomodoro-technique.pdf))
- Read [TODO List: One thing at a time!](https://joebew42.github.io/2020/07/08/todo/)
- Read the [Manifesto for Agile Software Development](http://agilemanifesto.org/)
- Read the [Principles behind the Agile Manifesto](http://agilemanifesto.org/principles.html)
- Read the [Manifesto for Software Craftsmanship](http://manifesto.softwarecraftsmanship.org/)

## 📐 Session 1: SOLID and Clean Code

> _Discover the core design principles that help you write code that is easy to understand, change, and grow: the building blocks of sustainable software_

- Watch [Core Design Principles for Software Developers](https://www.youtube.com/watch?v=llGgO74uXMI)
- Read the [SOLID principles](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod)
  - [SRP: Single Responsibility Principle](https://docs.google.com/open?id=0ByOwmqah_nuGNHEtcU5OekdDMkk)
  - [OCP: Open-Closed Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgN2M5MTkwM2EtNWFkZC00ZTI3LWFjZTUtNTFhZGZiYmUzODc1&hl=en)
  - [LSP: Liskov Substitution Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgNzAzZjA5ZmItNjU3NS00MzQ5LTkwYjMtMDJhNDU5ZTM0MTlh&hl=en)
  - [ISP: Interface Segregation Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgOTViYjJhYzMtMzYxMC00MzFjLWJjMzYtOGJiMDc5N2JkYmJi&hl=en)
  - [DIP: Dependency Inversion Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgMjdlMWIzNGUtZTQ0NC00ZjQ5LTkwYzQtZjRhMDRlNTQ3ZGMz&hl=en)
- Exercise: Look at the [Racing Car Katas](https://github.com/emilybache/Racing-Car-Katas)
  - Try to find where the SOLID principles are violated
- Read the [Clean Code: A Handbook of Agile Software Craftsmanship](https://www.goodreads.com/book/show/3735293-clean-code)
  - Chapter 1: Clean Code
  - Chapter 2: Meaningful Names
  - Chapter 3: Functions
  - Chapter 6: Objects and Data Structures
  - Chapter 7: Error Handling
  - Chapter 10: Classes
- Read [The Pragmatic Programmer: From Journeyman to Master](https://www.goodreads.com/book/show/4099.The_Pragmatic_Programmer)
  - Chapter 2: A Pragmatic Approach
  - Chapter 5: Bend or Break
  - Chapter 6: While You Are Coding
- Read [The Art of Enbugging](http://www.ccs.neu.edu/research/demeter/related-work/pragmatic-programmer/jan_03_enbug.pdf): Tell, don't ask / Law of Demeter
- Read [YAGNI](https://martinfowler.com/bliki/Yagni.html)
- Watch [SOLID for functional programming](https://www.youtube.com/watch?v=rmftOs2BzgU) (a case study of SOLID principles applied in Elixir)

## 🔴🟢🔵 Session 2: Test-Driven Design (TDD)

> _Learn how tests can help to drive the design of your code, how tests can lead to a better feedback loop, and less code! A key skill in modern development workflows._

- Read [Test-Driven Development: By Example](https://www.goodreads.com/book/show/387190.Test_Driven_Development)
  - Study the `Part I: The Money Example`
  - Exercise: Try to repeat it with a programming language at your choice.
- Read [Growing Object-Oriented Software, Guided by Tests](https://www.goodreads.com/book/show/4268826-growing-object-oriented-software-guided-by-tests)
  - Chapter 1: What is the point of Test-Driven Development?
  - Chapter 2: Test-Driven Development with Objects
  - Chapter 4: Kick-Starting the Test-Driven Cycle
  - Chapter 5: Maintaining the Test-Driven Cycle
- Unit Tests
  - Read Chapter 9: Unit Tests of [Clean Code](https://www.goodreads.com/book/show/3735293-clean-code)
  - Watch [The Clean Code Talks - Unit Testing](https://www.youtube.com/watch?v=wEhu57pih5w)
  - Read [Effective Unit Testing](https://www.goodreads.com/book/show/17282399-effective-unit-testing)
    - Part 1: Foundations
    - Part 2: Catalog
- Read [desirable properties of tests](https://medium.com/@kentbeck_7670/test-desiderata-94150638a4b3)
  - Watch [the video playlist](https://www.youtube.com/playlist?list=PLlmVY7qtgT_lkbrk9iZNizp978mVzpBKl)
- Read [Working Effectively with Unit Tests](https://leanpub.com/wewut/read)

## 🌱 Session 3: Refactoring

> _Sharpen your ability to improve the design of your code without changing its behavior. Recognize code smells, apply refactoring techniques, and keep your systems clean over time._

- Watch [Workflows of Refactoring](https://www.youtube.com/watch?v=vqEg37e4Mkw)
- Read [Refactoring: Improving the design of existing code](https://www.goodreads.com/book/show/44936.Refactoring)
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
- Try the [Refactoring Golf](https://github.com/daviddenton/refactoring-golf): Explore your IDE to see what's really possible using shortcuts and automation.

## 🧓🏻 Session 4: Working with Legacy Code

> _Master strategies and techniques to safely work in large, untested, or unfamiliar codebases. One of the most valuable real-world development skills for people who are dealing with legacy code at daily basis._

- Read [Working Effectively with Legacy Code](https://www.goodreads.com/book/show/44919.Working_Effectively_with_Legacy_Code)
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
  - Watch the alternative version [Testing and Refactoring Legacy Code - The Trip Service Kata - Part I](https://www.youtube.com/watch?v=pmoLmjirmTk)
    - And [Testing and Refactoring Legacy Code - The Trip Service Kata - Part II](https://www.youtube.com/watch?v=P1S9E_-yKBE): on OCP, Seam Model, and DIP.
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

## 🔄 Session 5: Testing, Design and Test-Driven Development

> _Explore the deeper relationship between testing and good design. Learn how testability often leads to better architecture, modularity, and clarity._

- Watch [The deep synergy between testability and good design](https://www.youtube.com/watch?v=4cVZvoFGJTU)
- Watch [How to Write Clean, Testable Code](https://www.youtube.com/watch?v=XcT4yYu_TTs)
- Watch [TDD and Software Design](https://www.youtube.com/watch?v=ty3p5VDcoOI)
- Read [Good Design is Easily-Learned](http://blog.scottbellware.com/2009/01/good-design-is-easily-learned.html)
- Exercise: Try to learn and repeat these Code Kata autonomously
  - [The Bowling Game Kata](http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata)
  - [The Roman Numerals Kata](http://www.codekatas.org/casts/roman-numerals-kata-with-audio-commentary)
- Watch [Unit Testing](https://www.youtube.com/watch?v=wEhu57pih5w)
- Read [Growing Object-Oriented Software, Guided by Tests](https://www.goodreads.com/book/show/4268826-growing-object-oriented-software-guided-by-tests)
  - Chapter 6: Object-Oriented Style
  - Chapter 7: Achieving Object-Oriented Design
  - Chapter 8: Building on Third-Party Code
- Read the [Clean Code: A Handbook of Agile Software Craftsmanship](https://www.goodreads.com/book/show/3735293-clean-code)
  - Chapter 8: Boundaries
- Watch [The Magic Tricks of Testing](https://www.youtube.com/watch?v=URSWYvyc42M)
- Read [Mocks Aren't Stubs](http://martinfowler.com/articles/mocksArentStubs.html)
- Exercises:
  - Try the [String Calculator Kata](http://osherove.com/tdd-kata-1/)
    - With [interactions](http://osherove.com/tdd-kata-2/)
  - Try the [Game Of Life Kata](https://kata-log.rocks/game-of-life-kata)
  - Try the [Tic Tac Toe Kata](https://kata-log.rocks/tic-tac-toe-kata)

## 🧸 Session 6: Practice with a new Programming Language

> _Apply your design and testing skills in a fresh language to reinforce your understanding and build true language-agnostic thinking._

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

## 🧼 Session 7: The Clean Architecture

> _Explore architectural choices that emphasize independence from frameworks, user interface, and databases, enabling a long-term flexibility and testability._

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

## 🗣️ Session 8: Domain-Driven Design (DDD)

> _Dive into modeling complex business domains with more clarity. Learn how to make your code to speak the language of the business and build software that truly reflects it._

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
  - [Domain-Driven Design: Tackling Complexity in the Heart of Software](https://www.goodreads.com/book/show/179133.Domain_Driven_Design)
  - [Implementing Domain-Driven Design](https://www.goodreads.com/book/show/15756865-implementing-domain-driven-design)
  - [Domain-Driven Design Reference: Definitions and Pattern Summaries](https://www.goodreads.com/book/show/23322716-domain-driven-design-reference)
  - [Domain Modeling Made Functional](https://www.goodreads.com/book/show/34921689-domain-modeling-made-functional)
- [Domain-Driven Design Starter Modelling Process](https://github.com/ddd-crew/ddd-starter-modelling-process)
  - A step-by-step guide for learning and practically applying each aspect of Domain-Driven Design (DDD) - from orienting around an organisation's business model to coding a domain model.

## 🔌 Session 9: Microservices

> _Understand how to better split systems into independently deployable services. Learn the benefits, trade-offs, and patterns that enables distributed architecture that better reflects business domains and support autonomous teams._

- Read [Microservices: A Definition of This New Architectural Term](https://martinfowler.com/articles/microservices.html)
- Watch [Microservices](https://www.youtube.com/watch?v=wgdBVIX9ifA)
- Watch [Principles Of Microservices](https://www.youtube.com/watch?v=PFQnNFe27kU)
- Read [Microservice Trade-Offs](http://martinfowler.com/articles/microservice-trade-offs.html)
- Read [Microservice Architecture: Aligning Principles, Practices, and Culture](https://www.goodreads.com/book/show/30827276-microservice-architecture-aligning-principles-practices-and-culture)
  - Chapter 1: The Microservices Way
  - Chapter 2: The Microservices Value Proposition
  - Chapter 3: Designing Microservice Systems
  - Chapter 4: Establishing a Foundation
  - Chapter 5: Service Design
- Read [Building Microservices: Designing Fine-Grained Systems](https://www.goodreads.com/book/show/22512931-building-microservices?)
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
- The other way around: [Monolith to Microservices: Evolutionary Patterns to Transform Your Monolith](https://www.goodreads.com/book/show/44144499-monolith-to-microservices)
  - Watch [Monolith Decomposition Patterns - Sam Newman](https://www.youtube.com/watch?v=64w1zbpHGTg)
  - Watch [microXchg 2016 - Rodrigue Schaefer : From monolith to microservices](https://www.youtube.com/watch?v=I9zpROdDf48)

## 🔭 Session 10: Further topics

> _Explore advanced techniques and design philosophies, from Event Sourcing to Simple Design, and more._

- Simple Design
  - Read [Beck Design Rules](https://martinfowler.com/bliki/BeckDesignRules.html)
  - Read [Emergent Design](http://ronjeffries.com/xprog/classics/expemergentdesign/)
  - Read [The Four Elements of Simple Design](http://blog.jbrains.ca/permalink/the-four-elements-of-simple-design)
  - Read [Putting An Age-Old Battle To Rest](http://blog.thecodewhisperer.com/permalink/putting-an-age-old-battle-to-rest)
  - Read Chapter 12 of [Clean Code](https://www.goodreads.com/book/show/3735293-clean-code): Emergence
  - Read [Understanding the Four Rules of Simple Design](https://leanpub.com/4rulesofsimpledesign)
- Watch Outside-in TDD ([part I](https://www.youtube.com/watch?v=XHnuMjah6ps) - [part II](https://www.youtube.com/watch?v=gs0rqDdz3ko) - [part III](https://www.youtube.com/watch?v=R9OAt9AOrzI))
- Read [Test-Driven Development: By Example](https://www.goodreads.com/book/show/387190.Test_Driven_Development)
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
- Watch [The Many Meanings of Event-Driven Architecture • Martin Fowler • GOTO 2017](https://www.youtube.com/watch?v=STKCRSUsyP0)
- Read [Growing systems towards DDD, Event-Sourcing and Event-Driven architecture](https://joebew42.github.io/2025/04/06/growing-systems-towards-ddd-event-sourcing-and-event-driven-architecture/)

## 📚 Recommended Readings

> This section provides a list of recommended books readings that have not been mentioned directly in this study path, but of significant importance.

- [The Nature of Software Development](https://www.goodreads.com/book/show/23016056-the-nature-of-software-development)
- [Extreme Programming Explained: Embrace Change (2nd Edition)](https://www.goodreads.com/book/show/58699420-extreme-programming-explained)
- [The Agile Samurai: How Agile Masters Deliver Great Software](https://www.goodreads.com/book/show/8248700-the-agile-samurai)
- [Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation](https://www.goodreads.com/book/show/8686650-continuous-delivery)
- [Release It!: Design and Deploy Production-Ready Software](https://www.goodreads.com/book/show/1069827.Release_It_)
- [Beyond Legacy Code: Nine Practices to Extend the Life (and Value) of Your Software](https://www.goodreads.com/book/show/26088456-beyond-legacy-code)
- [The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win](https://www.goodreads.com/book/show/17255186-the-phoenix-project)
