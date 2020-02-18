*This study path is released under the [**CC BY-SA 4.0**](https://creativecommons.org/licenses/by-sa/4.0/) license*

## Getting Started

- [The Pomodoro Technique](http://pomodorotechnique.com/) ([paper](http://baomee.info/pdf/technique/1.pdf))
- [Manifesto for Agile Software Development](http://www.agilemanifesto.org/)
- [Principles behind the Agile Manifesto](http://www.agilemanifesto.org/principles.html)
- [Manifesto for Software Craftsmanship](http://manifesto.softwarecraftsmanship.org/)

## Session 1: SOLID and Clean Code

- [Core Design Principles for Software Developers by Venkat Subramaniam](https://www.youtube.com/watch?v=llGgO74uXMI)
- [SOLID principles](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod)
  - [SRP: Single Responsability Principle](https://docs.google.com/open?id=0ByOwmqah_nuGNHEtcU5OekdDMkk)
  - [OCP: Open-Closed Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgN2M5MTkwM2EtNWFkZC00ZTI3LWFjZTUtNTFhZGZiYmUzODc1&hl=en)
  - [LSP: Liskov Substitution Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgNzAzZjA5ZmItNjU3NS00MzQ5LTkwYjMtMDJhNDU5ZTM0MTlh&hl=en)
  - [ISP: Interface Segregation Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgOTViYjJhYzMtMzYxMC00MzFjLWJjMzYtOGJiMDc5N2JkYmJi&hl=en)
  - [DIP: Dependency Inversion Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgMjdlMWIzNGUtZTQ0NC00ZjQ5LTkwYzQtZjRhMDRlNTQ3ZGMz&hl=en)
- Start the [Racing Car Katas](https://github.com/emilybache/Racing-Car-Katas)
  - find SOLID violations
- [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)
  - Chapter 1: Clean Code
  - Chapter 2: Meaningful Names
  - Chapter 3: Functions
  - Chapter 6: Objects and Data Structures
  - Chapter 7: Error Handling
  - Chapter 10: Classes
- [The Pragmatic Programmer](https://pragprog.com/book/tpp/the-pragmatic-programmer)
  - Chapter 2: A Pragmatic Approach
  - Chapter 5: Bend or Break
  - Chapter 6: While You Are Coding
- [The Art of Enbugging](http://www.ccs.neu.edu/research/demeter/related-work/pragmatic-programmer/jan_03_enbug.pdf): Tell, don't ask / Law of Demeter
- [YAGNI](https://martinfowler.com/bliki/Yagni.html)

## Session 2: Test-Driven Development

- [TDD by example](http://www.amazon.com/Test-Driven-Development-By-Example/dp/0321146530)
  - Study the `Part I: The Money Example` and try to practically follow the same exercise with a programming language at your choice.
- [Growing Object-Oriented Software, guided by tests](https://www.amazon.com/Growing-Object-Oriented-Software-Guided-Tests/dp/0321503627)
  - Chapter 1: What is the point of Test-Driven Development?
  - Chapter 2: Test-Driven Development with Objects
  - Chapter 4: Kick-Starting the Test-Driven Cycle
  - Chapter 5: Maintaining the Test-Driven Cycle
- [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)
  - Chapter 9: Unit Tests
- [The Clean Code Talks - Unit Testing](https://www.youtube.com/watch?v=wEhu57pih5w)
- [Effective Unit Testing](https://www.amazon.com/Effective-Unit-Testing-guide-developers/dp/1935182579)
  - Part 1: Foundations
  - Part 2: Catalog

## Session 3: Refactoring

- [Martin Fowler @ OOP2014 "Workflows of Refactoring"](https://www.youtube.com/watch?v=vqEg37e4Mkw)
- [Refactoring: Improving the design of existing code](http://www.amazon.com/Refactoring-Improving-Design-Existing-Code/dp/0201485672)
  - Chapter 1: Refactoring, a First Example
    - Try to repeat the [example Code](https://github.com/joebew42/refactoring-day/tree/master/movie-rental/java)
  - Chapter 2: Principles in Refactoring
  - Chapter 3: Bad Smells in Code
- Try to find and refactor the code smells in these Code Katas:
  - [TennisRefactoringKata](https://github.com/emilybache/Tennis-Refactoring-Kata)
  - [GildedRoseKata](https://github.com/joebew42/GildedRose)
  - What Code Smelles you have found?
    - What steps you followed to remove them?
    - What difficulties you have faced?

## Session 4: Working with Legacy Code

- [Working Effectively with Legacy Code](http://www.amazon.com/Working-Effectively-Legacy-Michael-Feathers/dp/0131177052)
  - Chapter 1: Changing Software
  - Chapter 2: Working with Feedback
  - Chapter 4: The Seam Model
  - Chapter 8: How Do I Add a Feature ?
  - Chapter 13: I Need to Make Changes, but I Don't Know What Tests to Write
  - Chapter 25: Dependency-Breaking Techniques
- [Working Effectively with Legacy Tests](http://natpryce.com/articles/000813.html)
- Try the [GildedRoseKata](https://github.com/joebew42/GildedRose)
  - Code Coverage
  - Add the new feature
  - Refactor
- Watch at these approaches to tackle the Gilded Rose Kata:
  - [All the Little Things by Sandi Metz](https://www.youtube.com/watch?v=8bZh5LMaSmE)
  - Writing test cases using Approval Tests, by Emily Bache ([Part I](https://www.youtube.com/watch?v=zyM2Ep28ED8), [Part II](https://www.youtube.com/watch?v=OJmg9aMxPDI), [Part III](https://www.youtube.com/watch?v=NADVhSjeyJA))
- Watch [Testing and Refactoring Legacy Code](https://www.youtube.com/watch?v=_NnElPO5BU0)
  - Try to repeat the [Code Kata](https://github.com/sandromancuso/trip-service-kata)
- More about [Approval Testing](http://www.methodsandtools.com/archive/approvaltest.php) and some examples:
  - [Characterization Testing](https://michaelfeathers.silvrback.com/characterization-testing)
  - [Mutation Testing](https://www.guru99.com/mutation-testing.html)
  - [Golden Master and Sampling](https://blog.thecodewhisperer.com/permalink/surviving-legacy-code-with-golden-master-and-sampling)
    - [How Not To Write Golden Master Tests](https://blog.thecodewhisperer.com/permalink/how-not-to-write-golden-master-tests)
  - Use this [code](https://github.com/jbrains/trivia) and try to test and then refactor it
    - Which is the approach you prefer to apply? Why?

## Session 5: TDD and "Friends"

- [How to Write Clean, Testable Code](https://www.youtube.com/watch?v=XcT4yYu_TTs)
- [Good Design is Easily-Learned](http://blog.scottbellware.com/2009/01/good-design-is-easily-learned.html)
- Try to learn and repeat these Katas autonomously
  - [TheBowlingGameKata](http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata)
  - [TheRomanNumeralsKata](http://www.codekatas.org/casts/roman-numerals-kata-with-audio-commentary)
- [Unit Testing](https://www.youtube.com/watch?v=wEhu57pih5w)
- [Growing Object Oriented Software, Guided by Tests](http://www.growing-object-oriented-software.com/)
  - Chapter 6: Object-Oriented Style
  - Chapter 7: Achieving Object-Oriented Design
  - Chapter 8: Building on Third-Party Code
- [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)
  - Chapter 8: Boundaries
- [The Magic Tricks of Testing by Sandi Metz](https://www.youtube.com/watch?v=URSWYvyc42M)
- [Mocks Aren't Stubs](http://martinfowler.com/articles/mocksArentStubs.html)
- Try the [StringCalculatorKata](http://osherove.com/tdd-kata-1/)
  - With [interactions](http://osherove.com/tdd-kata-2/)

## Session 6: Practice with a new Programming Language

Principles and Practices are not dependant on any particular programming language, rather they act as support or enabler to learn and get comfortable with programming languages and tools we never used before.

Now that you have learned something about _the good principles and practices of software development_, try to grab a new programming language which you never used before and try to repeat some of the Code Katas you already have done previously:

- [FizzBuzzKata](http://codingdojo.org/cgi-bin/index.pl?KataFizzBuzz)
- [TheBowlingGameKata](http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata)
- [StringCalculatorKata](http://osherove.com/tdd-kata-1/)
- [TheRomanNumeralsKata](http://www.codekatas.org/casts/roman-numerals-kata-with-audio-commentary)
- [OpeningHoursKata](https://github.com/christian-fei/opening-hours-kata)
- [Racing Car Katas](https://github.com/emilybache/Racing-Car-Katas)
- Repeat the Money Example of TDD by Example
- [GildedRoseKata](https://github.com/joebew42/GildedRose)

If you are looking for more Code Katas to learn and practice with your new programming language, try to give a look at [Kata-Log](https://kata-log.rocks/).

## Session 7: Deploy your application

- Read [The Twelve-Factor App](http://12factor.net/) before you start
- Write an `example application`
- Publish the code on a `GitHub` repository
- Organize your work in [User Stories](http://www.agilemodeling.com/artifacts/userStory.htm) (e.g. Trello)
- Setup a development environment (e.g. Vagrant/Ansible)
- Setup a CI environment (e.g. Travis)
- Deploy your application (e.g. Heroku)
- Test the deployed application
- [Continuous Delivery](http://martinfowler.com/bliki/ContinuousDelivery.html)
  - [Anatomy of the Deployment Pipeline](http://www.informit.com/articles/article.aspx?p=1621865)
- Describe your Continuous Delivery process (Can it be improved ? How ?)

## Session 8: Domain-Driven Design

- [Eric Evans - Tackling Complexity in the Heart of Software](https://www.youtube.com/watch?v=dnUFEg68ESM)
- [Domain-Driven Design Quickly](https://www.infoq.com/minibooks/domain-driven-design-quickly)
  - Chapter 1: What Is Domain-Driven Design
  - Chapter 2: The Ubiquitous Language
  - Chapter 3: Model-Driven Design
  - Chapter 4: Refactoring Toward Deeper Insight
  - Chapter 5: Preserving Model Integrity
- [Eric Evans - DDD: Putting the Model to Work](https://www.infoq.com/presentations/model-to-work-evans)
- [How to write a Repository](http://philcalcado.com/2010/12/23/how_to_write_a_repository.html)
- [Eric Evans JAX 2015 Keynote: DDD and Microservices: At last, some boundaries!](https://vimeo.com/125769142)
- Recommended readings:
  - [Domain-Driven Design: Tackling Complexity in the Heart of Software](https://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215)
  - [Implementing Domain-Driven Design](https://www.amazon.it/dp/0321834577)
  - [Domain-Driven Design Reference: Definitions and Pattern Summaries](https://www.amazon.com/Domain-Driven-Design-Reference-Definitions-Summaries/dp/1457501198)

## Session 9: Microservice Architecture

- [Microservices: A Definition of This New Architectural Term](https://martinfowler.com/articles/microservices.html)
- [GOTO 2014 • Microservices • Fowler](https://www.youtube.com/watch?v=wgdBVIX9ifA)
- [Principles Of Microservices by Sam Newman](https://www.youtube.com/watch?v=PFQnNFe27kU)
- [Microservice Trade-Offs](http://martinfowler.com/articles/microservice-trade-offs.html)
- [Microservice Architecture: Aligning Principles, Practices, and Culture](https://www.amazon.com/dp/1491956259)
  - Chapter 1: The Microservices Way
  - Chapter 2: The Microservices Value Proposition
  - Chapter 3: Designing Microservice Systems
  - Chapter 4: Establishing a Foundation
  - Chapter 5: Service Design
- [Building Microservices: Designing Fine-Grained Systems](https://www.amazon.com/Building-Microservices-Sam-Newman/dp/1491950358)
  - Chapter 1: Microservices
  - Chapter 2: The Evolutionary Architect
  - Chapter 3: How to Model Services
  - Chapter 4: Integration
  - Chapter 5: Splitting the Monolith
  - Chapter 6: Deployment
  - Chapter 7: Testing
  - Chapter 8: Monitoring
  - Chapter 11: Microservices at Scale
  - Book Reading Club: "Building Microservices" [[part I](https://www.youtube.com/watch?v=Caj-qCOniXM) - [part II](https://www.youtube.com/watch?v=zS57uYLzF1I) - [part III](https://www.youtube.com/watch?v=DAVMB_Tc00w)]
- [Practical Considerations For Microservice Architecture](https://vimeo.com/105751281)
- [Microservices Antipatterns](https://www.youtube.com/watch?v=I56HzTKvZKc)
- [Seven Microservices Anti-patterns](https://www.infoq.com/articles/seven-uservices-antipatterns)
- Transactions and consistency in distributed systems
  - [Using sagas to maintain data consistency in a microservice architecture](https://www.youtube.com/watch?v=YPbGW3Fnmbc)
  - [GOTO 2015 • Applying the Saga Pattern](https://www.youtube.com/watch?v=xDuwrtwYHu8)
- [Examples and other resources](https://gist.github.com/pdincau/8e6d42dfc44cf158e70293604bae0c17)

## Session 10: Further topics

- [TDD by example](http://www.amazon.com/Test-Driven-Development-By-Example/dp/0321146530)
  - Patterns for Test-Driven Development
- Simple Design
  - [Beck Design Rules](https://martinfowler.com/bliki/BeckDesignRules.html)
  - [Emergent Design](http://ronjeffries.com/xprog/classics/expemergentdesign/)
  - [The Four Elements of Simple Design](http://blog.jbrains.ca/permalink/the-four-elements-of-simple-design)
  - [Putting An Age-Old Battle To Rest](http://blog.thecodewhisperer.com/permalink/putting-an-age-old-battle-to-rest)
  - Chapter 12 of [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882): Emergence
- Outside-in TDD [[part I](https://www.youtube.com/watch?v=XHnuMjah6ps) - [part II](https://www.youtube.com/watch?v=gs0rqDdz3ko) - [part III](https://www.youtube.com/watch?v=R9OAt9AOrzI)]
- Clean Architeture
  - [Sandro Mancuso @ Lean Agile Scotland "Crafted Design"](https://vimeo.com/107963074)
  - [Sandro Mancuso @ Jax London 2014 "Crafted Design"](https://vimeo.com/128596005)
  - [Notes about "Crafted Design"](https://github.com/joebew42/joebew42.github.io/blob/master/notes/20150712SandroMancuso_CraftedDesign.txt)
  - [Hexagonal architecture](http://alistair.cockburn.us/Hexagonal+architecture)
  - [The Clean Architecture](https://8thlight.com/blog/uncle-bob/2012/08/13/the-clean-architecture.html)
- CQRS and Event Sourcing:
  - [Greg Young - CQRS and Event Sourcing - Code on the Beach 2014](https://www.youtube.com/watch?v=JHGkaShoyNs)
  - [Bryan Hunter - CQRS with Erlang](https://vimeo.com/97318824)
  - [Greg Young - A Decade of DDD, CQRS, Event Sourcing](https://www.youtube.com/watch?v=LDW0QWie21s)
  - [CQRS Journey](http://cqrsjourney.github.io/)
- [TDD and Software Design](https://www.youtube.com/watch?v=ty3p5VDcoOI)
- Try the [Social Networking Kata](https://github.com/sandromancuso/social_networking_kata)
- Try the [Salary Slip Kata](https://github.com/sandromancuso/salaryslipkata)
- Try the [Bank Account Kata](https://github.com/sandromancuso/Bank-kata)

## Recommended Readings

In this section I will provide a list of recommended books readings that have not been mentioned directly in this study path, but of significant importance.

- [The Nature of Software Development](https://www.amazon.com/Nature-Software-Development-Simple-Valuable/dp/1941222374)
- [Extreme Programming Explained: Embrace Change (2nd Edition)](https://www.amazon.com/Extreme-Programming-Explained-Embrace-Change-ebook/dp/B000OZ0N5S)
- [The Agile Samurai: How Agile Masters Deliver Great Software](https://www.amazon.com/Agile-Samurai-Software-Pragmatic-Programmers/dp/1934356581)
- [Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation](https://www.amazon.com/Continuous-Delivery-Deployment-Automation-Addison-Wesley/dp/0321601912)
- [Release It!: Design and Deploy Production-Ready Software](https://www.amazon.com/Release-Production-Ready-Software-Pragmatic-Programmers/dp/0978739213)
- [Beyond Legacy Code: Nine Practices to Extend the Life (and Value) of Your Software](https://www.amazon.com/Beyond-Legacy-Code-Practices-Software/dp/1680500791)
- [The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win](https://www.amazon.com/Phoenix-Project-DevOps-Helping-Business/dp/0988262509)
