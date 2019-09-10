# Hack Reactor: JavaScript 101 Workshop

Hey there! Ready to get your hands dirty with some code? 

In order to complete these exercises, open [repl.it](https://repl.it/) and write your code in the left-hand panel. You can run your code using the "Run" button.

**Need help? Grab an instructor, use Google search, or talk to your neighbor!**

## Slides

The lesson slides for this workshop can be found [here](https://docs.google.com/presentation/d/e/2PACX-1vSTVul9oGeIhxt7bitkxoPdNknoiZFYw66a0aDHb8OfNlNyVBnTSy9pzwzT0qzln5kGCHJiWAl4LwKR/pub?start=false&loop=false&delayms=60000).

## Exercises

### Exercise 1. Restaurant Tip Calculator

  1) Define a function named `calculateTip` and give it two arguments: `total` and `percent`

  2) Inside your function, use the `return` keyword to output a tip according to the `percent` argument.

  Extra Credit: Want to shave off the extra decimal places? [Click here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/toFixed) to learn about the `.toFixed()` function and how to use it.

In the example below, your function should output `7.965`.

```js
calculateTip(44.25, 18)
```

### Exercise 2. Picking apart a URL

  1) Define a function named `removePrefix` and give it one argument: `url`

  2) Inside your function, return the url without "www." included. Hint: Use `.slice`

  Hint: Don't forget to wrap quotes around your strings!

In the example below, your function should output `google.com`.

```js
removePrefix('www.google.com')
```

### Exercise 3. Random Number Generator

  1) Define a function named `randomNumberGen` with no arguments.

  2) Inside your function, return a random number between 1 and 10. Hint: Use `Math.random()` and `Math.floor(number)`

In the example below, your function should output a whole number between 1 and 10.

```js
randomNumberGen()
```

### Super Extra Credit: "Sentence Reverser"

  1) Define a function named `reverseSentence` with one argument: `sentence`

  2) Inside your function, return the reversed copy of the `sentence` that is passed in as an argument. Hint: Use `String.split()` `Array.reverse()` and `Array.join()`

In the example below, your function should output "!ecnetnes emosewa na si sihT".

```js
reverseSentence('This is an awesome sentence!')
```