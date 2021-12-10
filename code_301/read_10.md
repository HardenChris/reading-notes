# In memory storage

## The JavaScript Call Stack - What It Is and Why It's Necessary

* What is a ‘call’?

    - call stack is primarily used for function innovation
    
* How many ‘calls’ can happen at once?

    - one call at a time.

* What does LIFO mean?

    - > LIFO (Last In, First Out ): When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out when the function returns.

* Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

    - 
    
* What causes a Stack Overflow?

    - > A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.


## Javascript Error Messages

* What is a ‘reference error’?

    - > This is as simple as when you try to use a variable that is not yet declared you get this type of errors.

* What is a ‘syntax error’?

    - > I know it’s in the name of the errors, but as it says itself, this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

* What is a ‘range error’?

    - > Try to manipulate an object with some kind of length and give it an invalid length and this kind of error will show up.

* What is a ‘tyep error’? (What is a ‘type error’? The irony is there is a type error in the question.)

    - > Like the name indicates, these types of errors show up when the types (number, string, and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

* What is a breakpoint?

    - > The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break. You can also add conditional breakpoints by right-clicking a previous set breakpoint, which will make your program stop at that point only if a condition is met, this is awesome for when you want to debug huge cycles for specific values. 

* What does the word ‘debugger’ do in your code?

    - adds a stopping point to look at.


## Things I want to know more about

Freeborn, Charles. "The JavaScript Call Stack - What It Is and Why It's Necessary" freecodecamp, 11 Jan 2018, <https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/>

Spinola, Diogo. "JavaScript error messages && debugging" codeburst.io, 17 Jul 2017, <https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c>

All definitions and information came from the above-listed publication(s).

[<===Back>](README.md)
