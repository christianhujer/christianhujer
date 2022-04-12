# Agile Software Engineering

## Agile
> **(1) agile adjective**
> ag·​ile | \ ˈa-jəl  , -ˌjī(-ə)l  \
> Definition of *agile*
> 1: marked by ready ability to move with quick easy grace
> an agile dancer
> 2: having a quick resourceful and adaptable character
> an agile mind
― Source: https://merriam-webster.com/dictionary/agile

## Agility
> **What to do?**
> 1. Find out where you are.
> 2. Take a small step towards your goal.
> 3. Adjust your understanding based on what you learned.
> 4. Repeat
> **How to do it?**
> Given two or more otherwise roughly equivalent alternatives, prefer the option that makes future change easier.
― "Pragmatic" Dave Thomas, https://pragdave.me/blog/2014/03/04/time-to-kill-agile.htmll

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
> 2. Communicates Intent
> 3. No Duplication
> 4. Fewest Elements
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
🧟	Zero
🧟‍♂️	One
🧟‍♀️	Many
🧟	Boundaries
🧟‍♀️	Interface Definition
🧟‍♂️	Exceptions/Errors
🧟	Simple Scenarios, Simple Solutions

