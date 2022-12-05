# unit-3-code-analysis-practice

Using markdown, identify what the following code block does and explain how the `forEach` function works.

```js
function forEach(arr, action) {
  for (let i = 0; i < arr.length; i++) {
    action(arr[i]);
  }
}

forEach(['a', 'b', 'c'], console.log);
```
The `forEach` function is initialized to accept two values, `arr` and `action`. In the second line of code, a `for...loop` is used in order to iterate through the `arr` value. The loop will begin looping at index 0, will loop while the index value is less than the length of `arr` and will increment as the loop executes. For each iteration, the `action` will be executed onto the value represented by the index of `arr`. In the last line of code, `forEach` is invoked and an array is passed as the first argument and `console.log` is passed as the value for the argument `action`.       




**Guiding Questions:**
* What does the code do (what does it print? are any variable reassigned? etc...)
* What are the expected data types for each of the parameters?
* When the function is invoked, what value are provided as arguments?
* How does `forEach` use the provided arguments?

**Key Terms to use**: parameters, arguments, invoke/invocation, iterate, "element of the array", increment,  

<hr>

Your explanation here...
