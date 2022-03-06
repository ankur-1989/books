# Best Agile practices

## TDD

- Use it before you build it.
- Unit tests don’t guarantee a better design but they make it easier to create one.

It is 3 step dance.

1. 1st step is to write a test that fails
2. write minimum code until all the test passes
3. Refactor to improve the code and tests
4. we get improved code and repeat the process

## Different makes a difference

Run unit tests on each supported platform and environment combination

- follow the PiE principle program intently and expressively.
- Write code to be clear not clever
- Method: Why , pre conditions, post conditions, exceptions
- Premature optimization is the root of all evil
- code in short increments. When you write and test incrementally, you tend to create methods that are smaller and classes that are more cohesive.
- To improve the knowledge rotate them through tasks
- You might arque that if a developer is exclusively assigned to work on one area, then he is going to be highly proficient in it, leading to faster development. That's true, but in the long term, you gain benefits by having multiple eyes look at a piece of code. It helps improve the overall quality of the code.
- emphasize collective ownership of code.
- be a mentor share the knowledge
- allow people to figure it out
- answer the question with another question that leads in the right direction.

## Code Reviews

- pick up game also called commit reviews.
- Pair programming

### List of code review:

1. all exception handlers are non empty
2. Can you read und understand the code?
3. Are there any obvious errors?
4. Will the code have any undesirable effect on other parts of the code?
5. Is there any duplication of the code?
6. Are there any reasonable improvements or refactoring that can improve it?
7. Similarity analyzer or jester??

## use information radiators

- You might use a poster on the wall, a website or Wiki, or a blog or RSS feed. As long as you put the information somewhere that people will look at regularly, then you're in the right place. The whole team can use information radiators to broadcast their status, code designs, cool new ideas they've researched, and so on. Now just by walking around you can get smarter, and your manager will know exactly what's up. Keep others informed. Publish your status, your ideas and the neat things you're looking at. Don't wait for others to ask you the status of your work.
