# Error Handling & Debugging

## Execution Contexts

* **Global Context** - Global context is global and not in a function. There is only one per page.

* **Function Context** - code that is run inside of a function. Each function will have only one and their only context.

* **Eval context** - Code that is only executed in internal functions called `eval()`.

## Variable Scope 

* **Global Scope** - when a variable is declared globally (outside of functions) then it is a part of the global scope. if you do not use the keyword `var`then the variable will be global.

* **Function-level Scope** - variables declared in a function are function level scoped.

* **Stacks** - when a statement needs data from another function, it piles or stacks the new function on top of the current task.

* **hoisting**

* **lexical scope** - when a when is linked to the object it is defined in.

* **Try** - used as a container for a code you feel may throw an exception. If there is an issue the exception will be sent to the catch block.

* **Catch** - holds an alternative set of code that will step in to try to fix the exception from try.

* **Finally** - finally block will always run if try runs or fails . Normally is used to clean up.


Duckett, J (2011). JAVASCRIPT & JQUERY Interactive front-end web development, 449-486 

All definitions and information came from above listed publication(s).

[<===Back>](README.md)