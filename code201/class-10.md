# Ch. 10, “Error Handling & Debugging”
### ORDER OF EXECUTION
To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run.
### EXECUTION CONTEXTS
**EXECUTION CONTEXT:**
Every statement in a script lives in one of three
execution contexts:
1. GLOBAL CONTEXT
Code that is in the script, but not in a function.

2. FUNCTION CONTEXT
Code that is being run within a function.
Each function has its own function context.
3. EVIL CONTEXT (NOT SHOWN)
Text is executed like code in an internal function
called eval`()`
**VARIABLE SCOPE**
1. GLOBAL SCOPE
If a variable is declared outside a function, it can
be used anywhere because it has global scope.
If you do not use the var keyword when creating
a variable, it is placed in global scope.
2. FUNCTION-LEVEL SCOPE
When a variable is declared within a function,
it can only be used within that function. This is
because it has function-level scope

**EXECUTION CONTEXT& HOISTING**
Each time a script enters a new execution context, there are two phases
of activity:
1. PREPARE
* The new scope is created
* Variables, functions, and arguments are created
* The value of the this keyword is determined

2. EXECUTE

* Now it can assign values to variables
* Reference functions and run their code
* Execute statements

**UNDERSTANDING SCOPE**
In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object.

