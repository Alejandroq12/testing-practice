In this exercise, you will write a few practical tests for JavaScript functions using the Jest library. I should make sure I follow the AAA pattern to make my tests easier for other developers to read and understand. I will also try to use the TDD approach in practice.

#### Task 1
- Write a function *stringLength(string)* that takes any string as an argument and returns its characters count.
- Now write a test for this function.
- Next, expand the function to make it check if the string is at least 1 character long and not longer than 10 characters. Throw errors if those conditions are not met.
- Add tests for the new functionality.

#### Task 2
- Write a function *reverseString(string)* function. It should take a string as an argument and return it reversed.
- Write at least one test for this function.

#### Task 3
In this task, I will need to write several tests for each tested function. I could write all of the tests directly at the top level, but it's better to group related tests so their output is more readable. *Jest* has the `describe()` method just for that. Read about it [here](https://jestjs.io/docs/api#describename-fn) and apply it in the tests for this task:

- Write a simple *calculator* class or object, which will have 4 methods: *add*, *subtract*, *divide*, and *multiply*.
- Write at least 3 tests for each of the calculator methods.
- Group tests for each method using `describe()` method.

#### Task 4 
In this task we're going to do things differently:
- Start by writing a test for a *capitalize(string)* function. The test should make sure that this function takes a string as an argument and returns that string with the first character capitalized.
- Run your test - it should fail because I don’t have the *capitalize(string)* function implemented yet.
- Now make the tests green by implementing the *capitalize(string)* function. Think about what the minimum amount of code is necessary to pass this test and write it.


In task 4, I have just used the TDD approach for development by writing tests before writing the actual functions. Note the difference in the steps I followed here, compared with those I used in the previous 3 tasks.

## Challenge myself

*Use these questions to check what you learned during this lesson.*
- What is the next test you can write for *capitalize(string)*?
- What can go wrong with this function? For example, what happens if someone provides an integer as an input for this function?
