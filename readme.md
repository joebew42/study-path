## Getting Started

- [The Pomodoro Technique](http://pomodorotechnique.com/)
- [Manifesto for Agile Software Development](http://www.agilemanifesto.org/)
- [Principles behind the Agile Manifesto](http://www.agilemanifesto.org/principles.html)
- [Manifesto for Software Craftsmanship](http://manifesto.softwarecraftsmanship.org/)

## Week 1: Introduction to TDD

- [TDD by example](http://www.amazon.com/Test-Driven-Development-By-Example/dp/0321146530): The Money Example
- [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882): chap. 9: Unit Tests

## Week 2: Working with Legacy Code

- [Working Effectively with Legacy Code](http://www.amazon.com/Working-Effectively-Legacy-Michael-Feathers/dp/0131177052): chap. 8: How Do I Add a Feature?
- Start the [GildedRose Kata](https://github.com/joebew42/GildedRose)
  - Code Coverage
  - Add the new feature
  - No refactoring!
- [Working Effectively with Legacy Tests](http://natpryce.com/articles/000813.html)

## Week 3: Refactoring

- [Martin Fowler @ OOP2014 "Workflows of Refactoring"](https://www.youtube.com/watch?v=vqEg37e4Mkw)
- [Refactoring: Improving the design of existing code](http://www.amazon.com/Refactoring-Improving-Design-Existing-Code/dp/0201485672)
  - Chapter 1: Refactoring, a First Example
    - [Example Code](https://github.com/joebew42/refactoring-day/tree/master/movie-rental/java)
  - Chapter 2: Principles in Refactoring
  - Chapter 3: Bad Smells in Code
- [Testing and Refactoring Legacy Code](https://www.youtube.com/watch?v=_NnElPO5BU0)
- Takes the code of the week 2 and try to do refactoring (find code smells)
- Try the [TennisRefactoring Kata](https://github.com/emilybache/Tennis-Refactoring-Kata) (find code smells)

## Week 4: TDD and "Friends"

- [Unit Testing](https://www.youtube.com/watch?v=wEhu57pih5w)
- [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882): chap. 8: Boundaries
- [GOOS](http://www.growing-object-oriented-software.com/): Part I and Part II
- [Mocks Aren't Stubs](http://martinfowler.com/articles/mocksArentStubs.html)
- [TDD by example](http://www.amazon.com/Test-Driven-Development-By-Example/dp/0321146530): Part III

## Week 5: Clean code

- [SOLID principles](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod)
- [How to Write Clean, Testable Code](https://www.youtube.com/watch?v=XcT4yYu_TTs)
- [The Pragmatic Programmer](https://pragprog.com/book/tpp/the-pragmatic-programmer): chap. 2, 5, 6
- [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882): chap. 2, 3, 6, 7, 10
- Start the [Racing Car Katas](https://github.com/emilybache/Racing-Car-Katas)
  - find SOLID violations

## Week 6: Hands On Erlang

- [Programming Erlang (2nd Edition)](https://pragprog.com/book/jaerlang2/programming-erlang)
- Other useful resources about Erlang: [Spawned Shelter!](http://spawnedshelter.com/)
- Try these Katas in Erlang:
  - [RomanNumerals Kata](http://codingdojo.org/cgi-bin/index.pl?KataRomanNumerals)
  - [TheBowlingGame Kata](http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata)
  - [FizzBuzz Kata](http://codingdojo.org/cgi-bin/index.pl?KataFizzBuzz)
  - [StringCalculator Kata](http://osherove.com/tdd-kata-1/)
  - [Tennis Kata](http://codingdojo.org/cgi-bin/index.pl?KataTennis)

## Week 7: Deploy your application

- Write an `example application` in Erlang
- Find a way to organize your work in [User Stories](http://www.agilemodeling.com/artifacts/userStory.htm) (e.g. Trello)
- Find a way to setup a development environment (e.g. Vagrant/Ansible)
- Find a way to setup a CI environment (e.g. Travis)
- Find a way to deploy it (e.g. Heroku)
- Find a way to test the deployed application
- [Continous Delivery](http://martinfowler.com/bliki/ContinuousDelivery.html)
- Describe your Continuous Delivery process (Can it be improved ? How ?)

## Week 8: Refinements and IDD

- Crafted Design:
  - https://vimeo.com/107963074
  - https://vimeo.com/128596005
  - [Notes](http://joebew42.github.io/notes/20150712SandroMancuso_CraftedDesign.txt)
- [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882): chap. 12
- Looking at the `example application` of the week 7:
  - What are your considerations ?
  - Can you apply `IDD` ? If yes propose the changes.
