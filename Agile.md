# Agile Software Engineering

## Agile
> **(1) agile adjective**
> 
> ag·​ile | \ ˈa-jəl  , -ˌjī(-ə)l  \
> 
> Definition of *agile*
> 
> 1: marked by ready ability to move with quick easy grace  
> *an agile dancer*
> 
> 2: having a quick resourceful and adaptable character  
> an agile mind

― Source: https://merriam-webster.com/dictionary/agile

## Agility
> **What to do?**
> 1. Find out where you are.
> 2. Take a small step towards your goal.
> 3. Adjust your understanding based on what you learned.
> 4. Repeat
> 
> **How to do it?**
> 
> Given two or more otherwise roughly equivalent alternatives, prefer the option that makes future change easier.

― "Pragmatic" Dave Thomas, https://pragdave.me/blog/2014/03/04/time-to-kill-agile.htmll

See also: Shewhart Cycle, Deming Cycle, PDCA Cycle, PID Controller

## The Two Values of Software
> The **Secondary Value of Software** is its *behavior*:  
> That it does what the current users currently need without any bugs, crashes, or delays.

― Robert "Uncle Bob" C. Martin

⇒ But users and their needs change over time! Markets change!
> The **Primary Value of Software** is softness of its *structure*:  
> That it tolerates and facilitates the ongoing change for new features.

― Christian Hujer (Paraphrased form Robert C. Martin)

Credit: Robert C. Martin, "The Single Responsibility Principle" Video on cleancoders.com

## The 4 Rules of Simple Design
Purpose: Make change easier/Keep change easy
> 1. Passes the Tests
> 1. Communicates Intent
> 1. No Duplication
> 1. Fewest Elements

Credit: Kent Beck, Martin Fowler

Source: https://martinfowler.com/bliki/BeckDesignRules.html

## Test Automation Pyramid
(Interface of Exercise and Observation)  
Purpose: Make "Passes the Tests" available to different stakes.
* UI - User Interface/User Experience/Acceptance Tests, agent: User
* API - Application Programming Interface/Integration/Architecture Tests, agent: Architect
* ABI - Application Binary Interface/Unit/Developer/Micro Tests, agent: Developer

Credit: Mike Cohn, Robert "Uncle Bob" C. Martin, Christian Hujer

Sources: https://www.mountaingoatsoftware.com/blog/the-forgotten-layer-of-the-test-automation-pyramid https://twitter.com/unclebobmartin/status/1071707790366920710

## FIRST Tests
> * **F**ast
> * **I**ndepenent / **I**solated
> * **R**epeatable
> * **S**elf-Validating
> * **T**imely

## The 4 As of a Test
> * **A**rrange "**Given**" (preconditions, setup)
> * **A**ct "**When**" (exercise)
> * **A**ssert "**Then**" (verification, observation)
> * **A**nnihilate (cleanup)

Credit: Kent Beck, Robert C. Martin, "Papa" Chris Matts, Ward Cunningham

## 3 Laws of TDD
> 1. You are not allowed to write any production code unless it is to make a failing unit test pass.
> 1. You are not allowed to write any more of a unit test than is sufficient to fail; and compilation failures are failures.
> 1. You are not allowed to write any more production code than is sufficient to pass the one failing unit test.

― Robert "Uncle Bob" C. Martin, http://butunclebob.com/ArticleS.UncleBob.TheThreeRulesOfTdd

## Red-Green-Refactor
* Write failing test (red)
* Make it pass (green)
* *Refactor*

Repeat until done

Credit: Kent Beck

## ZOMBIES
* 🧟 Zero
* 🧟‍♂️	One
* 🧟‍♀️	Many
* 🧟 Boundaries
* 🧟‍♀️	Interface Definition
* 🧟‍♂️	Exceptions/Errors
* 🧟 Simple Scenarios, Simple Solutions

Credit: James W. Grenning, Christian Hujer

See also: Transformation Priority Premise, Mathematical Induction

## Ontology of Test Doubles
Mock is a Spy is a Stub is a Dummy is a TestDouble.

Fake is a TestDouble.

Credit: Robert C. Martin

## SOLID Principles
* SRP - Single Responsibility Principle: On its level of abstraction, every entity in a software system should have only one reason for change.
* OCP - Open Closed Principle: It should be possible to add features by adding new code rather than modifying existing code.
* LSP - Liskov Substitution Principle: The addition of new types shall not break any code relying on present types.
* ISP - Interface Segregation Principle: Interfaces for different users should be segregated so that they can change independently.
* DIP - Dependency Inversion Principle: To make a component reusable, break its dependencies on less generic components by inverting the dependencies.

Credit: Robert C. Martin, with modifications/updates by Christian Hujer

## Package Principles
* REP - Release Reuse Equivalence
* CRP - Common Reuse
* CCP - Common Closure
* ADP - Acyclic Dependencies
* SDP - Stable Dependencies
* SAP - Stable Abstractions

## Refactoring
> **refactoring noun**
> 
> re·​fac·​tor·​ing | \ ri-ˈfak-tər-iŋ  \
> 
> Definition of *refactoring*
> 
> 1: A change to the structure of code without changing its required behavior.  
> Without refactoring, the structure is suboptimal for adding this new behavior.

Purpose of refactoring: Increase (improve) the primary value of software (structure)/keep the primary value of software high

Credit: Martin Fowler

## Transformation
> **transformation noun**
> 
> trans·​for·​ma·​tion | \ ˌtran(t)s-fər-ˈmā-shən  , -fȯr- \
> 
> Definition of *transformation*
> 
> 1: A change to the behavior of code without changing the present structure.  
> This new red test case demands a transformation of the code that will support this new feature.

Purpose: Increase the secondary value of software (behavior)

Credit: Robert C. Martin

## Design Smells
Make change more difficult (risky, costly).
* Rigidity
* Fragility
* Inseparability (Immobility)
* Opacity
* Viscosity

Credit: Robert C. Martin

## Test
> **test noun**
> 
> \ ˈtest  \
> 
> Definition of *test*
> 
> 1: An executable speficiation by example of required behavior.
> This test verifies that a user cannot modify another user's profile.

## XP Values
* Communication
* Courage
* Feedback
* Respect
* Simplicity

Credit: Kent Beck, Ward Cunningham, Ron Jeffries, Don Wells, Cynthia Andres

## Retro Prime Directive
> Regardless of what we discover, we understand and truly believe that everyone did the best job they could, given what they knew at the time, their skills and abilities, the resources available, and the situation at hand.

― Norm Kerth, Project Retrospectives: A Handbook for Team Review

## Coupling and Cohesion
> **coupling noun**
> 
> cou·​pling | \ ˈkə-pliŋ (usual for sense 2)  , -pə-liŋ \
> 
> Definition of *coupling*
> 
> 1: A dependency that propagates change.  
> The coupling of these classes means that any change to the first class will also require changes to the other class.

> **cohesion noun***
> 
> co·​he·​sion | \ kō-ˈhē-zhən  \
> 
> Definition of *cohesion*
> 
> 1: Belonging together because of changing together.  
> The x and y attributes of a point change together so they belong together in the same data structure.
