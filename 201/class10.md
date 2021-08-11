# Debugging and Error Handling

There are two types of errors in JavaScript. The first is a programming error, where we, the JavaScript developers, do something wrong. These types of errors are typically found using our favorite browser and our favorite debugger.

The second type of error occurs when the web page reader answers a question incorrectly, pushes the wrong button, or tries to type in a Social Security number when we’re expecting a name. Or the error can happen when we’re mixing libraries and something goes wrong between them. We’ll look at these kinds of errors first, and then we’ll get into the various browsers and their debugging capabilities.

## Error propagation

Not all problems can be prevented by the programmer, unfortunately. If your program communicates with the outside world in any way, there is a chance that the input it gets will be invalid or that other systems that it tries to talk to are broken or unreachable.

Simple programs, or programs that run only under your supervision, can afford to just give up when such a problem occurs. You’ll look into the problem and try again. “Real” applications, on the other hand, are expected to not simply crash. Sometimes the right thing to do is take the bad input in stride and continue running. In other cases, it is better to report to the user what went wrong and then give up. But in either situation, the program has to actively do something in response to the problem.

## The debugger Keyword

The debugger keyword stops the execution of JavaScript, and calls (if available) the debugging function.

This has the same function as setting a breakpoint in the debugger.

If no debugging is available, the debugger statement has no effect.

## Major Browsers' Debugging Tools

Normally, you activate debugging in your browser with F12, and select "Console" in the debugger menu.

Otherwise follow these steps:

1. Chrome
Open the browser.
From the menu, select "More tools".
From tools, choose "Developer tools".
Finally, select Console.

2. Firefox
Open the browser.
From the menu, select "Web Developer".
Finally, select "Web Console".

3. Edge
Open the browser.
From the menu, select "Developer Tools".
Finally, select "Console".

4. Opera
Open the browser.
From the menu, select "Developer".
From "Developer", select "Developer tools".
Finally, select "Console".

5. Safari
Go to Safari, Preferences, Advanced in the main menu.
Check "Enable Show Develop menu in menu bar".
When the new option "Develop" appears in the menu:
Choose "Show Error Console".
