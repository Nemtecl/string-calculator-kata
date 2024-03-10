# Step 4

Support different delimiters:

1. to change a delimiter, the beginning of the string will contain a separate line that looks like this:
   `"//[delimiter]\n[numbers…]"`.
   for example `"//;\n1;2"` should return `3` where the default delimiter is `;` .

2. the first line is optional. all existing scenarios should still be supported

Hints:

- Start with the **simplest** test case of an empty string and move to one and two numbers
- Remember to solve things as **simply** as possible so that you force yourself to write tests you did not think about
- Remember to **refactor** after each passing test

## Continue

[step 5](./step_5.md)
