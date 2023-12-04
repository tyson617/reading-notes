# Class-10 Reading Notes

## Troubleshooting Javascript

- Name some key differences between a Syntax Error and a Logic Error.

  - Syntax Errors - in spelling, language violations
  - Logic Errors - in algorithm or flow of code


- List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.

  - In my cookie-stand lab, I’ve had several issues of variables not being defined and/or being defined but not used. The issue was that I was using the same element id when manipulating the DOM, so I wasn’t able to independently control the store details from the table, which resolved when I separated them.

- How will this topic continue to influence your long term goals?

  - Debugging is a constant requirement and skill needed to be a software engineer. Being proficient with solving errors will also decrease the frequency of it originally occurring and improving efficiency.

## Javascript Debugging

- How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?

  - The javascript debugger tool is conveniently built into the browser, and allows for a greater understanding of the code flow, runtime, and to help identify errors.

- Define what a breakpoint is.

  - Breakpoints are set in the page to pause execution and allow the developer to inspect, debug, test, and improve overall understanding of the code.

- What is the call stack?

  - A call stack is a data structure that tracks the sequence of function calls and operates on a “last in, first out” basis. This means that the last called function is the first to be resolved. This helps the developer trace the execution flow and identification of error origin.
