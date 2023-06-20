# Q1.

### window

- parent of document (global object)

### document

- one part of the window
- your webpage

### async

- wait before execution (dependent)
- document is also asynchronus

### api

- api - application interface
- if get response then display response (async)

### promise

- if promise resolve then do (async)

### call stack

1. first execution (global execution context)

### micro task queue

- high prefernece (priority then call back)
- deal with promise, resolve, reject, async - await

### callback queue

- dom - api - will in call back queue
- setTimeInterval

### event loop

- for async task only

- esponsible for executing the code, collecting and processing events, and executing queued sub-tasks.

- check call stack (check for microtask and callback queues) - give code to call stack for execution

### creation phase and execution phase

- creation phase (Memory Execution)
- memory allocation for variables and functions

- execution phase (Code Execution)
- assiging values for variables and execute the functions

### spread operator

- destructuring non primitive datatypes like arrays and object
- shallow copy
  e.g. let arr = [1,2,3,4]
  console.log(...arr)

### rest operator

function myData(...args) {
console.log(args);
}
myData("Maria", 24, "FrontEndDeveloper");

### setTimeout

- use to delay the output with given time period

### what is setInterval

- execute code again and again after given time period

### clearInterval

- stop the execution of setInterval function

### callback functions

- functions which is pass as an argument and used to handle asynchronous tasks

### callback hell

- callback - function execution depend on another function
- what if there are many function dependent on each other
- this will become callback hell
- just nested callback functions
- disadvantage = horizontal scaling of code
- use promise (async/await) to resolve this issue

### undefine vs nan vs not defined

- undefined: declared but not assigned any value
- not-defined: variable is not declared
- nan: not a number (try to convert string to number)
