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
