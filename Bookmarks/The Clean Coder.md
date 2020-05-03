### Professionalism:
- Take Responsibility
- Do not Harm Functionality and Structure
- Work Ethic
- Know your Field
- Continuous Learning
- Practice
- Collaboration
- Mentoring
- Know Basic Business Domain of the Software

### Saying No:
- Do; or do not. There is no trying
- The higher the stakes, the more valuable no becomes
- If your “trying” does not lead to the desired outcome, you will have failed
- If you don’t have a new plan, if you don’t make a change to your behavior, if you do everything exactly as you would have before you promised to “try,” then what does trying mean?
- The temptation to be a hero and “solve the problem” is huge

### Saying Yes:
- Say. Mean. Do.

### Coding:
- typing blind is all about confidence
- If you are tired or distracted, do not code
- the worst of all is saying you are done when you know you aren’t
- It is unprofessional to remain stuck when help is easily accessible.

### Test Driven Development:
- GOTO is harmful
- TDD works
THE THREE LAWS OF TDD:
  1. You are not allowed to write any production code until you have first written a failing unit test
  2. You are not allowed to write more of a unit test than is sufficient to fail—and not compiling is failing
  3. You are not allowed to write more production code that is sufficient to pass the currently failing unit test

- the tests you write after the fact are defense. The tests you write first are offense

### Practicing:
- https://katas.softwarecraftsmanship.org/
- http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata
- http://butunclebob.com/ArticleS.UncleBob.ThePrimeFactorsKata
- http://thecleancoder.blogspot.com/2010/10/craftsman-62-dark-path.html
- Wasa is very much like a two-man kata.
- One programmer writes a unit test, and then the other must make it pass. Then they reverse roles.
- BROADENING YOUR EXPERIENCE
  1. Open Source
  2. if you are a Java programmer, contribute to a Rails project. If you write a lot of C++ for your employer, find a Python project and contribute to it.

### Acceptance Testing
- Business people want to know exactly what they are going to get before they authorize a project. Developers want to know exactly what they are supposed to deliver before they estimate the project.
- professional developers always include error bars with their estimates so that the business understands the uncertainty
- Done means done. Done means all code written, all tests pass, QA and the stakeholders have accepted. Done.
- The purpose of acceptance tests is communication, clarity, and precision
- By agreeing to them, the developers, stakeholders, and testers all understand what the plan for the system behavior is
- Acceptance tests should always be automated
- Acceptance tests are not unit tests
- Unit tests are written by programmers for programmers
- Acceptance tests are written by the business for the business (even when you, the developer, end up writing them)
- Unit tests and acceptance tests are documents first, and tests second
- Their primary purpose is to formally document the design, structure, and behavior of the system
- Make sure that all your unit tests and acceptance tests are run several times per day in a continuous integration system

### Testing Strategies
- it should be the goal of the development group that QA find nothing wrong
- Unit Tests: These tests are written by programmers, for programmers, in the programming language of the system
- Component Test: A component test wraps a component. It passes input data into the component and gathers output data from it. It tests that the output matches the input. Any other system components are decoupled from the test using appropriate mocking and test-doubling techniques.
- Integration Test: these tests assemble groups of components and test how well they communicate with each other. The tests ensure that the architectural structure of the system is sound. It is at this level that we might see performance and throughput tests.
- System Tests: These are automated tests that execute against the entire integrated system
- Manual Exploratory Tests: This is where humans put their hands on the keyboards and their eyes on the screens. These tests are not automated, nor are they scripted.
