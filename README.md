# Exercise Details

- Create a simple JEST test to prove that the framework is properly configured and working.
  - Run all the tests
  - Run selected test file
  - Run tests in watch mode

# Running JEST Tests

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
