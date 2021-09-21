# What is functional programming?

- Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

## What is a pure function and how do we know if something is a pure function?

- The function always returns the same result if the same arguments are passed in.

- How we know it ?Given the same input, will always return the same output. Produces no side effects. Relies on no external state.

## What are the benefits of a pure function?

- They’re easier to reason about
- They’re easier to combine
- They’re easier to test
- They’re easier to debug
- They’re easier to parallelize

## What is immutability?

- When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

## What is Referential transparency?

- Referential Transparency emphasizes that an expression in a JavaScript program may be replaced by its value or any other variable having the same value without changing the result of the program.

## What is a module?

- js is a simple or complex functionality organized in single or multiple JavaScript files which can be reused throughout the Node. ... Each module in Node. js has its own context, so it cannot interfere with other modules or pollute global scope. Also, each module can be placed in a separate .

## What does the word ‘require’ do?

- used to load and cache JavaScript modules.

## What do we have to do to make a module available?

- The first thing you do to get access to module features is export them. This is done using the export statement.
