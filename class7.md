# "Programming with JavaScript" Reading Notes 📖

- The control flow is the order in which the computer executes statements in a script.
- Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops.
- Conditional structure
  - `if` `else`
- You can call functions you create for your conditions.
- Control flow means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects order of execution.
- A JavaScript function is a block of code designed to perform a particular task.
  function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
  }
  document.getElementById("demo").innerHTML = toCelsius(77);
  25 Celsius
- Using the example above, toCelsius refers to the function object, and toCelsius() refers to the function result.Accessing a function without () will return the function object instead of the function result.
    function toCelsius(fahrenheit) {
    return (5/9) *(fahrenheit-32);
         }
    document.getElementById("demo").innerHTML = toCelsius
  function toCelsius(f) { return (5/9)* (f-32); }
- Functions can be used the same way as you use variables, in all types of formulas, assignments, and calculations.
- Variables declared within a JavaScript function, become LOCAL to the function. Local variables can only be accessed from within the function.
- There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate.The expression `x = 7` is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to `7`. The expression `x = 7` is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to `7`.
- The precedence of operators determines the order they are applied when evaluating an expression.
- [My GitHub Portfolio](https://github.com/MaximoVincente/)
