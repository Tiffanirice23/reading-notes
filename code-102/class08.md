|# Class 8 || Operators and Loops

### What is an expression in JavaScript?
> At a high level, an expression is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate.

> Example#1: The expression x = 7 uses the `=` operator to assign the value seven to the variable `x`. The expression evaluates to 7.

> Example #2: The expression 3 + 4 is an expression that uses the `+` operator to add 3 and 4 together and produces a value, 7. However, if it's not eventually part of a bigger construct (for example, a variable declaration like const z = 3 + 4), its result will be immediately discarded — this is usually a programmer mistake because the evaluation doesn't produce any effects.

### Why would we use a loop in our code?
> Loops offer a quick and easy way to do something repeatedly. 
You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop:

> `for (let step = 0; step < 5; step++) {Runs 5 times, with values of step 0 through 4.
console.log("Walking east one step");
}`


### When does a for loop stop executing?
> If it evaluates to true , the statement or code in the loop is executed. If it evaluates to false , the loop stops.

### How many times will a while loop execute?
> The while loop starts by evaluating condition . If condition evaluates to true , the code in the code block gets executed. If condition evaluates to false , the code in the code block is not executed and the loop ends

*Read*
- [Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
- [Loops](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)