# Exercise Details

- Create a simple String calculator with a method signature: ```int Add(string numbers)```
  - The method can take up to two numbers, separated by commas, and will return their sum. For example “” or “1” or “1,2” as inputs.

  - For an empty string it will return 0.

  - Calling Add with a negative number will throw an exception “negatives not allowed”- and the negative that was passed.

  - If there are multiple negatives, show all of them in the exception message.

  - Numbers bigger than 1000 should be ignored, so adding 2 + 1001 = 2

- Allow the Add method to handle an unknown amount of numbers.

- Allow the Add method to handle new lines between numbers (instead of commas):
  - The following input is ok: “1\n2,3” (will equal 6)

  - The following input is NOT ok: “1,\n” (not need to prove it - just clarifying)


```Source: https://kata-log.rocks/string-calculator-kata```

# TDD Basics - Red, Green, Refactor

## Learning Objective

- Learn the 3 rules of TDD
- Focus on Red, Green, Refactor Cycle
- KISS Principle - Philosophy of coding

## Notes

- TDD has 3 simple rules.
  - Never write production code before writing a failing test
  - Only write enough test to prove failure and compiler issues are considered failures.
  - Only write enough production code to pass the failing test.

- While adhering to the above 3 rules, we will write tests by following the Red, Green, Refactor methodology
  - First We write a failing Test and confirm the tests are failing (RED state)
  - We write production code to fix the failing test. And We write ONLY enough production code to pass the test (GREEN state)
  - Then we refactor both the test and production code.

- Our philosophy of coding is to following the KISS Principle
  - **K**eep **I**t **S**imple **S**tupid
  - This means few things
    - We will start with the simplest test possible and increment the complexity of the test cases as we progress
    - We will write the simplest and sometimes stupidest production code to pass the **current** failing test
    - We give high regards for the simplicity and elegance of the code we write. I.e. we believe Simple is the best
