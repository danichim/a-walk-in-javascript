# A walk in JavaScript

## Preface

A lot of information has been written about JavaScript and EcmaScript since both the language creation time and the standard definition time.
The intention of this road map is to share with you one of many paths you can take to grok the language and specially to draw you to the highest quality information  (which I won't be ever able to write in a better way) in the attempt to prevent you from coming across misleading (when not completely wrong) documents outside in the wild.

Hopefully your walk will be much easier than mine!

## Table Of Contents

- [DAY 1](/day_01.md)
  - Introduction to JavaScript
    - What is JS anyway?
    - What's ECMAScript?
    - Language features quick overview
    - Myths busted
  - ES5 vs ES6
    - Relevant differences
    - Relevant improvements
    - Why are we using ES6 in this course?
    - After ES6?
  - Initial workspace Setup
    - Basic Runtime ( Node )
    - IDE ( Visual Studio Code )
    - Run Code extension
    - Introduction to NPM
- [DAY 2](/day_02.md)
  - Syntax, Grammar & Semantics
    - Statements
    - Expressions
    - Contextual Rules
  - ECMAScript Types
    - Value type groups
      - Primitives
        - Boolean
        - Null
        - Undefined
        - Number
        - BigInt ( stage-3 )
        - String
        - Symbol
      - Composite/Compound
        - Object
    - Type conversion
      - Explicit ( "type casting" )
      - Implicit ( Coercion )
  - Operators
    - Assignment operators
    - Comparison operators
    - Arithmetic operators
    - Bitwise operators
    - Logical operators
    - String operators
    - Conditional (ternary) operator
    - Comma operator
    - Unary operators
    - Relational operators
    - Destructuring
    - Operators Precedence
    - Spread/Rest
- [DAY 3](/day_03.md)
  - Objects explained
    - Objects, the big picture
    - Syntax
    - Object properties attributes (accessors, descriptors)
    - Prototype
    - Behavior Delegation
    - Exotic Objects
    - Object built-in methods
    - Standard built-in objects
- [DAY 4](/day_04.md)
  - Indexed and Keyed Collections
    - Collections family
    - The Array Object
    - Syntax
    - Array Built-in methods
    - Preliminary practice
    - Exercises
- [DAY 5](/day_05.md)
  - Control Structures
    - General definition
    - Branching
    - Grouping
    - Exception handling
    - Iteration
    - Arbitrary Jumps
    - The Iterable and the Iterator Protocol
    - Preliminary Practice
    - Exercises
- [DAY 6](/day_06.md)
  - Functions
    - General Definition
    - Function declaration (function statement)
    - Function expression
    - Function constructor
    - Constructor vs declaration vs expression
    - Properties of the Function object in the prototype chain
    - Arity & formal parameters
    - Formal parameters and the `arguments` thing
    - Functions as properties of an object
    - IIFE
    - Pure functions
    - Side Effects
  - Execution context
    - Types of Execution Context (executable code)
    - Execution Stack
    - How Execution Context is defined?
    - Articles and books used for this section
  - Scope
    - Part of a program
    - ECMAScript definition
    - General definitions
    - Examples
  - Hoisting
  - Closure
    - General definition
    - Examples
  - Can we Cheat Scope?
    - ev[a|i]l
    - with
  - Relative Concepts Readings
  - Preliminary practice
  - Exercises
- DAY 7
  - `this` Keyword
    - <https://github.com/getify/You-Dont-Know-JS/blob/master/this%20%26%20object%20prototypes/ch1.md>
    - <https://github.com/getify/You-Dont-Know-JS/blob/master/this%20%26%20object%20prototypes/ch2.md>
    - <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this>
    - BIND
    - APPLY
    - CALL
  - Strict mode
    - What happens on strict mode?
    - Semantic Differences
  - Arrow Functions
    - ...
    - ...
    - .. good practices
  - Generators
    - ..
    - ..
    - .. good practices
- [DAY 8](/day_08.md)
  - Classes
    - General definition
    - Syntax
      - `class` declaration statement
      - `class` expression
      - Class body and method definitions
    - ES6 Classes in depth
  - OOP vs Functional
    - General definitions
    - Some essential differences
    - Examples
  - Exercises
- DAY9
  - Event Loop
    - <https://github.com/Jaxolotl-Didactic-Lab/useful-info/blob/develop/web%20api%20-%20event%20loop.md>
    - <https://developer.mozilla.org/en-US/search?q=API>
    - ..
  - Asynchronous programming
    - Callback
      - <https://developer.mozilla.org/en-US/docs/Glossary/Callback_function>
      - <https://en.wikipedia.org/wiki/Callback_(computer_programming)>
    - Promise
    - Async/Await
    - .. good practices
- DAY 10
  - The runtimes
    - Web Browser
    - Node
    - MIXED ENVIRONMENT <https://github.com/getify/You-Dont-Know-JS/blob/1st-ed/types%20%26%20grammar/apA.md>
  - Javascript and the web
    - V8, SpiderMonkey, Chakra, WebKit, Hermes
    - HTML
    - CSS
    - .. good practices
- DAY 11
  - Debugging
    - <https://developer.mozilla.org/en-US/search?q=debug>
    - The console object
    - .. good practices
  - Transpilers
    - Babel
    - ...
    - .. good practices
  - Task runners & bundlers
    - Webpack
    - RollUp
    - ...
    - .. good practices
  - Unit / integration tests
    - <http://www.softwaretestingclass.com/what-is-difference-between-unit-testing-and-integration-testing/>
    - TDD
    - <https://jestjs.io/>
    - .. good practices
- DAY 12
  - Destructuring
    - <https://github.com/Jaxolotl-Didactic-Lab/useful-info/blob/develop/destructuring.md>
    - ..
    - .. good practices
  - Function composition
    - <https://github.com/Jaxolotl-Didactic-Lab/useful-info/blob/develop/currying_partialApplication_composition.md>
    - ..
    - .. good practices
