# Part II: Foundations of Programming (Solutions)

### Basic Requirements

#### Numbers

1. Enter the following expressions into your console.

   ```js
   1 + 2
   3 * 5
   5 / 4 - 13
   5000 * 234
   1073 / 57 + 200
   ```

2. Why are the values produced by the following two expressions different? What
   are they?

   ```js
   3 + 2 * 4 - 1;        // => 10
   (3 + 2) * (4 - 1);    // => 15
   ```

   **ANSWER**: The first expression evaluates to 10 and the second expression evaluates to 15. The addition of parentheses in the second example to wrap `(3 + 2)` and `(4 - 1)` changes the order in which the code is evaluated. This is because JavaScript evaluates mathematical expressions according to an order of operations, just like in mathematics. The order is PEMDAS (Parentheses, Exponents, Multiplication, Division, Addition, Subtraction).

3. Calculate how old you are in minutes using the console.

   ```js
   // If you are 30 years old:
   30 * 365 * 24 * 60;     // => 15768000
   ```

4. What is the percentage of people in the class with brown hair? Use the
   console to find out.

   ```js
   12 / 15 * 100;     // => 80
   ```

5. Try the following expressions in the console:

   ```js
   6 % 2
   42 % 10
   5 % 2
   6 % 3
   7 % 4
   100 % 12
   ```

   What is the significance of the result? How does the `%` (modulus) operator
   work?

   **ANSWER**: The modulo operator works by dividing the first operand (the one to the left of the %) by the second operand (the  one to the right of the %) and returning the remainder of that division.

6. Try the following:

   ```js
   3 % 2
   4 % 2
   5 % 2
   6 % 2
   ```

   What do the results tell you about the first operand to the modulus operator?

   **ANSWER**: The first operand is the number being divided.

#### Strings

1. Write a string that represents your full name.

   ```js
   'Ernest Hemingway';
   ```

2. Write a string that represents your favorite food.

   ```js
   'Steak';
   ```

3. Use the `+` operator to combine (known as *concatenation*) two or more
   strings, *e.g.*:

   ```js
   // Your first and last names
   "John" + " " + "Doe"
   ```

   + Your first and last names (as shown above)
      ```js
      "Ernest" + " " + "Hemingway";
      ```
   + Your parents' full names
      ```js
      "Clarence Hemingway" + " " + "Grace Hemingway";
      ```
   + Your home town and state
      ```js
      "Oak Park" + ", " + "Illinois";
      ```

4. Fix the errors in the following strings:

   ```js
   Where are all the quotes?
   'hmm something is not right"
   'Do other ' * 'operators work with string concatenation?
   ```

   **FIXED**:
   ```js
   "Where are all the quotes?";
   "hmm something is not right";
   'Do other ' + 'operators work with string concatenation?';
   ```
  
