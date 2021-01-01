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

# First Test

## Learning Objective

- Learn basics of JEST test execution.

## Notes

Ensure that the framework is working and we can execute the tests.

- Need to ensure all node packages are installed. Issue the following command at the project root

  ```npm install```

- Writing the first test as a dummy test. Start by creating a new file called ```base.test.ts``` withint ```/__tests__/``` folder.

- We will use a simple ```expect(true).toBe(true)``` to compare the boolean value 'true' to 'true'.

- Issue the following command at the project root and ensure the test is running.

  ```npm test```

- You can also issue the following command to ensure only 'base.test.ts' file is executed.

  ```npm test base.test```

- You can also run the tests in 'watch' mode. I.e. JEST will automatically run the test when we have made any changes to the source files. To run test in watch mode issue the following command at the project root.

  ```npm test base.test -- --watch```

  Obviously, if you omit the file name part 'base.test' the whole test suite will run in watch mode.
